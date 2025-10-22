## 1
``` c
#include<stdio.h>
void main()
{
        int a,b;
        printf("Enter element a : ");
        scanf("%d",&a);
        printf("Enter element b : ");
        scanf("%d",&b);
        if(a==b)
                printf("a and b are Equal.\n");
        else
                printf("a and b are not Equal.\n");
}
```
## 2
``` c
#include<stdio.h>
void main()
{
        int a;
        printf("Enter any Number : ");
        scanf("%d",&a);
        if(a%2==0)
                printf("%d is a Even\n",a);
        else
                printf("%d is a ODD\n",a);
}
```
## 3
``` c
#include<stdio.h>
void main()
{
        int a;
        printf("Enter any number : ");
        scanf("%d",&a);
        if(a>=0)
                printf("positive number\n");
        else
                printf("negative number\n");
}
```
## 4
``` c
#include<stdio.h>
void main()
{
        int year;
        printf("Enter any Year : ");
        scanf("%d",&year);
        if( year%4==0 && year%100!=0 ||year%400==0)
                printf("%d is a leap year\n",year);
        else
                printf("%d is not a leap year\n",year);
}
```
## 5
```c
//eligible for vote
#include<stdio.h>
void main()
{
        int age;
        printf("Enter age of the candidata : ");
        scanf("%d",&age);
        if(age>17)
                printf("candidate is eligible for vote",\n);
        else
                printf("candidate is not eligible for vote",\n);
}
```
 

