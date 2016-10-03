# review
import java.util.Scanner;

//gjg
/*
 * Collin Palmer
 * 10/3/16
 * Review for first exam
 * COSC 111
 */
public class classwork {
   // review sheet
	 public static void main(String[] args) {
	     //Variables-Identifier
		//Naming Rules:
		 //1. you can use letter,numbers,underscore
		 //2. it can not start with digit
		 //3. can not be keyword or reserve word
		 
		 //types:
		 //int-integer -2billion thru 2billion
		 int numofhours=0;
		 //flaot double - floating number
		 double gpa=0.0;
		 // String- any text("")
		 String address="";
		 // char-any single character('')
		 char character =' ';
		 // boolean - true and false
		 boolean correct=true;
		 
		 //assignment statement variable 
		 // =value,expression,variable
		 gpa=numofhours*3;
		 
		 
		 //constant
		 final int FREEZE =32;
		 
		 //expressions (*,/,%,-,+,+=,-=,*=,/=,%=,++,--)
		 // order of operation
		 //(),*,/,+,- PMDAS
		 System.out.println("5/2");//2
		 System.out.println("5/2*2.0");//4.0
		 System.out.println("5.0/2*2");//5.0
		 System.out.println(numofhours++);//0 post
		 System.out.println(++numofhours);//1 pre
		 System.out.println(5%7);// 5
		 System.out.println(7%5);//2
		 
		 //Casting
		 // n=(int)(3.4)   
		 // (char)(66)=B
		 // double to int, int to char, char to int
		 gpa= (double)(3);//3.0
		 
		 
		 
		//String has methods
		 // length
		 //equals , compares to strings
		 //tolowercase,touppercase
		 //trim
		 //substring
		 // indexOf
		 address="8075 west Morley";
		 System.out.println(address.length());
		 System.out.println(address.substring(0,4));// display first 4 characters
		 //End Chapter 1
		 
		 //Chapter2
		 //print,println,printf
		 //Scanner
		 
		 //print will print text and stay on same lime
		 //println makes it a new line
		 //printf will format text and print it
		 // formats %s for strings %d,integers, 
		 //%c chars, %f floating point numbers,%n new line
		 //can use a number between % and letter
		 //the width of the formatted output
		 System.out.printf("%41s",address);//-41 put spaces at end
		 System.out.printf("%4.2f",gpa);
		 
		 //Scanner
		 Scanner keyb=new Scanner(System.in);//for reading
		 gpa=keyb.nextDouble();
		 address=keyb.nextLine();
		 numofhours=keyb.nextInt();
		 character=keyb.next().charAt(0);//single character at 0 position
		 keyb.close();

	}

}
