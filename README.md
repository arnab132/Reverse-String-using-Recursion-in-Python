# Reverse-String-using-Recursion-in-Python

This is a Python Program to reverse a string using Recursion.

Problem Description:

The program takes a string and reverses the string using recursion.

Problem Solution:

1. Take a string from the user.
2. Pass the string as an argument to a recursive function to reverse the string.
3. In the function, put the base condition that if the length of the string is equal to 0, the string is returned.
4. Otherwise recursively call the reverse function to slice the part of the string except the first character and concatenate the first character to the end of the sliced string.
5. Print the reversed string.
6. Exit.

Program Explanation:

1. User must enter a String.
2. The string is passed as an argument to a recursive function to reverse the string.
3. In the function, the base condition is that if the length of the string is equal to 0, the string is returned.
4. If not equal to 0, the reverse function is recursively called to slice the part of the string except the first character and concatenate the first character to the end of the sliced string.
5. The reversed string is printed.

Runtime Test Cases:
 
Case 1:
Enter the string to be reversed: hello world
dlrow olleh
 
Case 2:
Enter the string to be reversed: first
tsrif

