
#include <stdio.h>

int main()
{
    int marks[4];
    for(int i=0; i<4; i++)
    {
        printf("enter the number",i);
        scanf("%d",&marks[i]);
    }
    for(int i=0; i<4; i++)
    {
        printf("the number of %d is %d\n",i+1, marks[i]);
    }
    return 0;
}
