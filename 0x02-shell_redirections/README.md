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

