# JAVA Assignment.


Q1]  prepare a code to check the voters eligibility. Take a variable int age. if age is greater than 18 
print. "eligible" else print " not eligible"

--->

package rohan;
import java.util.Scanner;
public class voter {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
    Scanner sc = new Scanner(System.in);
    int age;
    
    System.out.println("Enter your age : ");
    age = sc.nextInt();
    System.out.println(age);
    
    if(age>18) {
    	System.out.println("eligible");
    	
    }
    else {
    	System.out.println("not eligible");
    }
	}

}

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q2] Swap two variables without using third variable.

--->

package rohan;

import java.util.Scanner;


public class swapping {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
    Scanner sc = new Scanner(System.in);
    int a;
    int b;
    
    System.out.println("enter your first no. : ");
    a = sc.nextInt();
  ;
    System.out.println("enter your second no. : ");
    b = sc.nextInt ();
    
    System.out.println("value before swapping = a = " + a + " b = " + b);
    
    a = a + b;
    b = a - b;
    a = a - b;
    
    System.out.println("value after swapping = a = " + a + " b = " + b);
    
	}

}


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Q3]Create a code to check the length of a string = "Hi I’m learning in PFE, I will become a 
developer". Now if the length is greater than 28 change the string to "I will become a 
developer". and print "Successfully changed."

--->

package rohan;

import java.util.Scanner;
public class changedata {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		Scanner sc= new Scanner(System.in);
		System.out.println("Enter the text : ");
		String str=sc.nextLine();
		int leng = str.length();
		String a,b,c;
		if(leng>=28) {
			System.out.println("Successfully changed ");
		}else {
			
			System.out.println("I will become a developer");
		}		
		
		System.out.print("Enter A String : ");
		a=sc.nextLine();
		System.out.print("Enter B String : ");
		b=sc.nextLine();
		
		a=b;
		b=c;
		c=a;
		
		System.out.println("After switching the values : ");
		System.out.println("value of A is "+a);
		System.out.println("value of b is "+b);
	}
}

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q4]Change two strings with using third variable

--->

package rohan;

import java.util.Scanner;
public class changetwostring {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		Scanner scan=new Scanner(System.in);
		String a,b,c;
		
		System.out.print("Enter A String : ");
		a=scan.nextLine();
		System.out.print("Enter B String : ");
		b=scan.nextLine();
		
		a=b;
		b=c;
		c=a;
		
		System.out.println("After switching the values : ");
		System.out.println("value of A is "+a);
		System.out.println("value of b is "+b);
	}
}
 
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q5] Create a Java program to print your details, like name, address, phone number, blood group 
etc. 

--->

package rohan;

public class printditals {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		String name="rohan magar";
		String address="ta & dist. Dharashiv";
		String bloodgroup="B+";
		long phone= 8767189551;
		System.out.println(name);
		System.out.println(address);
		System.out.println(bloodgroup);
		System.out.println(phone);
	}
}

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q6]Create a Java program to change the value of a given variable, for example a is iniƟalzed as 
10 and make it to 20.

--->

package rohan;


public class change10to20 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		int a=10;
		System.out.println("value of a is : " + a*2);	
	}
}


----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q7]Write a Java program to print the sum of three numbers.

--->

package rohan;

import java.util.Scanner;
public class sumof3numbers {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner s= new Scanner(System.in);
		int a,b,c;
		System.out.print("Enter value of A : ");
		a=s.nextInt();
		System.out.print("Enter value of B : ");
		b=s.nextInt();
		System.out.print("Enter value of C : ");
		c=s.nextInt();
		System.out.println(a+b+c);
	}
}

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q8]Write a Java program to print square of a number. 

--->

package rohan;

import java.util.Scanner;
public class Square {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Scanner b=new Scanner(System.in);
		System.out.print("Enter number ");

		int a=b.nextInt();
		
		System.out.println(a*a);
		
	}

}

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q9]Write a java program which iniƟalizes a variable name and greets with "Hello , rohan have a good 
day"

--->

package rohan;

public class addstring {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		String a="rohan";
		
		System.out.println("Hello " + a+" have a good day");	
	}
}

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q10]Try to understand what happens when type casƟng is done from char to int and int to char

--->

package rohan;


public class typecasting {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		char b='a';
		System.out.println(" Typecasting is "+((int) b));
	}

}

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q11] Try to print the length of you name and full name, and then print the difference between the 
characters of the first name and last name. For example: F_name - Nilkanth L_name - Java 
Output for the above should be 4. 

--->

package rohan;

import java.util.Scanner;
public class Diffrancebetweenlength {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		Scanner name= new Scanner(System.in);
		System.out.print("Enter your First name : ");
		String Fname=name.nextLine();
		System.out.print("Enter your Last name : ");
		String Lname=name.nextLine();
		
