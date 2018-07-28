# Session3-Ex11

//  را چاپ کند(A)ب ن ک نمره دانشجویی را گرفته اگر نمره کمتر از 10 بود 
//  را چاپ کند(B) اگر نمره بین 10 تا 12 بود 
//  را چاپ کند(C) اگر نمره بین 12 تا 13 بود 
//  را چاپ کند(D) اگر نمره بین 14 تا 18 بود 
//  را چاپ کند(F) اگر نمره بین 18 تا 20 بود 
//  را چاپ کند(K) اگر نمره بین 0 تا 20 نبود 

package com.personal.ex11;

import java.util.Scanner;

public class ex11 {

	public static void main(String[] args) {

		Scanner sc= new Scanner(System.in);
		System.out.println("Enter a Number");
		int average;
		average= sc.nextInt();
		
		if(average<=10)
			System.out.println("A");
		else if(average>= 10 && average<=12)
			System.out.println("B");
		else if(average>= 12 && average<=13)
			System.out.println("C");

		else if(average>= 14 && average<=18)
			System.out.println("D");
		else if(average>20 && average<0)
			System.out.println("K");
		
	

	}

}




