# USING-IF-ELSE-STATEMENT
package pkgif.pkgelse;
import java.util.Scanner;

public class IfElse {
    public static void main(String[] args) {
        // TODO code application logic here
        Scanner sc = new Scanner(System.in);
        System.err.println("Enter a number:");
        int n =sc.nextInt();
        int i;
        if (n%2==0){
            System.err.println("It is a even number");
        } 
        else{
            System.err.println("It is a odd number");
        }
    }
    
}

o/p
run:
Enter a number:
12
It is a even number
BUILD SUCCESSFUL (total time: 15 seconds)
