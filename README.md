# identifiers
A program to identify valid identifiers

Description
This Lex program identifies identifiers from the input.
An identifier is defined as a string that:

Starts with a letter (a-z or A-Z)

May contain letters or digits after the first character.

The program reads input, matches identifiers using the pattern:

{letter}({letter}|{digit})*

and prints:
<word> is an identifier
Spaces, tabs, and newlines are ignored. The scanning continues until the end of input.

Example:
Input:
abc 123 x1 test

Output:

abc is an identifier
x1 is an identifier
test is an identifier
