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
## 6
``` c
#include<stdio.h>
void main()
{
        int n;
        printf("Enter Element N : ");
        scanf("%d",&n);
        if(n>0)
                printf("1\n");
        else
                printf("2\n");
}
```
## 7
``` c
#include<stdio.h>
void main()
{
        int a,b,c;
        printf("Enter Three Values");
        scanf("%d%d%d",&a,&b,&c);
        if(a>b && a>c)
                printf("A is greater number\n");
        else if(b>c)
                printf("B is greater number\n");
        else
                printf("C is greater number\n");
}
```
## 8
``` c
#include<stdio.h>
void main()
{
        char ch;
        printf("Enter any element");
        scanf("%c",&ch);
        if(ch=='a'||ch=='e'||ch=='i'||ch=='o'||ch=='u'||ch=='A'||ch=='E'||ch=='I'||ch=='O'||ch=='U')
                printf("%c is Vowel\n",ch);
        else
                printf("%c is consonat\n",ch);
}
```
## 9
``` c
#include<stdio.h>
void main()
{

        char ch;
        printf("Enter any element : ");
        scanf("%c",&ch);
        if((ch>64 && ch<91) || (ch>96 && ch<123))
               printf("%c is a Alphabet\n",ch);
        else
                printf("%c is a Non Alphabet\n",ch);
}
```
## 10
``` c
#include<stdio.h>
void main()
{
        int a,b;
        printf("Enter any Number : ");
        scanf("%d%d",&a,&b);
        if(a==b)
                printf("Both are Equal\n");
        else if(a>b)
                printf("%d is maximum and %d is minimum\n",a,b);
        else
                printf("%d is maximum and %d is minimum\n",b,a);
}
```
 

