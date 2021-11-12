# Printf

## Flowchart

https://app.code2flow.com/0FVgTQYGFEqX

### Objective:

* The main objetive is recreate the C library printf

### Requirements:

* Allowed editors: vi, vim, emacs
* All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89
* All your files should end with a new line
* A README.md file, at the root of the folder of the project is mandatory
* Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
* You are not allowed to use global variables
* No more than 5 functions per file
* In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples
* The prototypes of all your functions should be included in your header file called main.h
* Don’t forget to push your header file
* All your header files should be include guarded
* Note that we will not provide the _putchar function for this project

## Prototype

```
int _printf(const char *format, ...);
```

## Usage

* Prints a string to the standard output, according to a given format
* All files were created and compiled on Ubuntu 14.04.4 LTS using GCC 4.8.4 with the command gcc -Wall -Werror -Wextra -pedantic *.c
* Returns the number of characters in the output string on success, -1 otherwise
* Call it this way: _printf("format string", arguments...) where format string can contain conversion specifiers and flags, along with regular characters

## Examples

* _printf("Hello, World\n") prints "Hello, world", followed by a new line
* _printf("%s", "Hello") prints "Hello"
* _printf("This is a number: %d", 98) prints "This is a number: 98"

## _putchar

* this function prints an individual character (similar to standard library putchar)

## printf

* The core function where the buffer is defined and freed. All other functions are called from here

## main.h

* Header file that contains prototypes for all the functions and a struct holding a function and a character

## Madatory Task

* Write function that produces output with conversion specifiers c, s, and %.
* Handle conversion specifiers d, i.
* Create a man page for your function.

## man_printf_(3)

* Custom man page Create a man page for your function._

## Build with

* Made in C Language and compiled in Ubuntu 20.04 LTS

## Authors ✒️

* **Hernan Echeverri** - *Holberton Student* - [Hedaecra](https://github.com/hedaecra)
* **César Calero** - *Holberton Student* - [Cecales](https://github.com/Cecales)
