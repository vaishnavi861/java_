# java_

import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    
        Scanner sc=new Scanner(System.in);
        System.out.println("Welcome to CMR Restaurant");
        System.out.println("Hi, enter your name:");
        String name = sc.nextLine();
        System.out.println("hey " +name+" what do you like to have");
        System.out.println("1. Dal fry - 40 \n2. Paneer butter masala - 100 \n3. chicken curry - 120 \n4. fish fry - 100 \n5. tomato curry - 30");
        System.out.println("Select from the menu:");
        int n=sc.nextInt();
        System.out.println("enter the quantity:");
        int m=sc.nextInt();
        switch(n){
            case 1: System.out.println("you selected Dal fry pay "+(m*40));
                if(sc.nextInt()==(m*40)){
                    System.out.println("Order placed kindly wait.");
                    break;
                }
                else{
                    System.out.println("Invalid amount");
                    break;
                }
            case 2: System.out.println("you selected Paneer butter masala pay "+(m*100));
                if(sc.nextInt()==(m*100)){
                    System.out.println("Order placed kindly wait.");
                    break;
                }
                else{
                    System.out.println("Invalid amount");
                    break;
                }
            case 3: System.out.println("you selected chicken curry pay "+(m*120));
                if(sc.nextInt()==(m*120)){
                    System.out.println("Order placed kindly wait.");
                    break;
                }
                else{
                    System.out.println("Invalid amount");
                    break;
                }
            case 4: System.out.println("you selected fish fry pay "+(m*100));
                if(sc.nextInt()==(m*100)){
                    System.out.println("Order placed kindly wait.");
                    break;
                }
                else{
                    System.out.println("Invalid amount");
                    break;
                }
            case 5: System.out.println("you selected tomato curry pay "+(m*30));
                if(sc.nextInt()==(m*30)){
                    System.out.println("Order placed kindly wait.");
                    break;
                }
                else{
                    System.out.println("Invalid amount");
                    break;
                }
        }
        
    

	}
}
