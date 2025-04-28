# EX-01-Datatypes-Operators
## AIM:
Write a C program to find the character of a given ASCII value.

## ALGORITHM:
```
1.Start the program.
2.Declare three integer variable: a.
3.print the Character of ASCII Value %d is %c",a
4.End the program.
```
## PROGRAM:

```
#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    printf("Character of ASCII Value %d is %c",a,a);
    return 0;
}
```
## OUTPUT:
![Screenshot 2025-04-28 225619](https://github.com/user-attachments/assets/40a6701e-1866-487b-9e2a-c27383c5f206)


## RESULT:
The program successfully verified

# EX-02- Conditional-Statements
## AIM:
Write a program in C to read any Month Number in integer and display Month name in the word.

# ALGORITHM:
1.Start the program.
2.get input as a
3. if a==12 print "December"
4. if a==7 print"July"
5.else print "March"
8.End the program.

# PROGRAM:

```
#include <stdio.h>
int main()  
{
    int a;
    scanf("%d",&a);
    if (a==12) {
        printf("December");
    } else if (a==7) {
        printf("July");
    } else {
        printf("March");
    }
        
    
    return 0;
}
```
# OUTPUT:
![Screenshot 2025-04-28 230134](https://github.com/user-attachments/assets/78c7f0a8-1217-4c16-bed4-a8057d7b8149)


# RESULT:
The program successfully verified.
 
 
 
# EX-03- Operators-Expressions
## AIM:
Write a C program to find the perimeter of the rectangle.


## ALGORITHM:
1.Start the program.
2.Declare three float variables a,b
3.add two variables and multiply with 2
4.print "Perimeter of rectangle=%.2f units"
5.End the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    float a,b;
    scanf("%f %f",&a,&b);
    printf("Perimeter of rectangle=%.2f units",2*(a+b));
    return 0;
}
```
## OUTPUT:
![Screenshot 2025-04-28 234608](https://github.com/user-attachments/assets/0c988764-f35b-4295-a1cf-a1e9e41f0409)


## RESULT:
The program successfully verified.

# EX-04- Using Conditional Statements

## AIM:
Write a C program to find the absolute value of a number entered by the user through the keyboard without using predefined function using simple if statement?
## ALGORITHM:
1.Start the program.
2.Declare an integer variable a
3.if a==1 print "Absolute value =%d",abs(a)"
4.else print "Absolute value =%d",abs(a)"
5.End the program.

## PROGRAM:

```
#include <stdio.h>
#include <stdlib.h>
int main()
{
    int a;
    scanf("%d",&a);
    if (a==1)
    printf("Absolute value =%d",abs(a));
    else
    printf("Absolute value = %d",abs(a));
    return 0;
}
```

## OUTPUT:

![Screenshot 2025-04-28 235240](https://github.com/user-attachments/assets/e6ed52f3-892d-4f25-b5fe-df8f2637ba15)



## RESULT:
The program successfully verified.



# EX-05- To Check a number is positive or negative
## AIM:
Write a C program to read a number and check whether the number is divisible by 13 or not using  if else
## ALGORITHM:
1.	Start the program.
2. if a%13,print "Divisible by 13"
3.else print "not Divisible by 13"
4.end the program

## PROGRAM:
```
#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    if (a%13==0)
    printf("Divisible by 13");
    else
    printf("Not Divisible by 13");
    return 0;
}
```
## OUTPUT:
![Screenshot 2025-04-29 000154](https://github.com/user-attachments/assets/045a4709-abae-4e8a-9878-c314d4ba4004)


## RESULT:
The program successfully verified

