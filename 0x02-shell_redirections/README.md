#!/bin/bash
echo "Hello, World" : This script prints “Hello, World”, followed by a new line to the standard output.
echo "\"(Ôo)'" : This script displays a confused smiley (Ôo).
cat /etc/passwd : This script displays the content of the /etc/passwd file.
cat /etc/passwd /etc/hosts : This script displays the content of /etc/passwd and /etc/hosts
tail /etc/passwd : This script displays the last 10 lines of /etc/passwd
head /etc/passwd : This script displays the first 10 lines of /etc/passwd
head -n 3 iacta | tail -1 : This script displays the third line of the file iacta.
echo 'Best School'  >> "\\*\\\\'\"Best School\"\\'\\\\*$\\?\\*\\*\\*\\*\\*:)" : This script creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
ls -la > ls_cwd_content : This script writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
tail -1 iacta >> iacta : This script duplicates the last line of the file iacta.

find . -name "*.js" -type f -delete : This script deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
find . -mindepth 1 -type d | wc -l : This script counts the number of directories and sub-directories in the current directory. However, it does not take current and parent directories into account, but it counts hidden directories.

ls -t1 | head : This script displays the 10 newest files in the current directory. With the following requirements: One file per line and Sorted from the newest to the oldest

cat /etc/passwd | grep "root" : This script displays lines containing the pattern “root” from the file /etc/passwd
sort | uniq -u : This script  takes a list of words as input and prints only words that appear exactly once. It follows these additional requirements: 1) Input format: One line, one word; 2) Output format: One line, one word; and 3) Words should be sorted
cat /etc/passwd | grep "bin" | wc -l : This script displays the number of lines that contain the pattern “bin” in the file /etc/passwd
cat /etc/passwd | grep -A 3 "root" : This script displays lines containing the pattern “root” and 3 lines after them in the file /etc/passwd
cat /etc/passwd | grep -v "bin" : This script displays all the lines in the file /etc/passwd that do not contain the pattern “bin”.
cat /etc/ssh/sshd_config | grep "^[a-zA-Z]" : This script displays all lines of the file /etc/ssh/sshd_config starting with a letter. It also includes capital letters as well.

tr Ac Ze : This script replaces all characters A and c from input to Z and e respectively.
tr -d cC : This script removes all letters c and C from input.
