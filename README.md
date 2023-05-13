# JAVA_FULLSTACK_EXPERIMENT3
## AIM :
TO Write a Java program to find the number of day in a month

## SOFTWARE REQUIRED :
IntelliJ IDEA COMMUNITY EDITION

## ALGORITHM :
To find the number of day in month in Java, you can use the following algorithm:

### 1.Take input from the user for the month and store it in a variable
### 2.Create a switch statement based on the month variable.
### 3.For each case, print the corresponding number of days and break out of the switch statement.
### 4.Handle the special case of February separately, considering leap years. If the month is February, check if it's a leap year. If it is, print 29 days otherwise, print 28 days.
### 5.If the input month does not match any of the cases, display an error message indicating an invalid month.

## PROGRAM:
```
import java.util.Scanner;
public class days
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter month no. : ");
        int month = sc.nextInt();
        switch(month)
        {
            case 1:
                System.out.println("31 days");
                break;
            case 2:
                System.out.print("Enter the year: ");
                int year = sc.nextInt();
                if ((year % 4 == 0 && year % 100 != 0) || year % 400 == 0) {
                    System.out.println("29 days");
                } 
                else{
                    System.out.println("28 days");
                }
                break;
            case 3:
                System.out.println("31 days");
                break;
            case 4:
                System.out.println("30 days");
                break;
            case 5:
                System.out.println("31 days");
                break;
            case 6:
                System.out.println("30 days");
                break;
            case 7:
                System.out.println("31 days");
                break;
            case 8:
                System.out.println("31 days");
                break;
            case 9:
                System.out.println("30 days");
                break;
            case 10:
                System.out.println("31 days");
                break;
            case 11:
                System.out.println("30 days");
                break;
            case 12:
                System.out.println("31 days");
                break;
            default:
                System.out.println("Invalid Month");
        }
    }
}
```
## OUTPUT:
![image](https://github.com/anithapalani2123/JAVA_FULLSTACK_EXPERIMENT3/assets/94184990/29f86301-b437-441c-94c3-b7a5d2bb183d)

## RESULTS:
Thus, the code of find the number of day in month in java is executed successfully and obtain the result.
