# program-2d
### EX NO-2)d) -  Calculate the sum of digits of a number.

**Date:** 12/2/2026  
**Name:** Sivakarthikeyan. v
**Ref no:** 25017090 

---

### AIM:
To write a C program to calculate the sum of digits of a number.

---

### ALGORITHM:
1.Get a input number from the user.
2.separate the digits using modulo operator amd add the digits using loop
---

### PROGRAM:
```
#include<stdio.h>
int main()
{
    int num,sum=0;
    scanf("%d",&num);
    do{
    sum+=num%10;
    num=num/10;}
    while(num>0);
    printf("%d",sum);
}
```
### output :
<img width="410" height="163" alt="image" src="https://github.com/user-attachments/assets/170159f0-6146-4c45-9d6e-1209c297dc7e" />
### result
Thus the C program to find the sum of digits of a number is executed successfully.
