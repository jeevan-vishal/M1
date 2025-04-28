# EX-01-Datatypes-Operators
## AIM:
To write a program that reads three numbers and finds their sum.

## ALGORITHM:
```
1.Start the program.
2.Declare three integer variables: a, b, and c.
3.Prompt the user to input three numbers.
4.Read the three numbers using scanf().
5.Add the three numbers and store the result in a variable sum.
6.Display the sum using printf().
7.End the program.
```
## PROGRAM:
```.py
#include <stdio.h>
int main()
{
    int a,b,c;
    scanf("%d %d %d",&a,&b,&c);
    int sum=a+b+c;
    printf("Sum is:%d",sum);
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/ef88874b-610e-4b6a-8ea6-fc5236dc4231)


## RESULT:
The program successfully reads three numbers from the user, calculates their sum, and displays the result.


# EX-02- Conditional-Statements
## AIM:
To write a C program that reads any day number (1 to 7) and displays the corresponding day name.
If the input is not between 1 and 7, display "Invalid number.

# ALGORITHM:
1.Start the program.
2.Declare an integer variable day.
3.Ask the user to enter a day number (1–7).
4.Read the input using scanf().
5.Use a switch statement:

If day == 1, print "Sunday".

If day == 2, print "Monday".

If day == 3, print "Tuesday".

If day == 4, print "Wednesday".

If day == 5, print "Thursday".

If day == 6, print "Friday".

If day == 7, print "Saturday".

7.Else, print "Invalid number."

8.End the program.

# PROGRAM:
```.py
#include <stdio.h>
int main()  
{
    int a,b;
    scanf("%d %d",&a,&b);
    if(a==1){
        printf("Monday");
    }
    else if(a==2){
        printf("Tuesday");
        
    }
    else if(a==3){
        printf("Wednesday");        
    }
    else if(a==4){
        printf("Thusday");
    }
    else if(a==5){
        printf("Friday");
    }
    else if(a==6){
        printf("Saturday");
        
    }
    else{
        printf("invalid number.");
    }
    return 0;
}
```
# OUTPUT:
![image](https://github.com/user-attachments/assets/3f8046f7-180e-4a97-8083-f99fcd5e6265)


# RESULT:
The program correctly reads a day number, displays the appropriate day name if it is between 1 and 7, and shows "Invalid number." if it is outside this range.
 
 
 


# EX-03- Operators-Expressions
## AIM:
To write a C program to calculate the total, average, and percentage of marks obtained in three subjects for engineering admission.

## ALGORITHM:
1.Start the program.
2.Declare three float variables to store marks: m1, m2, m3.
3.Declare float variables for total, average, and percentage.
4.Prompt the user to enter marks of three subjects.
5.Read the marks using scanf().
6.Calculate:
total = m1 + m2 + m3
average = total / 3
percentage = (total / 300) * 100
7.Display the total, average, and percentage using printf().
8.End the program.

## PROGRAM:
```.py
#include <stdio.h>
int main()
{
   float a,b,c,total,avg,per;
   scanf("%f %f %f",&a,&b,&c);
   total=a+b+c;
   avg=(a+b+c)/3;
   per=avg;
   printf("Total marks = %.2f",total);
   printf("\nAverage marks = %.2f",avg);
   printf("\nPercentage = %.2f",per);
   return 0;
     
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/3c731311-aeae-4649-acbd-92e746ad137a)


## RESULT:
The program correctly reads three subject marks from the user, calculates the total, average, and percentage, and displays the results with two decimal places

# EX-04- Using Conditional Statements

## AIM:
To write a C program that reads a number and prints whether the number is positive, negative, or equal to 0 using an else-if conditional statement.

## ALGORITHM:
1.Start the program.
2.Declare an integer variable num to store the user input.
3.Prompt the user to input a number.
4.Use scanf() to read the number entered by the user.
5.Use an else-if conditional statement to check:
If num > 0, print "number is positive".
If num == 0, print "number is equal to 0".
If num < 0, print "number is negative".
6End the program.

## PROGRAM:
```.py
#include <stdio.h>
int main()  
{
    int a;
    scanf("%d",&a);
    if(a>0)
    {
        printf("number is positive");
    }
    else if(a<0)
    {
        printf("number is negative");
    }
    else
    {
        printf("number is 0");
    }
    return 0;
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/65a3bb6b-a212-4157-9293-9af119224389)




## RESULT:
The program successfully evaluates the input number and prints whether it is positive, negative, or equal to 0.





# EX-05- To Check a number is positive or negative
## AIM:
To write a C program that reads marks of three subjects, calculates the total and percentage, and then determines the division (First, Second, Pass, or Fail) based on the percentage and minimum marks criteria.
## ALGORITHM:
1.	Start
2.	Declare integer variables m1, m2, m3 for marks, and float variables tot, per.
3.	Input the marks for three subjects.
4.	Calculate total marks: tot = m1 + m2 + m3
5.	Calculate percentage: per = tot / 3
6.	Display total and percentage.
7.	Check if all marks are greater than or equal to 40:
8.	If yes:
a.	If percentage >= 60: Print “Division = First”
b.	Else if percentage >= 48: Print “Division = Second”
c.	Else if percentage >= 36: Print “Division = Pass”
9.	Else: Print “Division = Fail”
10.	End
## PROGRAM:
```.py
#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    switch(a)
    {
        case 9:
            printf("9 is positive.");
            break;
        case 4:
            printf("4 is positive.");
            break;
        case -7:
            printf("-7 is negative.");
            break;
    }
    return 0;
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/87878c81-ab30-4af4-88af-e6b8a2e95d99)


## RESULT:
The program successfully evaluates the input number and prints whether it is positive, negative, or equal to 0.

