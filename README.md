# EX-16-LEFT-SHIFT-OPERATION

## AIM
To write a C Program to perform the basic left shift operation for 44 integer number with 3 shifts.

## ALGORITHM
1.	Start the program.
2.	Assign values of a and b as 44 and 3.
3.	Use left shift operator (<<) and shift the value of a three times.
4.	Display the result.
5.	Stop the program.

## PROGRAM
#include<stdio.h>
int main()
{
    int a=44,b=3;
    int res=a<<b;
    printf("%d",res);
    return 0;
}

## OUTPUT
<img width="1814" height="514" alt="image" src="https://github.com/user-attachments/assets/7c6cb3da-be21-4092-ae00-77625d719295" />


## RESULT
Thus the program to perform the basic left shift operation for 44 integer number with 3 shifts has been executed successfully.



 
# EX-17-TWO-NUMBERS-ARE-EQUAL-OR-NOT

## AIM
Write a C Program to check whether the two numbers are equal or not using simple if statement.

## ALGORITHM
1.	Start the program.
2.	Read two numbers.
3.	If first number is equal to second number, display both are equal.
4.	Otherwise display both are not equal.
5.	Stop the program.

## PROGRAM
#include<stdio.h>
int main()
{
    int a,b;
    scanf("%d %d",&a,&b);
    if(a==b)
    printf("The numbers are equal");
    else
    printf("The numbers are NOT equal");
    return 0;
}

## OUTPUT
<img width="1813" height="575" alt="image" src="https://github.com/user-attachments/assets/67eeb720-8b6c-4aed-9dc4-acf3e5123f53" />
<img width="1815" height="548" alt="image" src="https://github.com/user-attachments/assets/bfd51836-1a7c-4fc3-955e-8d4156df18f6" />
           
## RESULT
Thus the program to check whether the two numbers are equal or not using simple if statement has been executed successfully
 
 


# EX-18-STRING-LOWERCASE-CONVERSION
## AIM
Write a C Program to convert the given string into lowercase.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using tolower( ) function convert the given string into its lowercase.
4.	Display the result.
5.	Stop the program.

## PROGRAM
#include<stdio.h>
#include<ctype.h>
#include<string.h>
int main()
{
    char str[50];
    scanf("%[^\n]s",str);
    for(int i=0;i<strlen(str);i++)
    {
        str[i]=tolower(str[i]);
    }
    printf("%s",str);
    return 0;
}

## OUTPUT
<img width="1817" height="677" alt="image" src="https://github.com/user-attachments/assets/4c0d0dfc-955d-46a4-a1c3-fb70cd679f0f" />

## RESULT
Thus the program to convert the given string into lowercase has been executed successfully
 
 


# EX-19-COUNT-OF-WORDS-IN-A-STRING
## AIM
Write a C Program to count the total number of words in a given string using do While loop.

## ALGORITHM
1.	Start the program.
2.	Read a string variable.
3.	Using for loop, inspect the string character by character.
4.	Whenever a space is encountered increment count by 1.
5.	Display the result.
6.	Stop the program.

## PROGRAM
#include<stdio.h>
#include<string.h>
int main()
{
    char str[50];
    scanf("%[^\n]s",str);
    int count=1;
    for(int i=0;i<strlen(str);i++)
    {
        if(str[i]==' ')
        count++;
    }
    printf("Total number of words = %d",count);
    return 0;
}

## OUTPUT
<img width="1817" height="696" alt="image" src="https://github.com/user-attachments/assets/1af23e42-7c81-4533-ad89-8e0dfe1bc828" />


## RESULT
Thus the program to count the total number of words in a given string using do While loop has been executed successfully
 
 


# EX  -20 -COMPARING TWO STRINGS
## AIM
write a Program to compare two strings without using strcmp().
## ALGORITHM
Step 1: Start the program.
Step 2: Declare two character arrays c1 and c2 of size 100 to store the strings. Also, declare an integer variable
             flag and initialize it to 0, and i for indexing.      
Step 3: Read the first string c1 using scanf("%[^\n]", c1); — this reads input until a newline is encountered 
            (i.e., can include spaces).
Step 4: Read the second string c2 using scanf("%s", c2); — this reads input until a space or newline (i.e., no 
            spaces in the second string).
Step 5: Start comparing characters of both strings from index i = 0.
Step 6: Repeat the following while neither c1[i] nor c2[i] is '\0' (i.e., end of string):
•	If c1[i] is not equal to c2[i], set flag = 1.
•	Increment i by 1.
Step 7: After the loop, check the value of flag:
•	If flag == 0, print "strings are same".
•	Otherwise, print "strings are not same".
Step 8: End the program.

## PROGRAM
#include<stdio.h>
int main()
{
    char str1[50];
    scanf("%[^\n]\n",str1);
    char str2[50];
    scanf("%[^\n]",str2);
    int i=0,flag=0;
    while(str1[i]!='\0'&&str2[i]!='\0')
    {
        if(str1[i]!=str2[i])
        flag=1;
        i++;
    }
    if(flag==0)
    printf("The strings are the same");
    else
    printf("The strings are not the same");
    return 0;
}

## OUTPUT
 <img width="1814" height="488" alt="image" src="https://github.com/user-attachments/assets/9384a76b-d8a7-4911-9266-060adb140559" />
<img width="1813" height="599" alt="image" src="https://github.com/user-attachments/assets/eca85ea0-cdd4-46fb-8d82-f206167eccde" />


## RESULT
Thus the C Program to compare two strings without using strcmp() has been executed successfully.

