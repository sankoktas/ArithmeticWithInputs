# ArithmeticWithInputs
This program prompts the user for two integers and then prints their sum, difference, multiplication and average with an organized format.

import java.util.Scanner;
public class KFS_ArithmeticWithInputs_Main

{ 

    public static void main (String [] args)
    
    {
        Scanner in = new Scanner(System.in);
        System.out.print("Please enter the bigger integer: ");
        int biginteger = in.nextInt(); //gets the value for the bigger integer from the user
        
        System.out.print("Please enter the smaller integer: ");
        int smallinteger = in.nextInt(); //gets the value for the smaller integer from the user
        
        int sum = biginteger + smallinteger ; //calculates the sum
        System.out.println("Sum: " + sum);//prints the sum
       
        int difference = biginteger - smallinteger ; //calculates the difference
        System.out.println("Difference: " + difference);//prints the difference
        
        int multiplication = biginteger * smallinteger ;//calculates the product
        System.out.println("Multiplication: " + multiplication);//prints the product 
        
        double average = (biginteger + smallinteger)/2.0 ;//calculates the average
        System.out.println("Average: " + average);//prints the average
        
    }
    
}
