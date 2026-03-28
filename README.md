# c-module-4

# EXP NO: 4a) C PROGRAM TO PERFORM THE BASIC RIGHT SHIFT OPERATION FOR 60 INTEGER NUMBER WITH 3 SHIFT.

# AIM:
To write a C program to perform the basic right shift operation for 60 integer number with 3 shift.

# ALGORITHM:
1. Inside main() function, declare the integer a value as 60.
2. Perform the right shift operation with 3 shift.
3. Print the value using printf function.

# PROGRAM:
```
#include<stdio.h>
int main()
{
  int a=60;
  a=a>>3;
  printf("After Right Shift Operation value of a is:%d\n",a);
  return 0;
}
```

# OUTPUT:
<img width="1136" height="259" alt="image" src="https://github.com/user-attachments/assets/187caef3-0b9a-4384-a09c-2aa5cb25dad5" />

# RESULT:
Thus, the program is verified successfully.

# EXP NO: 4b) C PROGRAM TO CHECK WHETHER THE GIVEN CHARACTER IS VOWEL OR NOT USING NESTED IF.

# AIM:
To write a C program to check whether the given character is vowel or not using nested if.

# ALGORITHM:
1. Take the character from the input from the user using scanf function.
2. Using nested if function, check whether the character is a vowel or not.
3. If both the if and else if conditions are not true, then the else block will be executed.

# PROGRAM:
```
#include<stdio.h>
int main()
{
    char ch;
    scanf("%c",&ch);
    if(ch=='a' || ch=='e' || ch=='i' || ch=='o' || ch=='u') printf("It is an vowel.\n");
    else if(ch>='a' && ch<='z')printf("It is a consonant.\n");
    else printf("It is not an vowel nor consonant.\n");
    return 0;
}
```

# OUTPUT:
<img width="1100" height="345" alt="image" src="https://github.com/user-attachments/assets/d3c163e6-c89a-4ce4-be14-0f3931fb56ab" />

# RESULT:
Thus, the program is verified successfully.

# EXP NO: 4c) C PROGRAM TO COMPARE TWO STRINGS USING STRCMP().

# AIM:
To write a Program to compare two strings using strcmp().

# ALGORITHM:
1. Use the header files #include<string.h> and #include<ctype.h>.
2. In main() function, take the two strings from the user as inputs using scanf function.
3. Use strcmp() function to compare both the strings.
4. If the value is equal to 0, then the strings are same.
5. Otherwise, the strings are not same.

# PROGRAM:
```
#include<stdio.h>
#include<string.h>
#include<ctype.h>
int main()
{
    char str1[100],str2[100];
    scanf("%s",str1);scanf("%s",str2);
    int value=strcmp(str1,str2);
    if(value==0) printf("strings are same");
    else printf("strings are not same");
    return 0;
}
```

# OUTPUT:
<img width="1118" height="332" alt="image" src="https://github.com/user-attachments/assets/d81c00a5-06e1-4d1f-8258-4d2c2e2ba829" />

# RESULT:
Thus, the program is verified successfully.

# EXP NO: 4d) C PROGRAM TO IMPUT CHARACTER FROM USER AND CHECK WHETHER CHARACTER IS UPPERCASE OR LOWERCASE ALPHABET USING SIMPLE IF.

# AIM:
To write a C program to input character from user and check whether character is uppercase or lowercase alphabet using simple if.

# ALGORITHM:
1. In main() function, take the character from the user as input using scanf function.
2. Using if condition, check whether the character is in uppercase or in lowercase.
3. If the conditions are not satisfied, then the else block will be executed.
   
# PROGRAM:
```
#include<stdio.h>
int main()
{
    char ch;
    scanf("%c",&ch);
    if((ch>='a' && ch<='z') || (ch>='A' && ch<='Z'))
    {
        if(ch>='A' && ch<='Z')
        {
            printf("It is uppercase character\n");
        }
        else printf("It is in lowercase character\n");
    }
    else printf("It is not an alphabet\n");
    return 0;
}
```

# OUTPUT:
<img width="1092" height="307" alt="image" src="https://github.com/user-attachments/assets/1f62fa9b-e733-43ee-9f5e-256b07550b2b" />

# RESULT:
Thus, the program is verified successfully.

# EXP NO: 4e) C PROGRAM TO FIND THE THE LENGTH OF THE STRING 'TIGER'.

# AIM:
To write a C program to find the length of the string 'TIGER'

# ALGORITHM:
1. Use the header file #include<string.h>.
2. In main() function, take the string from the user as input using scanf function.
3. Using strlen() function, find the length of the string.
4. Print the length of the string using printf function.
   
# PROGRAM:
```
#include<stdio.h>
#include<string.h>
int main()
{
  char str[100]="TIGER";
  scanf("%s",str);
  int length=strlen(str);
  printf("Length of Str is %d",length);
  return 0;
}
```

# OUTPUT:
<img width="1127" height="307" alt="image" src="https://github.com/user-attachments/assets/9920348f-0fdb-49df-9230-404d70294dd3" />

# RESULT:
Thus, the program is verified successfully.
