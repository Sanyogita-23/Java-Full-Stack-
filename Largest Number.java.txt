package day2;
import java.util.Scanner;
public class Largestnumber {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);
		
		System.out.println("Enter a number: ");
		int a = sc.nextInt();
		int b = sc.nextInt();
		int c = sc.nextInt();
		
		if(a >= b && a >= c) {
			System.out.println("largest = "+a);
		}
		else 
			if (b >= a && b >= c) {
				System.out.println("largest = "+b);
			}
			else
			{
				System.out.println("largest = "+c);
			}
		sc.close();

	}

}
