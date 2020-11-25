#Assignment-2 programs

#1. C program to print all natural numbers from 1 to n
 

#include <stdio.h>

int main()

{
    int i, n;

    printf("Natural numbers from 1 to %d : \n", n);

   
    for(i=1; i<=n; i++)
    {
        printf("%d\n", i);
    }

    return 0;
}l



#2.C program to all natural numbers in reverse in given range

#include <stdio.h>

int main()

{
    int i, start, end;

    printf("Enter starting value: ");
    scanf("%d", &start);
    printf("Enter end value: ");
    scanf("%d", &end);

    for(i=start; i>=end; i--)
    {
        printf("%d\n", i);
    }

    return 0;
}
