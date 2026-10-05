//even-or-odd.c
//code to find weather a number is even or odd
#include<stdio.h>
int main()
{
    int a;
    printf("enter the value of a: ");
    scanf("%d",&a);
    if(a%2!=0)
    {
        printf("a is odd number");
    }
    else
    {
        printf("a is even number");
    }
    return 0;

}
