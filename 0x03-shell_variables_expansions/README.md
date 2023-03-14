#!/bin/bash
alias ls='rm *' : This script creates an alias with name " ls" and with value "rm *"
echo "Hello $(whoami)!" : This script prints Hello user where user is the current Linux user
PATH=$PATH:/action : This script Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
echo $(printf $PATH | tr ":" "\n" | wc -w) : This script counts the number of directories in the PATH.
printenv : This script lists environment variables.
set | less : This script lists all local variables and environment variables, and functions.
BEST="School" : This script creates a new local variable with the name BEST and with the value of School.
export BEST="School" : This script creates a new global variable
echo $((128 + TRUEKNOWLEDGE)) : This script prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line.
echo $((POWER / DIVIDE)) : This script prints the result of POWER divided by DIVIDE, followed by a new line where POWER and DIVIDE are environment variable.
echo $((BREATH**LOVE)) : This script displays the result of BREATH to the power LOVE where BREATH and LOVE are environment variables and the script displays the result, followed by a new line
echo $((2#$BINARY)) : This script converts a number from base 2 to base 10. Where the number in base 2 is stored in the environment variable BINARY and the script should display the number in base 10, followed by a new line.
echo {a..z}{a..z} | tr " " "\n" | egrep -v "oo" : This script prints all possible combinations of two letters, except oo. Where; Letters are lower cases, from a to z. One combination per line. The output should be alpha ordered, starting with aa
Do not print oo. Your script file should contain maximum 64 characters
