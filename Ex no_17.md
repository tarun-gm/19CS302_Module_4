# EX 17 C Program to compare two strings without using strcmp().

## DATE:
08.06.2026

## AIM:
To write a C Program to compare two strings without using strcmp().

## Algorithm

1. Start the program.
2. Declare two character arrays.
3. Get two strings from the user.
4. Compare the strings character by character using loop.
5. If all characters are equal, display Strings are Equal.
6. Otherwise, display Strings are Not Equal.
7. Stop the program.

## Program:

```c
#include <stdio.h>

int main()
{
    char s1[50], s2[50];
    int i = 0, flag = 0;

    scanf("%s", s1);
    scanf("%s", s2);

    while(s1[i] != '\0' || s2[i] != '\0')
    {
        if(s1[i] != s2[i])
        {
            flag = 1;
            break;
        }

        i++;
    }

    if(flag == 0)
    {
        printf("Strings are Equal");
    }
    else
    {
        printf("Strings are Not Equal");
    }

    return 0;
}
```

## Output:

```text
hello
hello

Strings are Equal
```

## Result:
Thus the program was executed and the output was verified successfully.
