# Basics

In this file you will be able to see the scripts in order to apply simple commands on shell. These scripts will give you the opportunity to activate directly these commands without any error, and will make you able to understand how to create a script and also how to give a file the authority to execute the command given to.

In this file you will see as below:
- [0-current_working_directory](https://github.com/eno007/shell/blob/main/basics/0-current_working_directory) 
**(Script that contains the command `pwd` and will identify at which path you are working.)** 
- [1-listit](https://github.com/eno007/shell/blob/main/basics/1-listit) 
**(Script that will list files. `ls` on its own lists all files in the current directory except for hidden files. )**
- [2-bring_me_home](https://github.com/eno007/shell/blob/main/basics/2-bring_me_home) 
**(Script that contains command `cd` and in Linux it offers several ways to navigate and change the working directory using the terminal window. It lets you change directories using relative and absolute paths, move to parent or root directories, or find directories with incomplete names.)** 
  - *(**The `cd` command is a built-in shell command. This means that its behavior varies slightly between shells since it uses shell environment variables.**)* 
- [3-listfiles](https://github.com/eno007/shell/blob/main/basics/3-listfiles) 
**Script that contains command `ls -l` and it is used to list :** 
  1. *contents of the directory in a table* 
  2. *format with columns including content permissions*, 
  3. *number of links to the content*, 
  4. *owner of the content*,
  5. *group owner of the content*,
  6. *size of the content in bytes*,
  7. *last modified date / time of the content*,
  8. *file or directory name*.
- [4-listmorefiles](https://github.com/eno007/shell/blob/main/basics/4-listmorefiles) 
**Script that contains command `ls -l -a`  or you can type `ls -a -l` or `ls -la` or `ls -al` to list files or directories in a table format with extra information including hidden files or directories:** 
- [5-listfilesdigitonly](https://github.com/eno007/shell/blob/main/basics/5-listfilesdigitonly) 
**Script that contains command `ls -l -a -n`  or you can type `ls -lan` to list long format with user and group IDs, displayed numerically including hidden files (starting with .)** 
- [6-firstdirectory](https://github.com/eno007/shell/blob/main/basics/6-firstdirectory) 
**Script that contains command `mkdir path/name of the new directory`  to create a directory in the required path with the required title.**
- [7-movethatfile](https://github.com/eno007/shell/blob/main/basics/7-movethatfile) 
**Script that contains command `mv path/file_name to path/new_directory`  to move a file in the required path at a required direction.** 
- [8-firstdelete](https://github.com/eno007/shell/blob/main/basics/8-firstdelete) 
**Script that contains command `rm path/file_name`  to remove a file in the required path at a required direction.** 
- [9-firstdirdeletion](https://github.com/eno007/shell/blob/main/basics/9-firstdirdeletion) 
**Script that contains command `rm -rf path/directory_name`  to remove a directory in the required path.**
- [10-back](https://github.com/eno007/shell/blob/main/basics/10-back) 
**Script that contains command `cd -`  to change the working directory to the previous one.**
- [11-lists](https://github.com/eno007/shell/blob/main/basics/11-lists) 
**Script that contains command `ls -la`  to list all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the required directory (in this order), in long format.**
- [12-file_type](https://github.com/eno007/shell/blob/main/basics/12-file_type) 
**Script that contains command `file`  that prints the type of a specific file in the given directory.**
- [13-symbolic_link](https://github.com/eno007/shell/blob/main/basics/13-symbolic_link) 
**Script that contains command `ln`  that creates a symbolic link in the current working directory.**
- [14-copy_html](https://github.com/eno007/shell/blob/main/basics/14-copy_html) 
**Script that contains command `cp`  that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.**
- [15-lets_move](https://github.com/eno007/shell/blob/main/basics/15-lets_move) 
**Script that contains command `mv [A-Z]`  that that moves all files beginning with an uppercase letter to a specific directory.**
- [16-clean_emacs](https://github.com/eno007/shell/blob/main/basics/16-clean_emacs) 
**Script that contains command `rm *`  that deletes all files in the current working directory that end with a specific character.**
- [17-tree](https://github.com/eno007/shell/blob/main/basics/17-tree) 
**Script that contains command `mkdir -p`  that creates the given directories as requested in the current directory.** 
