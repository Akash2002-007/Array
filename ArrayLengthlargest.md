package com.nit.skyio;

public class Largest {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
    int []arr= {10,20,50,5};
    int largest=arr[0];
    for(int i=1;i<arr.length;i++) {
    	if(arr[i]>largest) { 
    		largest=arr[i];
    		
    	}
    }
    System.err.println("This is largest elment:="+largest);
	}

}
