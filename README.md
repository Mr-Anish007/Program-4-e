# Program-4-e
## C-Module 4
## EX_NO-04)e)-STRINGS
### Date: 19-10-2025
### Name: Anish D
### Register Number:25010086
## AIM:
Write a C program to find vowels in a given string using function
## ALGORITHM:
1. Start the program.
2. Declare a character array to store the input string and an integer variable vol initialized to 0.
3. Read a line of text from the user using scanf("%[^\n]", word).
4. Use a for loop to iterate through each character of the string:
    a. If the character is a vowel (a, e, i, o, u in both uppercase and lowercase), increment the vol counter.
5. After the loop, print the total number of vowels stored in vol.
6. End the program.
## PROGRAM:
```
#include<stdio.h>
#include<string.h>
#include<ctype.h>
int main()
{
    char word[100];
    scanf("%[^\n]",word);
    int vol=0;
    for(int i=0;i<strlen(word);i++)
    {
        if(word[i]=='a'||word[i]=='A'||word[i]=='e'||word[i]=='E'||word[i]=='i'||word[i]=='I'||word[i]=='o'||word[i]=='O'||word[i]=='u'||word[i]=='U')
        vol++;
        
    }
    printf("%d",vol);
}
```
## OUTPUT:
<img width="833" height="233" alt="Screenshot 2025-10-19 225404" src="https://github.com/user-attachments/assets/eed78bc8-1237-4d2e-996d-c98982106f6e" />

## RESULT:
Thus the program to find vowels in a given string using function has been executed successfully
