# Pattern

## Aim:

## Equipment Required:

## Algorithm:

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
