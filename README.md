# Pattern

## Aim:
To write a C# program to print a pattern.

## Equipment Required:
Visual Stdio.

## Algorithm:
```
### Step1:
Create a class and declare a variable with string datatype.
### Step2:
Use for loop to check whether the input is a palindrome or not.
### Step3:
Use if condition to check whether input is equal to the calculated number.
### Step4:
Display the results of the condition of the input using Console.WriteLine().

```

## Program:
```
using System;
using System.Data;

namespace ConsoleApp12
{
    public class pascal
    {
        public static void Main(string[] args)
        {
            int rows = 8, s = 1;
            for (int i = 0; i < rows; i++)
            {
                for (int space1 = 1; space1 < rows - i; space1++)
                {
                    Console.Write(" ");
                }
                for (int j = 0; j <= i; j++)
                {
                    if (i == 0 || j == 0)
                    {
                        s = 1;
                    }
                    else
                    {
                        s = s * (i - j + 1) / j;
                    }
                    Console.Write(s + " ");


                }
                Console.WriteLine();
            }
        }
    }
}




```

## Output:
![Screenshot (8)](https://user-images.githubusercontent.com/94508142/226585461-40438312-f6f1-4b41-a47a-66add994f246.png)


## Result:
Thus the C# to print the pattern is successfully executed.
