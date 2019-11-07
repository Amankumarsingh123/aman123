#Aman Kumar Singh
#Branch CE A1
#Roll 1914009

1] program to find factorial of number.

#include<stdio.h>
#include<conio.h>
void main()
{
int n,i,fact=1;
clrscr();
printf(“enter any no:”);
scanf("%d",&n);
for(i=n;i>=1;i–)
{
fact=fact*i;
}
printf(“factorial=%d”,fact);
getch();
}

2] program to find whether given no. is a prime no.or not.

#include<stdio.h>
#include<conio.h>
void main()
{
int n,i,r=0;
clrscr();
printf(“enter any no:”);
scanf("%d",&n);
for(i=2;i<=n-1;i++)
{
if(n%i0)
{
r=1;
break;
}
if(r0)
printf(“prime no”);
else
printf(“not prime”);
getch();
}

3] program to display sum of series 1+1/2+1/3+…+n.

#include<stdio.h>
#include<conio.h>
void main()
{
int n,i,sum=0;
clrscr();
printf(“enter any no:”);
scanf("%d",&n);
printf(“1”);
for(i=2;i<=n-1;i++)
printf(" 1/%d",i);
for(i=1;i<=n;i++)
sum=sum+i;
printf(" 1/%d",n);
printf("\nsum=1/%d",sum+1/n);
getch();
}

4] program to display series and file sum of 1+2+5+…+n.

#include<stdio.h>
#include<conio.h>
void main()
{
int n,i,sum=0;
clrscr();
printf(“enter any no:”);
scanf("%d",&n);
for(i=1;<n;i+2)
{
printf("%d+0",i);
sum=sum+i;
}
printf("%d",n);
printf("\nsum=%d",sum+n);
getch();
}

5] program to show sum of 10 element of array & show the average.

#include<stdio.h>
#include<conio.h>
void main()
{
int a[10],i,sum=0;
float av;
clrscr();
printf(“enter elements of an aaray:”);
for(i=0;i<10;i++)
scanf("%d",&a[i]);
for(i=0;i<10;i++)
sum=sum+a[i];
printf(“sum=%d”,sum);
av=sum/10;
printf(“average=%2f”,av);
getch();
}

6] program to find the maximum no.in an array.

#include<stdio.h>
#include<conio.h>
void main()
{
int a[5],max,i;
clrscr();
printf(“enter element for the array:”);
for(i=0;i<5;i++)
scanf("%d",&a[i]);
max=a[0];
for(i=1;i<5;i++)
{
if(max<a[i])
max=a[i];
}
printf(“maximum no=%d”,max);
getch();
}

7] program to display a matrix.

#include<stdio.h>
#include<conio.h>
void main()
{
int a[3][2],b[3][2],i,j;
clrscr();
printf(“enter value for a matrix:”);
for(i=0;<3;i++)
{
for(j=0;<2;j++)
scanf("%d",&b[i][j]);
}
printf(“enter value for b matrix:”);
for(i=0;i<3;i++)
{
for(j=0;j<2;j++)
scanf("%d";,&b[i][j]);
}
printf("\na matrix is\n\n");
for(i=0;i<3;i++)
{
for(j=0;j<2j++)
{
printf("%d",a[i][j]);
}
printf("\n");
}
printf("\nb matrix is \n\n");
for(i=0;i<3;i++)
{
for(j=0;j<2;j++)
{
printf("%d",b[i][j]);
}
printf("\n");
}
getch();
}

8]
