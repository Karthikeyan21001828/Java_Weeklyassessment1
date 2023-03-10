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

```
### Output:


