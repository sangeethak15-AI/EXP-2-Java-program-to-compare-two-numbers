# EXP-2-Java-program-to-compare-two-numbers

## AIM:
To compare two numbers using java programming language.

## PROCEDURE:
1.Import required packages.

2.Declare main method with the signature "public static void main(String[] args)".

3.Get two numbers as input.

4.Compare two numbers using else-if ladder.

5.Dispaly the output accordingly.
## PROGRAM:
```
import java.util.Scanner;
public class compare {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        if(a==b)
        {
            System.out.println(a+"=="+b);
        }
        else if(a>b)
        {
            System.out.println(a+">"+b);
        }
        else if(a<b)
        {
            System.out.println(a+"<"+b);
        }
        else {
            System.out.println(a+"!="+b);
        }
    }
}
```
## OUTPUT:
![image](https://github.com/sangeethak15-AI/EXP-2-Java-program-to-compare-two-numbers/assets/93992063/05f55e78-08ac-4f80-abc1-e5c124a5a5ba)


## RESULT:
To compare two numbers using java programming language was successfully done.
