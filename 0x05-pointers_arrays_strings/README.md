

General

Why C programming is awesome (don’t forget to tweet today, with the hashtag #cisfun :))

Who invented C

Who are Dennis Ritchie, Brian Kernighan and Linus Torvalds

What happens when you type gcc main.c

What is an entry point

What is main

How to print text using printf, puts and putchar

How to get the size of a specific type using the unary operator sizeof

How to compile using gcc

What is the default program name when compiling with gcc

What is the official Holberton C coding style and how to check your code with betty-style

How to find the right header to include in your source code when using a standard library function

How does the main function influence the return value of the program

Requirements C

Allowed editors: vi, vim, emacs

All your files will be compiled on Ubuntu 14.04 LTS using gcc 4.8.4

All your files should end with a new line

A README.md file at the root of the holbertonschool-low_level_programming repo, containing a description of the repository

A README.md file, at the root of the folder of this project, containing a description of the project

There should be no errors and no warnings during compilation

You are not allowed to use system

Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl

0-preprocessor: Preprocessor

A script that runs a C file through the preprocessor and save the result into another file. The C file name will be saved in the variable $CFILE; The output should be saved in the file c using gcc $CFILE -E -o c.



1-compiler: Compiler

A script that compiles a C file but does not link. The C file name will be saved in the variable $CFILE; The output file should be named the same as the C file, but with the extension .o instead of .c;



Example: if the C file is main.c, the output file should be main.o using gcc -c $CFILE.



2-assembler: Assembler

A script that generates the assembly code of a C code and save it in an output file. The C file name will be saved in the variable $CFILE; The output file should be named the same as the C file, but with the extension .s instead of .c.



Example: if the C file is main.c, the output file should be main.s using gcc -S $CFILE.



3-name: Name

A script that compiles a C file and creates an executable named cisfun. The C file name will be saved in the variable $CFILE using gcc $CFILE -o cisfun.





