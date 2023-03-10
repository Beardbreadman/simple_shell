# simple_shell
A simple UNIX command interpreter that replicates functionalities of the simple shell (sh). Additional functions are also included. This program was written entirely in C as a milestone project for ALX Africa Software Engineering.

**A simple Unix command line interpreter**
![shell](/)

****
## Table of contents
 - **What is the shell?**
 - **About this project**
 - **Essential Functionalities of the Simple Shell**
 - **File description**
 - **List of allowed functions and system calls for this project**
 - **USAGE**
 - **Example of Usage**
 - **Bugs**
 ****

## What is the shell?
The shell is a program that takes commands from the keyboard via the terminal, and gives them to the operating system to perform.\

## About this project
This project is a simple version of the linux shell  replica made by team sponge under the system [Alxse/Holberton School] taking part of the "Low-level programming & Algorithm - Linux and Unix system programming" projects.\

It is created using the **C programming Language** and it can do many functionalities that a real shell does.

## Essential Functionalities of the Simple Shell:
> Displays a prompt "#cisfun$ " and waits for user input.\
> Runs all commands of type "executable program" (ls and /bin/ls).\
> Runs the following build_in commands: **exit**, **env**, **setenv** and **unsetenv**.\
> Handles commands with arguments.\
> Handles the PATH global variable.\
> Handles The EOF (End Of File) condition.\
> Handles the Ctrl + C signal -> It doesn't exit the shell

## Files description
 - **AUTHORS** -> List of contributors to this repository
 - **man_1_simple_shell** -> Manual page for the simple_shell
 - **main.h** -> Header file
 - **main.c** -> main function
 - **aux_error1**
 - **aux_error2**
 - **aux_help**
 - **aux_help2**
 - **aux_lists**
 - **aux_lists2**
 - **aux_mem**
 - **aux_stdlib**
 - **aux_str**
 - **aux_str2**
 - **aux_str3**
 - **cd_shell**
 - **cd**
 - **check_syntax_error**
 - **cmd_exec**
 - **env**
 - **exec_line**
 - **exit_shell**
 - **get_builtin**
 - **get_error**
 - **get_help**
 - **get_line**
 - **get_sight**
 - **read_line**
 - **rep_var**
 - **shell_loop**
 - **split**

****
## List of allowed functions and system calls for this project
 - access (man 2 access)
 - chdir (man 2 chdir)
 - close (man 2 close)
 - closedir (man 3 closedir)
 - execve (man 2 execve)
 - exit (man 3 exit)
 - _exit (man 2 _exit)
 - fflush (man 3 fflush)
 - fork (man 2 fork)
 - free (man 3 free)
 - getcwd (man 3 getcwd)
 - getline (man 3 getline)
 - isatty (man 3 isatty)
 - kill (man 2 kill)
 - malloc (man 3 malloc)
 - open (man 2 open)
 - opendir (man 3 opendir)
 - perror (man 3 perror)
 - read (man 2 read)
 - readdir (man 3 readdir)
 - signal (man 2 signal)
 - stat (__xstat) (man 2 stat)
 - lstat (__lxstat) (man 2 lstat)
 - fstat (__fxstat) (man 2 fstat)
 - strtok (man 3 strtok)
 - wait (man 2 wait)
 - waitpid (man 2 waitpid)
 - wait3 (man 2 wait3)
 - wait4 (man 2 wait4)
 - write (man 2 write)
****

## USAGE
You can try our shell by following these steps:
> **Step 1:** Clone our repository using this command, (you need to have git installed on your machine first)
````
git clone https://github.com/Beardbreadman/simple_shell
````
> **Step 2:** Change directory to simple_shell:
````
cd simple_shell
````
> **Step 3:** Compile the C files in this way:
````
gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
````
> **Step 4:** Run the shell
````
./hsh
````
**Exiting the shell**
When you want to exit the shell, you can use one of the following methods:
> **1: Type the command "exit"**
````
exit
````
> **2: Press on Ctrl + D**

## TEAM
Wonderful Adebayo  : [LinkedIn/wonderful] | [GitHub/beardbreadman]\
Fira Gemeda 

[LinkedIn/Wonderful]: <https://www.linkedin.com>

[GitHub/Beardbreadman]: <https://github.com/Beardbreadman>


