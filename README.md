# first.code
/*******************************************
Statement - Print Hello World
Programmer - Vineet Choudhary
Written For - https://turboc.codeplex.com
********************************************/

#include <stdio.h>
#include <conio.h>

void main()

{
       float e1,e2,e3,x,y,z;
       clrscr();

       // variable inputs
       printf("Enter the value of x: ");
       scanf("%f",&x);

       printf("Enter value of y: ");
       scanf("%f",&y);

       printf("Enter value of z: ");
       scanf("%f",&z);

       // calculations
       e1 = (4.2 * (x+y) * 5 / z);
       e2 = (0.52 * x / (y+z));
       e3 = (x+y)*(x+y);

       // getting z
       z = (e1 - e2)/e3;
       printf("value of z is %.2f",z);

       getch();
}

\\first code on github