		int fnl=Fname.length();
		int lnl=Lname.length();
		if(fnl>lnl){
			System.out.println("Diffrance is : "+(fnl-lnl));
		}else {
			System.out.println("Diffrance is : "+(lnl-fnl));
		}	
	}
}

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q12]Check what is the number of leƩer for "K" String: ABCDEFGHIJKLMNOPQRSTUVWXYZ 
Example: for D number should be 4

--->


package rohan;

import java.util.Scanner;
public class arrayfindvalueofk {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		String array[]= {" ","A","B","C","D","E","F","G","H","I","J","K","L","M","N","O","P","Q","R","S","T","U","V","W","X","Y","Z"};
		String k="B";
		for(int i=0;i<=27;i++) {
			if(array[i]==k) {
				System.out.println(i);
			}
}
	}

}


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q13] Concatenate two Strings Example for two Strings:: String a= Nilkanth String b= Java Output NilkanthJava 

--->

package rohan;

public class concatenate2string {

	public static void main(String[] args) {
		
		String str="Nilkanth";
		String str1="java";
		System.out.print(str+str1);
	}
}

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q14] Concatenate one String and one integer. Example for one String and two integer: String a = 
Nilkanth int b = 6197 int c = 1234 Output: Nilkanth619712344

--->

package rohan;


public class intandstrinconcat {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		String str="Nilkanth";
		int in1=6197;
		int in2=1234;
		
		System.out.println(str+in1+in2);

	}

}

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



Q15]Print the mathemaƟcal table for anynumber. 

--->

package rohan;

import java.util.Scanner;
public class tableof5 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Scanner s=new Scanner(System.in);
		System.out.print("Enter NUmber For whose table is to be printed : ");
		int a=s.nextInt();
		for(int i=1;i<=10;i++) {
			System.out.println(a*i);
		}	
	}
}



----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q16] Write a program in Java to find the first 10 natural numbers. Sample output:The natural 
numbers are:1 2 3 4 5 6 7 8 9 10

--->

package rohan;


public class printpositivenumber {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int a=10;
		for(int i=0;i<=a;i++) {
			System.out.println(i);
		}
		
	}

}


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q17] Write a program to find the factorial value of any number entered through the keyboard.
 
--->

package rohan;


public class factorofnumber {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		int a=5,b=a,c=1;
		while(a/b!=a){
			c=c*b;
			b--;
			}
		
		System.out.println(c);
	}

}


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q18] Print first 30 even numbers and the total of them. 

--->

package rohan;


public class printevennumber {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
int a=30,b=0;

for(int i=0;i<=a;i++) {
	
	if(i%2==0) {
		b=i+b;
	}
}
System.out.println(b);
	}
}

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q19] Print the below pattƩern. 

//******
//******
//******
//******
//******
//******

--->

package rohan;

public class patternI {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		
		for(int i=0;i<=5;i++) {
			for(int j=0;j<=5;j++){
				System.out.print("*");
			}
			System.out.println();
		}
	}
}


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q20] Print the below pattƩern.
*
**
***
****
*****
******

--->

package rohan;


public class patternI {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		
		for(int i=0;i<=5;i++) {
			for(int j=0;j<=i;j++){
				System.out.print("*");
			}
			System.out.println();
		}
	}
}


----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q21] Print the below pattƩern.
     * 
    * * 
   * * * 
  * * * * 
 * * * * * 

--->

package rohan;


public class pattranI {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		
		for(int i=5;i>0;i--) {
			for(int j=0;j<=5;j++){
				if(j>=i) {
				System.out.print("* ");}
				else {
					System.out.print(" ");
				}
			}
			System.out.println();
		}
	}
}


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q22] Print the below pattƩern.
     1 
    2 2 
   3 3 3 
  4 4 4 4 
 5 5 5 5 5 

--->

package rohan;

public class pattranI {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		int p=1;
		for(int i=5;i>0;i--) {
			for(int j=0;j<=5;j++){
				if(j>=i) {
				System.out.print(p+" ");}
				else {
					System.out.print(" ");
				}
			}
			p++;
			System.out.println();
		}
	}
}


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Q23] Prepare a basic calculator mechanism using a switch in java. AddiƟon, subtracƟon, 
mulƟplicaƟon, division, squared.

--->

package rohan;
		Scanner name = new Scanner(System.in);
		String stra="Enter Value of A : ";
int a = name.nextInt();
String strb="Enter Value of B : ";
int b=name.nextInt();


		int add=a+b;
		int s=a-b;
		int m=a*b;
		int div=a/b;
		System.out.println("Addataion of A and B is "+ add);
		System.out.println("substracatation of A and B is " + s);
		System.out.println("Multyplacatation of A and B is " + m);
		System.out.println("Dividatation of A and B is " + div);

	}

}

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
