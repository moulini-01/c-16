//# c-16
//square pattern
#include <stdio.h>

int main()
{
    int i,j,n;
    printf("enter the size of number matrix:");
    scanf("%d",&n);
    for(int i=1;i<=n;i++)
    {
        for(int j=1;j<=n;j++)
        {
            printf("* ");
        }
        printf("\n");
    }
    return 0;
}
