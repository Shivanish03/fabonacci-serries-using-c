/*# fabonacci-serries-using-c
/*fabonacci series
// the series is : 0,1,0+1,1+(0+1),1+(1+0+1),-----so, taking a=0 and b=1 so that the addition of a and b declare result for c (third value)//
#include<stdio.h>
#include<conio.h>
int main()
{
/*declaring n,a,b,c for n=series limit ,a= first no,b=second number and c= sum of a and b (third number of series)
int n,a=0,b=1,c;
printf("enter limit:-");
scanf("%d", n);
/* starting for loop for iteration to complete the series  
for(i=0;i<=n;i++)
printf("%d", a);
/*formula to apply fabonacci series
c=a+b;
a=b;
b=c;
return 0;
}
