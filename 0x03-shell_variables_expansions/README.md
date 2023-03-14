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
printf "%.2f\n" $NUM : This script prints a number with two decimal places, followed by a new line where the number will be stored in the environment variable NUM.
printf '%x\n' $DECIMAL : This script converts a number from base 10 to base 16. The number in base 10 is stored in the environment variable DECIMAL. The script displays the number in base 16, followed by a new line
tr '[A-Za-z]' '[N-ZA-Mn-za-m]' : This script encodes and decodes text using the rot13 encryption. Assume ASCII.
cat -n | cut -c6- | grep -vP "[02468]\t" | cut -f2 : This script prints every other line from the input, starting with the first line.
printf '%o\n' $(( 5#$( echo $WATER | tr water 01234) + 5#$( echo $STIR | tr stir. 01234 ) )) | tr 01234567 behlnort : This script dds the two numbers stored in the environment variables WATER and STIR and prints the result. Where; WATER is in base water. STIR is in base stir. The result is in base bestchol.
