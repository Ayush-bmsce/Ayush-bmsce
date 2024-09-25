1. 1.Program to print "Hello world"
2. public class helloWorld{
3.     public static void main(String[] args){
4.         System.out.print("Hello World");
5.     }
6. }

7. 2.Program to check if a number is prime or not.

8. public class isPrime{
9.    public static void main(String[] args){
10.        int a = 11;
11.        int factor = 0;
12.        for(int i = 2; i < a/2 + 1; i++){
13.            if(a % i == 0){
14.                factor++;
15.            }
16.       }
17.       if(factor == 0){
18.           System.out.print("Yes the number is prime");
19.       }else{
20.           System.out.print("No the number is not prime");
21.       }
22.     }
23.  }

24.   3.Program to print fibonacci series.

25.   public class fibNum{
26.     public static void main(String[] args){
27.     int n = 5;
28.     int n1 = 0, n2 = 1, n3 = 0;
29.     System.out.println("First two numbers are", n1, n2);
30.     for(int i = 1; i < n; i++){
31.         n3 = n2 + n1;
32.         n1 = n2;
33.         n2 = n3;
34.         System.out.println(n2);
35.     }
36.     }
37. }


4. Program to check if a triangle is scalene, isosceles or equilateral.


public class ifTriangle{
  public static void main(String[] args){
    int a = 6, b = 5, c = 6;
    if(a == b && b == c && a == c){
      System.out.print("It is an equilateral triangle");
    }else if(a == b||b == c||a == c){
      System.out.prinln("It is an isosceles triangle");
    }else{
      System.out.println("It is a scalene triangle");
    }
    }
}

5.Program to calculate simple interest.

public class SI{
 public static void main(String[] args){
   int interest = 15, time = 5, principal = 1000;
   int SI = interest*time*principal/100;
   System.out.print("Special interest is : ", SI);
 }
}


6.Program to swap two numbers.
public class swapNum{
  public static void main(String[] args){
    int a = 6, b = 7;
    System.out.println("Before swap a = "+ a +  " b = "+ b);
    int temp = a;
    a = b;
    b = temp;
    System.out.println("After swap a = "+ a +  " b = "+ b);
  }
}
