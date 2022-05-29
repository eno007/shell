# I/O Redirections and filters
In this directory you will learn about what do the commands `head`, `tail`, `find` , `wc`, `sort`, `uniq`, `grep`, `tr` do. How to redirect standard output to a file, how to get standard input from a file instead of the keyboard, how to send the output from one program to the input of another program and how to combine commands and filters with redirections.
- [0-hello_world](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/0-hello_world) 
**(Script that contains the command `echo` that prints a message, followed by a new line to the standard output.)** 
- [1-confused_smiley](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/1-confused_smiley) 
**(Script that will use command `echo` and that displays a confused smiley. )**
- [2-hellofile](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/2-hellofile) 
**(Script that contains command `cat` and display the content of the specific file.)** 
- [3-twofiles](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/3-twofiles) 
**Script that contains command `cat` and it is used to display contents of multiple files requested.
- [4-lastlines](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/4-lastlines) 
**Script that contains command `tail` to display specific number of lines of a specific filename.** 
- [5-firstlines](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/5-firstlines) 
**Script that contains command `head` that displays the first 10 lines of a specific file .)** 
- [6-third_line](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/6-third_line) 
**Script that contains a combination of command `head` and `tail` that displays the third line of the file requested.**
- [7-file](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/7-file) 
**Script that contains command `echo` that creates a file named exactly as requested and containing a specific text  ending by a new line.**
- [8-cwd_state](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/8-cwd_state)
**(Script that contains the command `>>` that writes into the file requested the result of a command requested and to overwrite the file.)**
- [9-duplicate_last_line](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/9-duplicate_last_line)
**(Script that will use command `tail ` and `>>`  that duplicates the requested line of the file given. )**
- [10-no_more_js](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/10-no_more_js)
**(Script that contains command `find` deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.)**
- [11-directories](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/11-directories)
**Script that contains command `find` and `wc` that counts the number of directories and sub-directories in the current directory.** 
- [12-newest_files](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/12-newest_files)
**Script that contains command `ls` and `head` that displays the 10 newest files in the current directory.**
- [13-unique](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/13-unique)
**Script that contains command `sort` and `uniq` that takes a list of words as input and prints only words that appear exactly once.**
- [14-findthatword](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/14-findthatword)
**Script that contains a combination of command `grep` that displays lines containing the pattern requested from the file  requested.**
- [15-countthatword](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/15-countthatword)
**Script that contains command `grep` and `wc` that displays the number of lines that contain the pattern requested in the file requested.**
- [16-whatsnext](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/16-whatsnext)
**(Script that contains the command `grep` that displays lines containing the pattern requested and 'n' lines after them in the file given.)**
- [17-hidethisword](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/17-hidethisword)
**(Script that will use command `grep ` that displays all the lines in the file given that do not contain the pattern requested. )**
- [18-letteronly](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/18-letteronly)
**(Script that contains command `grep -i` that displays all lines of the file given starting with a letter that include capital letters as well.)**
- [19-AZ](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/19-AZ)
**Script that contains command `tr` that replace all characters from input to specified output respectively.**
- [20-hiago](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/20-hiago)
**Script that contains command `tr -d` that removes all given characters from input.**
- [21-reverse](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/21-reverse)
**Script that contains command `rev` that  reverse its input.**
- [22-users_and_homes](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/22-users_and_homes)
**Script that contains a combination of command `cut` and `sort` that displays all users and their home directories, sorted by users.**
- [23-empty_casks](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/23-empty_casks)
**Script that contains command `find`, `cut` and `rev` that finds all empty files and directories in the current directory and all sub-directories, only the names of the files and directories should be displayed (not the entire path), hidden files should be listed, one file name per line and the listing should end with a new line.**
- [24-gifs](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/24-gifs)
**(Script that contains the command `find`, `cut`, `sort` and `rev` that lists all the files with a specified extension in the current directory and all its sub-directories as requested.)**
- [25-acrostic](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/25-acrostic)
**(Script that will use command `cut ` and `paste` that  decodes acrostics that use the first letter of each line. )**
- [26-the_biggest_fan](https://github.com/eno007/shell/blob/main/io_redirections_and_filters/26-the_biggest_fan)
**(Script that contains command `cut` `sort` `uniq` `head` and `rev` that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.)**
