# Module-2

---

# 2a : C Program to print the string "KEYBOARD" n number of times.

## AIM:
To write a C Program to print the string "KEYBOARD" n number of times.

## ALGORITHM:
1. Start
2. Input: Read an integer N from the user.
3. Repeat the following steps N times:
- Print "KEYBOARD"
4. End


## PROGRAM:
```
#include <stdio.h>
int main()
{
    int num1;
    scanf("%d", &num1);
    for (int i = 1; i <= num1; i++)
    {
        printf("KEYBOARD \n");
    }
    return 0;
}
```

## OUTPUT:
<img width="801" height="165" alt="Image" src="https://github.com/user-attachments/assets/fddb29e0-92cd-4a9d-9ea7-7baab0dc0eb8" />

## RESULT:
Thus,the program has been executed successfully.

---

# 2b : C program to print rhombus  pattern

## AIM:
To write a C program to print rhombus  pattern

## ALGORITHM:
1. Start
2. Input: Read an integer N from the user.
3. Repeat the following steps for i = 1 to N:
- Print (N - i) spaces.
- Print N hash (#) symbols.
- Move to the next line.
4. End


## PROGRAM:
```
#include <stdio.h>
int main()
{
    int num1;
    scanf("%d", &num1);
    for (int i = 1; i <= num1; i++)
    {
        for (int s = num1-i; s >= 1; s--)
        {
            printf(" ");
        }
        for (int j = 1; j <= num1; j++)
        {
            printf("#");
        }
        printf("\n");
    }
}
```

## OUTPUT:
<img width="800" height="253" alt="Image" src="https://github.com/user-attachments/assets/1bba788e-251c-4fc5-b757-778c992b14b2" />

## RESULT:
Thus,the program has been executed successfully.

---

# 2c : C program to perform addition and subtraction of two numbers using functions (with argument and without return type).

## AIM:
To write a C program to perform addition and subtraction of two numbers using functions (with argument and without return type).

## ALGORITHM:
1. Start
2. Input two numbers, say A and B
3. Compute the sum: SUM = A + B
4. Output the result SUM
5. End


## PROGRAM:
```
#include <stdio.h>
void as(int x, int y);
int main()
{
    int num1, num2;
    scanf("%d %d", &num1, &num2);
    as(num1, num2);
    return 0;
}
void as(int x, int y)
{
    printf("Addition: %d \n", x + y);
    printf("Subtraction: %d", x - y);
}
```

## OUTPUT:
<img width="803" height="181" alt="Image" src="https://github.com/user-attachments/assets/22b57ee6-e8f7-4c3b-9297-bb1895dcc7f6" />

## RESULT:
Thus,the program has been executed successfully.

---

# 2d : C program to find the sum of odd digits using for loop.

## AIM:
To write a C program to find the sum of odd digits using for loop.

## ALGORITHM:
1. Start
2. Read input n
3. Initialize i = 1 (first odd number)
4. Initialize count = 0 and sum = 0
5. Repeat while count < n:
- Print i
- Add i to sum
- Increment i by 2 (next odd number)
- Increment count by 1
6. Print sum
7. End


## PROGRAM:
```
#include <stdio.h>
int main()
{
    int num1, sum = 0;
    scanf("%d", &num1);
    for (int i = 1, j = 1; j <= num1; i += 2)
    {
        printf("%d ", i);
        sum += i;
        j++;
    }
    printf("\n%d", sum);
    return 0;
}
```

## OUTPUT:
<img width="803" height="245" alt="Image" src="https://github.com/user-attachments/assets/5119a3d9-2dc2-46b6-ab8f-a0e11da17ff4" />

## RESULT:
Thus,the program has been executed successfully.

---

# 2e : C program to print the given triangular number pattern using loop.

## AIM:
To write a C program to print the given triangular number pattern using loop.

## ALGORITHM:
1. Start
2. Read input n
3. Repeat for i = 1 to n:
- Set value = n - i + 1
- Repeat for j = 1 to i:
- Print value (without newline)
- Print newline
4. End

## PROGRAM:
```
#include <stdio.h>
int main()
{
    int num1;
    scanf("%d", &num1);
    for (int i = 1; i <= num1; i++)
    {
        for (int j = 1; j <= i; j++)
        {
            printf("%d",num1-i+1);
        }
        printf("\n");
    }
}
```

## OUTPUT:
<img width="807" height="260" alt="Image" src="https://github.com/user-attachments/assets/eb3a9941-eb9e-4ad3-bb4a-03a7719f2b71" />

## RESULT:
Thus,the program has been executed successfully.

---
