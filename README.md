# sum-of-n-numbers-using-recursion
using recursion in java


import java.util.*;
import java.io.*;

public class HelloWorld{

     public static void main(String []args)
     {
         Scanner sc=new Scanner(System.in);
         int n=sc.nextInt();
         int res=check(n);
         System.out.println(res);
     
     }
     static int check(int n)
     {
         if(n==1)
         {
             return 1;
         }
         return n+check(n-1);
     }
}
