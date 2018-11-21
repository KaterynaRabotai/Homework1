# Homework1
package com.gmail.murkateryna;

import java.util.Scanner;

public class Hw11 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc = new Scanner (System.in);
		System.out.println("Enter a five-digit number");
		int number=sc.nextInt();
		
		int number1=number/10000;
		System.out.println(number1);
		
		int number2=number%10000/1000;
		System.out.println(number2);
	
		int number3=number%1000/100;
		System.out.println(number3);
		
		int number4=number%100/10;
		System.out.println(number4);
		
		int number5=number%10;
		System.out.println(number5);
