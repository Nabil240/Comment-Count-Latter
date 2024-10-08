Description:
This C program is designed to check whether a given input string represents a comment, specifically in C or C++ style, and to output the total number of characters in the string.

Key Features:
Input Handling: The program prompts the user to input a comment string using gets() (which is unsafe and can lead to buffer overflows, so replacing it with fgets() is recommended).

Comment Detection:

Single-line comments: Recognized if the string starts with //.
Multi-line comments: Identified if the string starts with /* and ends with */. However, the current logic may incorrectly identify comments if only part of the multi-line comment syntax is present.
String Length Calculation: The length of the entered string is calculated using strlen().

