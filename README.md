# 9-9_User_input
package com.company;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
	Scanner keyboard = new Scanner(System.in);
	String name = keyboard.nextLine();
	double gpa = keyboard.nextDouble();
	int credits=keyboard.nextInt();
	double major_gpa= keyboard.nextDouble();
	double account_balance=keyboard.nextDouble();

	System.out.println("name: " + name);
	System.out.println("gpa :" + gpa);
	System.out.println("credits:" + credits);
	System.out.println("major gpa"+ major_gpa);
	System.out.println("Account Balance=" + account_balance);
if (gpa > 1.0 && credits > 120 && account_balance==0 && major_gpa>=2.5)
{
	System.out.print("Can Graduate");
}else
{
	System.out.print("Can Not Gradaute");
}
System.out.print(name.charAt(1));

    }
}
