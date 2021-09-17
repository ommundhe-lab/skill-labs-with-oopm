# skill-labs-with-oopm
C++ Lab 1
// Add 2 no.
int main()
{
  int n1,n2,result;
  n1=10;
  n2=5;
  result=n1+n2;
  // cout<<"n1+n2=result",n1,n2,result;
  cout<< n1 <<" + "<< n2 <<" = "<< result;
  return 0;

  int num1,num2;
  cout<<"enter 2 number";
  cin>> num1;
  cin>> num2;
  cout<< num1 <<"user entrerd number are: "<< num1 <<" and " << num2;
  return 0;
}

//Print Number Entered by user
#include<iostream>
using namespace std;

int main()
{
  int num1,num2;
  cout<<"enter 2 number";
  cin>> num1;
  cin>> num2;
  cout<< num1 <<"user entrerd number are: "<< num1 <<" and " << num2;
  return 0;
}

 //Swap Two Numbers 
#include <iostream >
using namespace std; 
int main()
{
 int a = 1, b = 2, temp; 
 temp = a;
 a = b;
 b = temp;
 cout << "Value of a is " <<a<<endl; 
 cout << "Value of b is " <<b; 
 return 0;
}
  
 //to check whether no is even or odd 
#include <iostream>
using namespace std; 
int main()
{
 int num = 56; 
 if(num % 2 == 0)
  cout<<num<<" is even"; 
 else
  cout<<num<<" is odd"; return 0;
}
 
  java lab1
  //To Add Two Numbers
public class Main
{

 public static void main(String[] args)
 {
    int x = 14; int y = 19;
    int sum = x + y ;
    System.out.println("x + y =" +sum);
 }
}

import java.util.*;

public class MyClass {

    public static void main(String args[]) {

      int n1, n2,temp;

      Scanner sc = new Scanner(System.in);

      System.out.println("input number 1");
      n1=sc.nextInt();
      System.out.println("input number 2");
      n2=sc.nextInt();

      System.out.println(" n1 + n2=" +(n1+n2));
    }
}

//to swap two numbers public class Main
public class main{
   public static void main(String[] args){
    int n1 = 45, n2 = 56;
    System.out.println("Before swapping"); 
    System.out.println("First number = " + n1); 
    System.out.println("Second number = " + n2);
    n1 = n1 - n2;
    n2 = n1 + n2; 
    n1 = n2 - n1;
    System.out.println("After swapping");
    System.out.println("First number = " + n1); 
   System.out.println("Second number = " + n2);
 }
}

  import java.util.Scanner;

public class EvenOdd {

    public static void main(String[] args) {

        Scanner reader = new Scanner(System.in);

        System.out.print("Enter a number: ");
        int num = reader.nextInt();

        if(num % 2 == 0)
            System.out.println(num + " is even");
        else
            System.out.println(num + " is odd");
    }
}

  

 




