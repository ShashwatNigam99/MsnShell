# OS Assignment 2

Assignment On Making a shell in C with piping, redirection, signal handling.

## Running Instructions

* Run `make`
* Run `make clean`
* `./msnshell` to run the shell

## Features implemented

* cd
* ls
* echo
* pwd
* clear
* exit
* pinfo
* kjob
* fg
* bg
* overkill
* setenv
* unsetenv
* ctrlZ and ctrlC handlers
* jobs

#### The shell also supports background and foreground processes.
#### An `&` following the command name runs it in background. Also a notification is displayed after the background process exits

## Bonus Features

* clock
* remindme

## File structure

* builtins.c - builtin commands
* env.c - setenv and unsetenv
* jobs.c - kjob,overkill,jobs,fg,bg
* ls.c - ls command
* pinfo.c - pinfo command
* utilities.c - utility functions
* msnshell.c - main file
