# simple_shell
A joint Alx software engineering project between Emmanuel Amarteifio and Hibah Ahmed, where are tasked to create our own shell and writes codes that can be used to perform some simple functions. 


Description This repo has our custom shell project, which attempts to replicate some of the processes of the 'sh' shell or 'bash' shell. C language standard functions and system calls utilized

access

chdir

close

closedir

execve

exit

fork

free

fstat

getcwd

getline

kill

lstat

malloc

open

opendir

perror

read

readdir

signal

stat

strtok

wait

waitpid

wait3

wait4

write

_exit

Brief Synopsis All files in this repository are designed to compile with GNU compiler collection 'gcc' in the linux environment from 'Ubuntu 20.04 LTS'. When compiled, the executable file replicates a 'shell' or command line interpreter, which is a user interface used for access to an operating system's services. This shell has a set of custom built-in commands, and also integrates with other commands located in the system's PATH. Output and functionality from commands is designed to replicate output from the shell sh (dash) and some bash commands.

Usage compile $ gcc -Wall -Werror -Wextra -pedantic *.c -o hsh

Compile with Make: make all

executing the program interactive mode: $ ./hsh

non-interactive mode: $ echo "ls -la" | ./hsh

Display a prompt and wait for the user to type a command. A command line always ends with a new line.
The prompt is displayed again each time a command has been executed.
The command lines are simple, no semicolons, no pipes, no redirections or any other advanced features.
The command lines are made only of one word. No arguments will be passed to programs.
If an executable cannot be found, print an error message and display the prompt again.
Handle errors.
You have to handle the “end of file” condition (Ctrl+D)


WHAT WE LEARNT 


How a shell works and finds commands


Creating, forking and working with processes


Executing a program from another program


Handling dynamic memory allocation in a large program


Pair programming and team work


Building a test suite to check our own code
