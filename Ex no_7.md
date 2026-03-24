# EX 7 C Program to Print a right triangle star Pattern
## DATE:
## AIM:
To write a C Program to Print a right triangle star Pattern

## Algorithm
1. Start

2. Declare integer variables n, i, and j

3. Read the value of n (number of rows) from the user

4. Set i = 1

5. Repeat the following steps while i <= n:

Set j = 1

Repeat while j <= i:

Print "*" (without newline)

Increment j by 1

Print a newline character to move to the next row

Increment i by 1

6. Stop


## Program:
```
#include <stdio.h>

int main()

{

int n, i, j;

printf("Enter the number of rows: ");
  
scanf("%d", &n);

for(i = 1; i <= n; i++) {
 
for(j = 1; j <= i; j++) {
          
printf("*");

}
  
printf("\n");

}

    return 0;

}

```
## Output:
<img width="392" height="181" alt="image" src="https://github.com/user-attachments/assets/5ac87374-c1c3-46c4-91d5-1cf93cba3d44" />



## Result:
Thus the program was executed and the output was verified successfully.
