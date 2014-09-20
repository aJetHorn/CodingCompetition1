Detecting unreachable instructions | 1 point(s)
Untouched instructions in code can cause some serious problems. You may have heard about a recent security hole related to this topic.
Your task is to write a small program that catches the “untouched” lines of code written in our simplified programming language.
The program starts at line 1. You may assume the program will be terminated if it infinitely loops or continues past its last instruction.
Input description/format
Each line of input contains an instruction (NEXT or GOTO).
1.	NEXT: the program will move to the next line.
2.	GOTO X: the program will go to line number X.
Output description/format
Please print out the line number of instructions that the program doesn't touch (one line number per line in the output file).
Example input
NEXT NEXT GOTO 5 NEXT GOTO 1 NEXT 
Example output
4 6

