# EX 16 C program to find minimum between three fraction numbers using conditional operator.

## DATE:
08.06.2026

## AIM:
To write a C program to find minimum between three fraction numbers using conditional operator.

## Algorithm

1. Start the program.
2. Declare three float variables.
3. Get the three fraction numbers from the user.
4. Use conditional operator to find the minimum number.
5. Display the minimum value.
6. Stop the program.

## Program:

```c
#include <stdio.h>

int main()
{
    float a, b, c, min;

    scanf("%f %f %f", &a, &b, &c);

    min = (a < b) ? ((a < c) ? a : c) : ((b < c) ? b : c);

    printf("%.2f", min);

    return 0;
}
```

## Output:

```text
5.6 2.4 7.8

2.40
```

## Result:
Thus the program was executed and the output was verified successfully.
