#!/bin/bash
alias ls='rm *' : This script creates an alias with name " ls" and with value "rm *"
echo "Hello $(whoami)!" : This script prints Hello user where user is the current Linux user
PATH=$PATH:/action : This script Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program.
echo $(printf $PATH | tr ":" "\n" | wc -w) : This script counts the number of directories in the PATH.
printenv : This script lists environment variables.
