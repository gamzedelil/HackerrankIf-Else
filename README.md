# HackerrankIf-Else
package hackerranktwo;

import java.util.Scanner;

public class Main {
	

	public static void main(String[] args) {
		
		 int n;
	       
	       Scanner inp = new Scanner(System.in); 
	      
	       System.out.println("Enter the n number:");
	       n = inp.nextInt();
	       
	       if (n % 2 == 0 ) {
	    	   
	    	   if(n>=2 && n<=5) {
	  	    	   System.out.println(" Not Weird ");
	    	   }
	    	   
	    	   else if (n >= 6 && n<= 20){
	    		   System.out.println("Weird");
	    	   }
	    	   
	    	   else {
	    		   System.out.println("Not Weird");
	    	   }
	       }
	       
	       else {
	    	   System.out.println("Weird");
	    	   
	       }

	}
}

