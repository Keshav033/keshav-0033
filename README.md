
// Cprogram to find the man's rate in still water and the rate of current
#include <stdio.h>
void rate1(float,float);
void rate2(float,float);
void main()
{
    float a,b;
    printf("Enter the Downstream speed in m/s\n");
    scanf("%f",&a);
    printf("Enter the Upstream speed in m/s\n");
    scanf("%f",&b);
    rate1(a,b);
    rate2(a,b);
}
void rate1(float a,float b)
{
    float x;
    x=(a+b)/2;
    printf("The man's rate in still water is:%fm/s\n",x);
}
void rate2(float a,float b)
{
    float y;
    y=(a-b)/2;
    printf("The rate of current is:%fm/s\n",y);
}
