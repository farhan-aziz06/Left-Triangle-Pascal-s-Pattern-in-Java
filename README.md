# Left-Triangle-Pascal-s-Pattern-in-Java
Write a program to print Left  Triangle Pascal’s Pattern in Java


import java.util.Scanner;


public class Main {


    public static void main(String[] args) {
    
    
        Scanner console = new Scanner(System.in);
        System.out.println("Enter Number of Rows:");
        int row = console.nextInt();
        for (int i =1; i<= row; i++){
            for (int sp=i; sp<=row-1; sp++){
                System.out.print(" ");
            }
            for (int j = 1; j<=i; j++){
                System.out.print("*");
            }
            System.out.println();
        }
        for (int i =row-1; i>=1; i--){
            for (int sp = i; sp <=row-1; sp++ ){
                System.out.print(" ");
            }
            for (int j =1; j<=i; j++){
                System.out.print("*");
            }
            System.out.println();
        }

    }
}





output: 



Enter Number of Rows:
5

    *
   **
  ***
 ****
*****
 ****
  ***
   **
    *
