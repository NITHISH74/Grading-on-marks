# Grading-on-marks

## Aim:
To write a C# program to grade the marks.
## Algorithm:
### Step 1:
Start the C# program in Visual studio 2022.

### Step 2:
Create a class and declare one variable with integer datatype.
### Step 3:
Get marks from the User.


### Step 4:
Use if and elif condition to check the grade.
### Step 5:
print the grade for the given mark.
### Step 6:
Save the program and Run the program.
### Step 7:
Take the screenshot of the output of the program.

## Program:
```
using System;
namespace hello
{
    class program
    {
            static void Main(string[] args)
            {
            int marks;
            Console.WriteLine("ENTER THE MARK:");
            marks = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("\nYOUR GRADE IS:");
            if (marks>90)
                Console.WriteLine("O GRADE");
            else if (marks > 80)
                Console.WriteLine("A+ GRADE");
            else if (marks > 70)
                Console.WriteLine("A GRADE");
            else if (marks > 60)
                Console.WriteLine("B+ GRADE");
            else if (marks > 50)
                Console.WriteLine("B GRADE");
            else if (marks >= 40)
                Console.WriteLine("C GRADE");
            else
                Console.WriteLine("FAIL");

        }
    }
}
```

## Output:
![image](https://user-images.githubusercontent.com/94164665/167250398-06c1383a-dbbc-4d09-8dfc-2146cf36ad79.png)

## Result:
Thus the C# program to grade the marks is executed successfully.

