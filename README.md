# Largest-of-three-numbers
## Aim:
To write a C# program to find the largest of three numbers

## Algorithm:
### Step1: 
Start
### Step2:
Create a class and declare three variable with integer datatype
### Step3:
Use if condition to check whether num1 is largest than num2 and num3
### Step4:
Use elif condition to check whether num2 is largest than num1 and num3
### Step5:
Use else condition to display that third variable is largest among all the variables
### Step6:
stop

## Program:
```python3
using System;
namespace Hello
{
    class Scope
    {
        public static void Main(string[] args)
        {
            int a;
            int b;
            int c;
            Console.WriteLine("Enter the numbers");
            a = Convert.ToInt32(Console.ReadLine());
            b = Convert.ToInt32(Console.ReadLine());
            c = Convert.ToInt32(Console.ReadLine());
            if (a>b) {
                if (a>c) {
                    Console.WriteLine("Largest Number is: " + a);
                }
                else
                {
                    Console.WriteLine("Largest Number is: " + c);
                }
            }
            else
            {
                Console.WriteLine("Largest Number is: " + b);
            }
        }
    }
}
```
## Output:

![image](https://user-images.githubusercontent.com/75235167/163827274-8da14142-3c9d-40eb-9daa-499018423d8d.png)

## Result:
Thus the C# program to find the largest of three numbers is executed successfully
