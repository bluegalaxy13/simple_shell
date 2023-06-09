<h1 align ="center">simple_shell</h1><br>

------------

## Repository Description

The files needed to replicate a basic **Unix Shell** and its associated commands can be found in this repository. It is designed to carry out the **0x16. C - Simple Shell** project at and implements many of the same functionalities as the original Ken Thompson's Shell using the POSIX API.

## This shell provides the following features:

* Display a prompt and wait for the user to type a command. A command line always ends with a new line.
* The prompt is displayed again each time a command has been executed.
* The command lines are simple, no semicolons, no pipes, no redirections or any other advanced features.
* The command lines are made only of one word. No arguments will be passed to programs.
* If an executable cannot be found, print an error message and display the prompt again.
* Handle errors.
* You have to handle the “end of file” condition (**Ctrl+D**)

## Usage Examples

## Examples

Here are shown some examples of the usage of the Shell:

- ls

```shell
Hell_Shell>> ls
AUTHORS  Hell_Shell  README.md auxiliar_functions.c  create_child.c  dir  execute.c  free_mem.c  generateAUTHORS  man_1_simple_shell  shell.h shell_init.c  tokening.c
```

```shell
Hell_Shell>> /bin/ls
AUTHORS  Hell_Shell  README.md	auxiliar_functions.c  create_child.c  dir  execute.c  free_mem.c  generateAUTHORS  man_1_simple_shell  shell.h shell_init.c  tokening.c
```

## Authors:

- *Ricardo Sass* - [@bluegalaxy13](https://github.com/bluegalaxy13)
- *Philic Antwi Boasiako* - [@PhilBoa](https://github.com/PhilBoa)
