#include<stdio.h>
void main()
{
    int y;
    printf("Enter the year:\t");
    scanf("%d", &y);
    if(y%400==0)
        printf("\n%d is Leap year",y);
    else if(y%100==0)
        printf("\n%d is not leap year",y);
    else if(y%4==0)
        printf("\n%d is a leap year",y);
    else
    printf("%d is not a leap year",y);
    
}
