# Grading-on-marks

## Aim:
To write a C# program to grade the marks.

## Algorithm:
### step 1:
Start.

### step 2:
Create a class and declare one variable with integer datatype.

### step 3:
Get marks from the User.

### step 4:
Use if and elif condition to check the grade.

### step 5:
print the grade for the given mark.

### step 6:
stop.

## Program:
```python
using System;
namespace Hello
{
    class program
    {
        static void Main(string[] args)
        {
            int marks;
            Console.WriteLine("ENTER THE MARK:");
            marks = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("\nYOUR GRADE IS:");
            if (marks > 90)
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
<img width="670" alt="image" src="https://user-images.githubusercontent.com/75235554/167237086-48eb7a7a-9b4b-4e89-8131-f56ad88be15b.png">


## Result:
Thus the C# program to grade the marks is executed successfully.

