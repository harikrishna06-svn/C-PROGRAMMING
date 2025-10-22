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



