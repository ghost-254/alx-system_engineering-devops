#!/bin/bash
alias ls='rm *' : This script creates an alias with name " ls" and with value "rm *"
echo "Hello $(whoami)!" : This script prints Hello user where user is the current Linux user
PATH=$PATH:/action : This script Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
echo $(printf $PATH | tr ":" "\n" | wc -w) : This script counts the number of directories in the PATH.
printenv : This script lists environment variables.
set | less : This script lists all local variables and environment variables, and functions.
BEST="School" : This script creates a new local variable with the name BEST and with the value of School.
