package javaPackage;
import java.util.Scanner;
public class SiAndCi {

	public static void main(String args[])
	{
		float si;
		Scanner input=new Scanner(System.in);
		System.out.println("Enter p,t,r");
		int p=input.nextInt();
		int t=input.nextInt();
		int r=input.nextInt();
		si=(p*t*r)/100;
        System.out.println("The Simple Interest is="+si);		
	}
}
