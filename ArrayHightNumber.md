package com.nit.skyio;

import java.util.Arrays;
import java.util.Scanner;

public class HightNumber {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
  int []arr= {20,10,40,30,90,80,69,99};
  Scanner sc=new Scanner(System.in);
  int nth=sc.nextInt();
   Arrays.sort(arr);
   System.out.println(Arrays.toString(arr));
   for(int i=arr.length-2;i>=0;i--) {
	  
		   if(arr[i]!=arr[i+1]) {
			   nth--;
			  
		   }
		   if(nth==1) {
			   System.out.println(arr[i]+" ");
		   }
		  
	   }
   
	}

}
