# Review

import java.util.Scanner;

public class Code2 {

	

	public static void main(String[] args) {
		
		createUserInput();
		validate();
		
		/*Scanner eben = new Scanner(System.in);
		System.out.println("Enter an integer: ");
		
		int integer = eben.nextInt();
		if(integer>0) {
		System.out.println("You entered: "+ integer);
		}*/
		/*while(integer<0)
			{
			Scanner eben1 = new Scanner(System.in);
			System.out.println("Enter a proper integer: ");
			int integer1 = eben.nextInt();
			if(integer1>0) {
				System.out.println("Accomplished");
				break;
			}
			else if(integer1<0) {
				Scanner eben2 = new Scanner(System.in);
				System.out.println("Enter a proper integer: ");
				int integer2 = eben.nextInt();
				break;
			}
			
			
		}
		 
		
		
		/*do 
		{
		
			
			System.out.println("Enter an integer: ");
		}
		while(integer < 0);*/
		/*if(integer<0 ) {
			Scanner eben1 = new Scanner(System.in);
			System.out.println("Enter an integer: ");
			
			int integer1 = eben1.nextInt();
			System.out.println("You entered: "+ integer1);
			
			
			
			
		}
		*/
			

	
		
	}
	
		public static void createUserInput() {
			Scanner eben = new Scanner(System.in);
			System.out.println("Enter an integer: ");
			
			int integer = eben.nextInt();
			if(integer>0) {
			System.out.println("You entered: "+ integer);
			
		}
		}
		public static void validate() {
			
			Scanner eben = new Scanner(System.in);
			int integer = eben.nextInt();
			while(integer<0)
			{
			Scanner eben1 = new Scanner(System.in);
			System.out.println("Enter a proper integer: ");
			int integer1 = eben1.nextInt();
			if(integer1>0) {
				System.out.println("Accomplished");
				break;
			}
			else if(integer1<0) {
				Scanner eben2 = new Scanner(System.in);
				System.out.println("Enter a proper integer: ");
				int integer2 = eben2.nextInt();
				break;
		}
			}
		}
}

