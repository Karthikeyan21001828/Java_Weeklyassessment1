# Java_Weeklyassessment_1
## 1.Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers
### Program
```
import java.util.Scanner;
public class Main 
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int n1,n2;
        n1=sc.nextInt();
        n2=sc.nextInt();
        System.out.println("Sum="+add(n1,n2));
        System.out.println("Difference="+sub(n1,n2));
        System.out.println("Product="+multi(n1,n2));
        System.out.println("Division="+divi(n1,n2));
        System.out.println("Modulus="+modulo(n1,n2));
    }
    static int add(int n1,int n2)
    {
        return n1+n2;
    }
    static int sub(int n1,int n2)
    {
        return n1-n2;
    }
    static int multi(int n1,int n2)
    {
        return n1*n2;
    }
    static int divi(int n1,int n2)
    {
        return n1/n2;
    }
    static int modulo(int n1,int n2)
    {
        return n1%n2;
    }
}
```
### Output:
![image](https://user-images.githubusercontent.com/93427303/224340703-08dc9835-1f5e-43dd-908a-45fd5c36f6f2.png)

## 2.Write a Java program to compare two numbers
### Program
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int n1=sc.nextInt();
        int n2=sc.nextInt();
        if(n1==n2)
        {
            System.out.println("Both the numbers are equal.");
        }
        else
        {
            System.out.println("Both numbers are not equal.");
            if(n1>n2)
            {
                System.out.println("Since first number greater than second number.");
            }
            else
            {
                System.out.println("Since second number greater than first number.");
            }
        }
    }
}
```
### Output:
![image](https://user-images.githubusercontent.com/93427303/224342317-93ec69f7-8b6f-4d5e-838f-726d7921c668.png)

## 3.Write a Java program to convert a string to an integer
### Program
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        String s1=sc.nextLine();
        int i=Integer.parseInt(s1);
        System.out.println("Converted Number is "+i);
    }
}
```
### Output:
![image](https://user-images.githubusercontent.com/93427303/224343525-a49d6a2a-03a2-4af5-87c5-8bafde8b8f5a.png)

## 4.Java Program to find area of rhombus
### Program
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter Two diagonal of a rhombus:");
        int d1=sc.nextInt();
        int d2=sc.nextInt();
        int area=(d1*d2)/2;
        System.out.println("Area of rhombus="+area);
    }
}
```
### Output:
![image](https://user-images.githubusercontent.com/93427303/224345048-27533380-2b63-4975-a585-b20b471075d2.png)

## 5.Write a Java program to find the number of days in a month
### Program
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int mon_no=sc.nextInt();
        switch(mon_no)
        {
            case 1,3,5,7,8,10,12:
                System.out.println("Month contains 31 days.");
                break;
            case 4,6,9,11:
                System.out.println("Month contains 30 days");
                break;
            case 2:
                System.out.println("Month contains 28 days");
                break;
            default:
                System.out.println("Wrong month number.");
        }
    }
}
```
### Output:
![image](https://user-images.githubusercontent.com/93427303/224346670-a0de954c-4d92-444e-8dc4-7ff4f60225ff.png)

## 6.Write a Java program to print the even numbers from 1 to 20
### Program
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        int start=1,end=20;
        for(int i=start;i<=end;i++)
        {
            if(i%2==0)
            {
                System.out.print(i+" ");
            }
        }
    }
}
```
### Output:
![image](https://user-images.githubusercontent.com/93427303/224347361-426f6fa8-bb2d-41f1-9e8b-42e4b4ed5e78.png)

## 7.Write a Java program to create a simple calculator
### Program
```
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        int n1,n2,res;
        System.out.println("Enter Two Number:");
        n1=sc.nextInt();
        n2=sc.nextInt();
        System.out.println("Enter the operation to do\n1.Addtion\n2.Subtraction\n3.Multiplication\n4.Division\n5.Modulus");
        int op=sc.nextInt();
        switch(op)
        {
            case 1:
                res=n1+n2;
                System.out.println(n1+" + "+n2+" = "+res);
                break;
            case 2:
                res=n1-n2;
                System.out.println(n1+" + "+n2+" = "+res);
                break;
            case 3:
                res=n1*n2;
                System.out.println(n1+" * "+n2+" = "+res);
                break;
            case 4:
                res=n1/n2;
                System.out.println(n1+" / "+n2+" = "+res);
                break;
            case 5:
                res=n1%n2;
                System.out.println(n1+" % "+n2+" = "+res);
                break;
            default:
                System.out.println("Wrong process");
        }

    }
}
```
### Output:
![image](https://user-images.githubusercontent.com/93427303/224348394-32103f87-1e3d-4447-baf8-7293f5479283.png)


## 8.Write a Java program to print multiplication table of given number
### Program
```
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        System.out.print("Enter a number:");
        int num=sc.nextInt();
        System.out.println("Multiplication Table");
        for(int i=1;i<=10;i++)
        {
            System.out.println(num+"*"+i+"="+num*i);
        }
    }
}

```
### Output:
![image](https://user-images.githubusercontent.com/93427303/224349966-9beee921-fbf1-46a8-9ff9-770a8e02ffed.png)
