## Program 6 : Write a program to demonstrate for loop statement .
```
#include<stdio.h>
int main()
{
int n;
printf("Enter number to count to:  ");
scanf("%d",&n);
for(int i=10; i<n; i++){
printf("%d\t",i+1);
}
printf("\n");
return 0;
}
```
**Output: Enter number to count to:  33,
11	12	13	14	15	16	17	18	19	20	21	22	23	24	25	26	27	28	29	30	31	32	33**
