/*
 * Exercise 20.9
 * 
 * "(Print the characters in a string reversely) Write a recursive method 
 * that displays a string reversely on the console using the following header:
 * 			public static void reverseDisplay(String value)
 * 
 * Created: 2014.01.11
 * 
 * Author: Aleksander V Grunnvoll
 */

import java.util.Scanner;


public class Ex_20_9 {

	public static void main(String[] args) {
		Scanner input = new Scanner(System.in);
		System.out.print("Enter string to reverse: ");
		String str = input.nextLine();
		System.out.println();
		reverseDisplay(str);
	}
	
	
	public static void reverseDisplay(String value) {
		
		// Base case
		if(value.length() == 0)
			return;
		
		System.out.print(value.charAt(value.length() - 1));
		reverseDisplay(value.substring(0, value.length() - 1));
		
	}
	
}
