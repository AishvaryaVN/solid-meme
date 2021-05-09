#include<stdio.h>
int main()
{
    int a=6,b=3;
    printf("\n before swap \n a=%d\n b=%d",a,b);
    a=a+b;
    b=a-b;
    a=a-b;
    printf("\n after swap \n a=%d\n b=%d",a,b);
    getch();
    return 0;
}
