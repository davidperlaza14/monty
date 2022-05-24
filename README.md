0x18. C - Stacks, Queues - LIFO, FIFO
Description
This Holberton School project is a custom ByteCode interpreter, coded in C. Compilation: gcc -Wall -Werror -Wextra -pedantic *.c -o monty Usage: ./monty byte_file.m

The program reads from the file byte_file.m that contains one instruction per line. It then calls the right function to modify a stack according to the instruction. It prints custom error messages if the instruction is wrong.

Table of contents
FileDescription
main.centry point of the program
monty.h main header file
lists.h header file for the lists functions
get_func.cfunction that picks the right function for the instruction
handler_funcs1.chandler functions for the instructions
handler_funcs2.chandler functions for the instructions
handler_funcs3.chandler functions for the instructions
list_funcs1.cdoubly linked list functions
list_funcs2.cdoubly linked list functions
strtow.cstring tokenizing functions
free.cmemory handling functions
char.chandler functions for ascii instructions
bfAdvanced tasks: Brainf*ck programs
