# 19AI304-Fundamentals-of-C-Programming-2025-Odd-M1
# IAPR-1- Module 1 - FoC
## 1. Implementation of basic C programs using Literals,Consonants, Variables, Data types.
## 2. Implementation of different categories of operators.
# Ex.No:1
  Build a C program to demonstrate the usage of different types of literals: integer, float, character, and string.  
# Date : 
# Aim:
To build a C program that prints integer, float,character, and string literals on the console using the printf() function.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside the main() function, use printf() to display each literal along with its size in bytes using sizeof() :
  
   3.1 Integer literal (e.g., 10) using `%d`
   
   3.2 Float literal (e.g., 3.14) using `%f`
   
   3.3 Character literal (e.g., 'A') using `%c`
   
   3.4 String literal (e.g., "Hello C") using `%s`
   
### Step 4: 
   Stop
# Program:
```
#include <stdio.h>
int main(){
    int intLiteral=25;
    float floatLiteral=25.5;
    char charLiteral='c';
    char stringLiteral[]="Twenty Five";
    printf("Integer Literal = %d\n",intLiteral);
    printf("Float Literal = %f\n",floatLiteral);
    printf("Char Literal = %c\n",charLiteral);
    printf("String Literal = %s",stringLiteral);
}
```
# Output:
<img width="320" height="103" alt="image" src="https://github.com/user-attachments/assets/c4a1ad48-c40e-4e5e-9319-eadcc25daf34" />


# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:2
  Build a C program to display the value of a macro constant and a constant variable.
# Date : 
# Aim:
  To build a C program that demonstrates the use of macro constants and constant variables.
# Algorithm:
### Step 1:
  Start  
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Define a macro constant `PI` with value `3.14159` using `#define`.
### Step 4: 
   Inside `main()`:
   
   4.1 Declare a constant integer variable `DAYS`
   
   4.2 Initialize it with the value `7`
   
### Step 5:  
  Use `printf()` to display the values of `PI` and `DAYS`.     
### Step 6:  
  Stop
# Program:
```
#include <stdio.h>
#define pi 3.14159
int main(){
    const int max=100;
    printf("Macro constant (pi) = %f\n",pi);
    printf("Constant Variable (max) = %d",max);
}
```
# Output:
<img width="307" height="60" alt="image" src="https://github.com/user-attachments/assets/2999a581-fbcf-4a4c-8ec2-927142397a80" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:3
  Build a C program to demonstrate the use of different data types such as int, float, double, and char, and display their values using printf().
# Date : 
# Aim:
  To build a C program that declares variables of various data types—integer, float, double, and character—initializes them, and prints their values on the screen.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside main(), declare and initialize variables of types int, float, double, and char.
### Step 4: 
   Display their values using printf().
### Step 5:    
   Stop
# Program:
```
#include <stdio.h>
int main(){
    int a=45;
    float b=45.5;
    double c=123.456;
    char d='A';
    printf("Integer = %d\n",a);
    printf("Float = %.2f\n",b);
    printf("Double = %.2f\n",c);
    printf("Character = %c\n",d);
    return 0;
}
```
# Output:
<img width="175" height="108" alt="image" src="https://github.com/user-attachments/assets/4d5af94c-e790-4db9-99a5-5a2e71f78f45" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.

# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:4
  Build a C program to perform arithmetic and bitwise operations on two integers entered by the user. The program should display: Arithmetic operations: addition, subtraction, multiplication, division, and remainder. Bitwise operations: AND, OR, XOR, left shift, right shift, and NOT.
# Date : 
# Aim:
  To build a C program that takes two integers as input and demonstrates the arithmetic and bitwise operations, displaying the results of each operation.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Declare two integer variables a and b.
### Step 4: 
   Prompt the user to enter two integers and read the input using scanf().
### Step 5:    
   Perform arithmetic operations on a and b:
   #### Sum (a + b)
   #### Difference (a - b)
   #### Product (a * b)
   #### Quotient (a / b)
   #### Remainder (a % b)
### Step 6: 
  Perform bitwise operations on a and b:
  #### AND (a &amp; b)
  #### OR (a | b)
  #### XOR (a ^ b)
  #### Left shift (a << b)
  #### Right shift (a >> b)
  #### Bitwise NOT of a (~a) and b (~b)
### Step 7:   
  Display the results of all operations using printf().
### Step 8:   
  Stop
# Program:
```
#include <stdio.h>
int main(){
    int a,b;
    printf("Enter Integer 1 : \n");
    scanf("%d",&a);
    printf("Enter Integer 2 : \n");
    scanf("%d",&b);
    printf("Arithmetic Operations on a and b are:\n");
    printf("Sum (a+b) = %d\n",a+b);
    printf("Difference (a-b) = %d\n",a-b);
    printf("Product (a*b) = %d\n",a*b);
    printf("Quotient (a/b) = %d\n",a/b);
    printf("Remainder (a%b) = %d\n",a%b);
    printf("\n");
    printf("Bitwise Operations on a and b are:\n");
    printf("AND (a&b) = %d\n",a&b);
    printf("OR (a|b) = %d\n",a|b);
    printf("XOR (a^b) = %d\n",a^b);
    printf("Left Shift (a<<1) = %d\n",a<<1);
    printf("Right Shift (a>>1) = %d\n",a>>1);
    printf("Bitwise NOT of a = %d\n",~a);
    printf("Bitwise NOT of b = %d\n",~b);
}
```
# Output:
<img width="421" height="524" alt="image" src="https://github.com/user-attachments/assets/b9f9321d-5dcd-48a7-b24a-cf426200ee5b" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:5
  Develop a C program to check whether a given character is a vowel, consonant, digit, or special symbol using the ternary operator.
# Date : 
# Aim:
  To develop and implement a C program that classifies a character as a vowel, consonant, digit, or special symbol using the ternary operator.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Input a character ch from the user.
### Step 4: 
   Check if ch is a digit ('0' to '9').
   
   If true → Print "Digit" → Go to Step 8.
   
   If false → Go to Step 5.
   
### Step 5:    
   Check if ch is an alphabet letter ('A' - 'Z' or 'a' – 'z').
   
   If true → Go to Step 6.
   
   If false → Go to Step 7.
   
### Step 6: 
   Check if ch is a vowel (a, e, i, o, u or A, E, I, O, U).
   
   If true → Print "Vowel" → Go to Step 8.
   
   If false → Print "Consonant" → Go to Step 8.
   
### Step 7:   
   Print "Special Symbol".
### Step 8:   
  Stop
# Program:
```
#include <stdio.h>
int main(){
    char a;
    printf("Enter a character of your choice:\n");
    scanf("%c",&a);
    if ((a>='a')&&(a<='z')||(a>='A')&&(a<='Z')){
        if ((a=='A')||(a=='E')||(a=='I')||(a=='O')||(a=='U')||(a=='a')||(a=='e')||(a=='i')||(a=='o')||(a=='u')){
            printf("Vowel.");
        }
        else{
            printf("Consonant");
        }
    }
    else if ((a>='0')&&(a<='9')){
        printf("Digit.");
    }
    else{
        printf("Special Symbol.");
    }
}
```
# Output:
<img width="370" height="72" alt="image" src="https://github.com/user-attachments/assets/ee972d26-78bc-4b89-919d-4cb978fc1a66" />
<img width="374" height="70" alt="image" src="https://github.com/user-attachments/assets/6a22e603-efca-44ef-933c-beff50eab23e" />
<img width="356" height="85" alt="image" src="https://github.com/user-attachments/assets/4060ed82-9721-48fd-bba5-1043c29afe9b" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


