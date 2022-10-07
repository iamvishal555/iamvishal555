/******************************************************************************

                            Online C Compiler.
                Code, Compile, Run and Debug C program online.
Write your code in this editor and press "Run" button to compile and execute it.

*******************************************************************************/

#include <stdio.h>
#include<conio.h>

void main()
{
 int a,s=0,d;
 
 printf("Enter 4 digit numbers \n");
 scanf("%d",&a);
 
 d=a%10;
 s=s+d;
 a=a/10;
     d=a%10;
     s=s+d;
     a=a/10;
     
        d=a%10;
        s=s+d;
        a=a/10;
            d=a;
            s=s+d;
 printf("\nAddition of 4 digit number%d /n",s);
            getch();
         
                }
