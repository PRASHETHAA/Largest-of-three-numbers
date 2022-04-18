# Largest-of-three-numbers
## Aim:To write a C# program to find the largest of three numbers

## Algorith:
Step1:
Start

Step2:
Create a class and declare three variable with integer datatype

Step3:
Use if condition to check whether num1 is largest than num2 and num3

Step4:
Use elif condition to check whether num2 is largest than num1 and num3

Step5:
Use else condition to display that third variable is largest among all the variables

Step6:
stop

## Program:
using System;  
public class Exercise8  
{  
    public static void Main()
{
    int num1, num2, num3;
    Console.Write("\n\n");
    Console.Write("Find the largest of three numbers:\n");
    Console.Write("------------------------------------");
    Console.Write("\n\n");

    Console.Write("Input the 1st number :");
    num1 = Convert.ToInt32(Console.ReadLine());
    Console.Write("Input the  2nd number :");
    num2 = Convert.ToInt32(Console.ReadLine());
    Console.Write("Input the 3rd  number :");
    num3 = Convert.ToInt32(Console.ReadLine());
 
  if (num1 > num2)
    {
        if (num1 > num3)
        {
            Console.Write("The 1st Number is the greatest among three. \n\n");
        }
        else
        {
            Console.Write("The 3rd Number is the greatest among three. \n\n");
        }
    }
    else if (num2 > num3)
        Console.Write("The 2nd Number is the greatest among three \n\n");
    else
        Console.Write("The 3rd Number is the greatest among three \n\n");
}
}

## Output:

![largest](https://user-images.githubusercontent.com/75234942/163844139-05f4d57f-9666-49f6-b8eb-7822585f22cc.png)

## Result:
Thus the C# program to find the largest of three numbers is executed successfully
