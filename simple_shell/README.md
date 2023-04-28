# Simple Shell

A simple UNIX command interpreter shell program that reads input from the user or from a script file and executes the requested command(s). This program was written in C and runs on the UNIX command line interface.

## Getting Started

This shell can be installed and run on a UNIX-based operating system such as Linux or macOS. Follow the instructions below to set up and run the shell:

### Prerequisites

- GCC compiler

### Installing

1. Clone the repository:

```bash
git clone https://github.com/oforigyimah/simple_shell.git
```

2. Navigate to the project directory:

```bash
cd simple_shell/
```

3. Compile the program:

```bash
gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
```

### Running

To run the shell, enter the following command in the terminal:

```bash
./hsh
```

## Usage

This shell can be used to execute any UNIX command. Enter the command at the prompt and press Enter. The shell will execute the command and display the output on the screen.

The shell also supports the following built-in commands:

- `exit`: Exit the shell
- `cd`: Change the current working directory
- `help`: Display information about the shell and its built-in commands

To run a built-in command, enter the command at the prompt and press Enter.

## Examples

```bash
$ ./hsh
$ ls -l
total 88
-rw-rw-r-- 1 vagrant vagrant  2889 Sep  2 23:57 AUTHORS
-rw-rw-r-- 1 vagrant vagrant  4102 Sep  2 23:57 builtins.c
-rw-rw-r-- 1 vagrant vagrant  3784 Sep  2 23:57 error_handler.c
-rw-rw-r-- 1 vagrant vagrant  2872 Sep  2 23:57 execute_command.c
-rw-rw-r-- 1 vagrant vagrant  1968 Sep  2 23:57 free_mem.c
-rw-rw-r-- 1 vagrant vagrant  1083 Sep  2 23:57 get_path.c
-rw-rw-r-- 1 vagrant vagrant   543 Sep  2 23:57 header.h
-rw-rw-r-- 1 vagrant vagrant  4116 Sep  2 23:57 main.c
-rw-rw-r-- 1 vagrant vagrant 11576 Sep  2 23:57 README.md
-rw-rw-r-- 1 vagrant vagrant  4058 Sep  2 23:57 string_handler.c
-rw-rw-r-- 1 vagrant vagrant  1719 Sep  2 23:57 tokenize.c
$
$ cd ..
$
$ pwd
/home/vagrant/simple_shell
$
$ help
Simple Shell - A UNIX command interpreter
Usage: simple_shell
Built-in commands:
cd [directory]        Change the current working directory
help                  Display information about the shell and its built-in commands
exit                  Exit the shell
$
$ exit
$
```


