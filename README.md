# cen4802
Janet Malavet


import java.util.*;
public class firsmethod
{
	//returning the nth fibonacci sequence
      public static int fibonacci(int n)
    {
    //if n = 1 or fewer, then return n
    if (n <= 1)
       return n;
    //recursively bring the function fibonacci
    return fibonacci(n-1) + fibonacci(n-2);
    }
    //main method 
    public static void main (String args[])
    {
    //delare variable n
    int n;
    //create scanner class object
    Scanner scnr=new Scanner(System.in);
    //get value of n 
    System.out.println("Enter value of n: ");
    n=scnr.nextInt();
    //print nth number in sequence
    System.out.println("The "+n+"th term of the Fibonacci sequence is "+fibonacci(n));
}
}
