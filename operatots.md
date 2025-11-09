## qu2
```c
#include<stdio.h>
int main()
{
int a=10;
int b=2;
int c;
c=(a&b);
printf("c=%d",c);
return 0;
} 
```
## qu3
```c
#include<stdio.h>

#define MOBILE 0x01
#define LAPPY 0x02

int main()
{
    unsigned char item = 0x00;
    item |= MOBILE;
    item |= LAPPY;
    printf("I have purchased.....:");
    if(item & MOBILE){
        printf("Mobile,");
    }
    if(item & LAPPY){
        printf("Lappy");
    }

    return 0;
}
```
## qu4
``` c
#include<stdio.h>
int main()
{
char var=0x04;
var=var|0x04;
printf("%d,",var);
var|=0x01;
printf("%d",var);
return 0;
}
```
## qu5
``` c
#include<stdio.h>
int main()
{
char flag=0x0f;
flag&=~0x02;
printf("%d",flag);
return 0;
}
```
## qu7
``` c
#include<stdio.h>
int main()
{
int x=10;
x&=~2; 
printf("x=%d",x);
}
```
##  qu11
``` c
#include<stdio.h>
void main()
{
printf("value is =%d",(10++));
} 

```
## qu12
``` c
#include<stdio.h>
void main()
{
const char var='A';
++var;
printf("%c",var);
}
```
## qu13
``` c
#include<stdio.h>
void main()
{
int x=10;
x+=(x++)+(++x)+x;
printf("%d",x);
}
```
## qu14
``` c
#include<stdio.h>
void main()
{
int a=10,b=2,x=0;
x=a+b*a+10/2*a;
printf("value is =%d",x);
}
```
## qu15
``` c
#include<stdio.h>
void main()
{
unsigned short var='B';
var+=2;
var++;
printf("var:%c,%d",var,var);
}
```
## qu16
``` c
#include<stdio.h>
void main()
{
char var=10;
printf("var is=%d",++var++);
}
```
## qu17
``` c
#include<stdio.h>
void main()
{
int x=(20 ||40)&&(10);
printf("x=%d",x);
}
```
## qu18
``` c
 #include <stdio.h>
 void main()
                                                                                                                     
{
 int x;
 x= (printf("AA")||printf("BB"));
 printf("%d",x);
 printf("\n");
 x= (printf("AA")&& printf("BB"));
 printf("%d",x);
 }
```
## qu19
``` c
 #include <stdio.h>
 void main()
 {
 int a=3,b=2;
 a=a==b==0;
 printf("%d,%d",a,b);
 }
```
## qu20
``` c
 #include <stdio.h>
 void main(){
 int intVar=20,x;
 x= ++intVar,intVar++,++intVar;
 printf("Value of intVar=%d, x=%d",intVar,x);
 }
 ```
## qu21
``` c
 #include <stdio.h>
 int main(){
 char val=250;
 int  ans;
 ans= val+ !val + ~val + ++val;
 printf("%d",ans);
 return 0;
 }
```
## qu22
``` c
 #include<stdio.h>
  int main()
  {
  int a = 10 ;
  double b = 5.6;
  int c;
  c =a+b;
  printf(“%d” , c);
  }
```
## qu23
``` c
 #include <stdio.h>
 int main(){
 int x;
 x=100,30,50;
 printf("x=%d\n",x);
 x=(100,30,50);
 printf("x=%d\n",x);
 return 0;
 }
```





