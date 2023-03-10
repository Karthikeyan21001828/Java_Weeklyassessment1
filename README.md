# Java_Weeklyassessment_1
## 1.Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers
### Program
```
import java.util.Scanner;
public class Main1 {
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
```
### Output:
