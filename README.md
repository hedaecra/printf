# Printf :floppy_disk: 

## Flowchart

![This is a alt text.](https://app.code2flow.com/0FVgTQYGFEqX.png "This is a sample image.")

### Objective: :clipboard:

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

## Description :page_with_curl:

`_printf` is our custom implementation of the C `printf` program function . It produces an output according to format described.

## Prototype

```
int _printf(const char *format, ...);
```

## Usage :computer:

|Specifiers   |  Printed As  |
| :------------: | :------------: |
| c  |  characters |
|s   | string of characters  |
| %  | no conversion, writes '%'  |
|  d or i  | int to signed decimal  |

**String**
* Specifier: `%s`
* Input:  `len = _printf("I am a string. \n");`
* Output: `I am a string`

**Character**
* Specifier: `%c`
* Input:  `_printf("char: %c\n", 'A');`
* Output: `char: A`

**Integer**
* Specifier: `%i`
* Input:  `_printf("Length: %i\n", len);
* Output: `Length: 16`

**Decimal:**
* Specifier: `%d`
* Input:  `_printf("%d\n", 1000);`
* Output: `1000`

**Percent:**
* Specifier: `%%` 
* Input:  `_printf("%%\n", %);`
* Output: `%`

## Examples

* _printf("Hello, World\n") prints "Hello, world", followed by a new line
* _printf("%s", "Hello") prints "Hello"
* _printf("This is a number: %d", 98) prints "This is a number: 98"

## Files
File Name | Description
--- | ---
`_printf.c` | Produces an output according to specifiers 
`_putchar.c` | Function to write a char to standard output
`main.h` | Header file with function prototypes and struct
`print_chars.c` | Containing functions to print char, string and % symbols
`print_numbers.c` | Containing functions to print decimal and integer numbers

### Main Functionality :rocket:

- [X] Produces output with (printf) conversion specifiers c, s, and %.
- [X] Handles conversion specifiers d, i.
- [X] man page added.


## Madatory Task

* Write function that produces output with conversion specifiers c, s, and %.
* Handle conversion specifiers d, i.
* Create a man page for your function.

## man_3_printf

* Custom man page made for the _printf function, it´s include in the `_printf` repository [printf](https://github.com/hedaecra/printf).

## Build with :wrench:

* Made in C Language and compiled in Ubuntu 20.04 LTS

## Authors :black_nib:

* **Hernan Echeverri** - *Holberton Student* - [Hedaecra](https://github.com/hedaecra)
* **César Calero** - *Holberton Student* - [Cecales](https://github.com/Cecales)
