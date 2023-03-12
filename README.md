# SLACK---ASSESSMENT---1
# V R ANU AYSHWARYA 
# 212221040016

## 1.Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers

~~~java
 import java.util.Scanner;
 public class Main {
     public static void main(String[] args)
     {

        Scanner s=new Scanner(System.in);
        int a=s.nextInt();
        int b=s.nextInt();
        System.out.println("Sum of the input number:"+(a+b));
        System.out.println("Difference of the input number:"+(a-b));
        System.out.println("Product of the input number:"+(a*b));
        System.out.println("Quotient of the input number:"+(a/b));
        System.out.println("Remainder of the input number:"+(a%b));
     }
 }
 ~~~
 
 ## OUTPUT
![WhatsApp Image 2023-03-12 at 12 50 32 (1)](https://user-images.githubusercontent.com/127651217/224531313-0397f182-49ca-478b-a120-047dae90a5dc.jpeg)


## 2.Write a Java program to compare two numbers

~~~java
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        Scanner s=new Scanner(System.in);
        int x=s.nextInt();
        int y=s.nextInt();
        if(x>y)
        {
            System.out.println(x+" is greater than "+y);
        }
        else if(x<y)
        {
            System.out.println(y+" is greater than "+x);
        }
        else
        {
            System.out.println("Both inputs are equal");
        }
    }
}
~~~

## OUTPUT
![WhatsApp Image 2023-03-12 at 12 53 46](https://user-images.githubusercontent.com/127651217/224530512-2ea1fba0-140b-4583-b89a-f2bcfa6e628b.jpeg)

## 3. Write a Java program to convert a string to an integer

~~~java 
public class Main {
    public static void main(String[] args)
    {
        String sc="200";
        int i=Integer.parseInt(sc);
        System.out.println(i);
        
    }
}
~~~

## OUTPUT
![WhatsApp Image 2023-03-12 at 12 56 37](https://user-images.githubusercontent.com/127651217/224530631-0a0f7311-1dcd-492a-ba50-c13961871dce.jpeg)


## 4.Java Program to find area of rhombus

~~~java
import java.util.Scanner;
public class Main {
    public static int rhombus(int p,int q)
    {
        return ((p*q)/2);
    }
    public static void main(String[] args)
    {
        Scanner s=new Scanner(System.in);
        int dia1=s.nextInt();
        int dia2=s.nextInt();
        System.out.println(rhombus(dia1,dia2));
        
    }
}
~~~
## OUTPUT
![WhatsApp Image 2023-03-12 at 13 00 46](https://user-images.githubusercontent.com/127651217/224530782-6eaa8175-982c-4abc-9056-dc242f10a092.jpeg)

## 5.Write a Java program to find the number of days in a month

~~~java
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        Scanner s=new Scanner(System.in);
        int month=s.nextInt();
        int year=s.nextInt();
        if((month==1)||(month==3)||(month==5)||(month==7)||month==8||month==10||month==12)
        {
            System.out.println("This month has 31 Days.");
        }
        else if((month==4)||(month==6)||(month==9)||(month==11))
        {
            System.out.println("This month has 30 Days.");
        }
        else
        {
            if ((year % 400 == 0) || ((year % 4 == 0) && (year % 100 != 0)))
            {
                System.out.println("This month has 29 Days.");
            }
            else
            {
                System.out.println("This month has 28 Days.");
            }

        }
    }
}
~~~
## OUTPUT
![WhatsApp Image 2023-03-12 at 13 03 03](https://user-images.githubusercontent.com/127651217/224530872-c1e58f04-c9ab-492f-88f4-ece50f419264.jpeg)


## 6.Write a Java program to print the even numbers from 1 to 20

~~~java
public class Main {
    public static void main(String[] args)
    {
        int i;
        for(i=1;i<=20;i++)
        {
            if(i%2==0)
            {
                System.out.println(i);
            }
        }
        
    }
}
~~~

## OUTPUT
![WhatsApp Image 2023-03-12 at 13 05 08](https://user-images.githubusercontent.com/127651217/224530953-5be563a3-5a2b-418f-a7c0-82330356ec16.jpeg)

## 7.Write a Java program to create a simple calculator

~~~java
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        Scanner s=new Scanner(System.in);
        int re=s.nextInt();
        int se=s.nextInt();
        String sym=s.next();
        switch (sym)
        {
            case "+":
                System.out.println(re+se);
                break;
            case "-":
                System.out.println(re-se);
                break;
            case "*":
                System.out.println(re*se);
                break;
            case "/":
                System.out.println(re/se);
                break;
            case "%":
                System.out.println(re%se);
                break;
            case "&":
                System.out.println(re&se);
                break;
            case "|":
                System.out.println(re|se);
                break;

        }
        
    }
}
~~~
## OUTPUT
![WhatsApp Image 2023-03-12 at 13 21 52](https://user-images.githubusercontent.com/127651217/224531639-9e2bbcf8-2bc1-4e13-8a28-55f74c89b2be.jpeg)

## 8.Write a Java program to print multiplication table of given number

~~~java
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        Scanner s=new Scanner(System.in);
        int multab=s.nextInt();
        int n=s.nextInt();
        int i;
        for(i=1;i<=n;i++)
        {
            System.out.println(multab+"*"+i+"="+(multab*i));
        }
    }
}
~~~

## OUTPUT
![WhatsApp Image 2023-03-12 at 13 09 40](https://user-images.githubusercontent.com/127651217/224531104-8cd34052-72f1-4b9f-b940-0dedc33523b0.jpeg)
