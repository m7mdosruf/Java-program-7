package homwork2;

import java.util.Scanner;

public class test6 {

public static void main(String[] args) {
Scanner n = new Scanner(System.in);
System.out.print("Enter the number of stars(*) you want at the base of the triangle = ");
int x=n.nextInt();
System.out.println("=============================================================================");
String z = "*";
String c = "*";
for (int i = 0 ; i<x ; i++) {

for (int m = 0 ; m<x-i ; m++) 
    System.out.print(" ");
System.out.println(c);
    c=c+z ;
}
System.out.println("=============================================================================");
System.out.println("                              Good bay                                     ");
       
        
        
    
}
    
}
