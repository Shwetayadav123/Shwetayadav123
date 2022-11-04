Q1) Accept age and gender from user and display the rate of interest as follow

age above 60 and gender Male (RI= 7 %)
age above 60 and gender FeMale (RI= 7.5 %)
below 60 age = RI 5%.   




package shweta;
import java.util.*;
public class age {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
Scanner sc=new Scanner(System.in);
System.out.println("Enter you age");
int a=sc.nextInt();
System.out.println("Enter your gender M for Male and F for Female");
char g=sc.next().charAt(0);
if(a>=60) {
	if(g=='f') {
		System.out.println("Rate of intrest 7.5%");
	}
	else {
		System.out.println("Rate of intrest 7.0%");
	}
	
	}
else {
		System.out.println("Rate of intrest 5.0%");
}
	}

}
