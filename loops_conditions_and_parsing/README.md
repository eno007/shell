# Loops, Conditions and Parsing
In this chapter, we will discuss about 3 important elements [loops](https://tldp.org/LDP/Bash-Beginners-Guide/html/sect_09_01.html), [conditions](https://acloudguru.com/blog/engineering/conditions-in-bash-scripting-if-statements) and [parsing](https://www.geeksforgeeks.org/how-to-pass-and-parse-linux-bash-script-arguments-and-parameters/) you will find projects where these concepts are tested and bring out to practice through different tasks and examples. 

## Loops in Unix
A loop is a powerful programming tool that enables you to execute a set of commands repeatedly. In this chapter, we will examine the following types of loops available to shell programmers −

- The while loop
- The for loop
- The until loop
- The select loop

You will use different loops based on the situation. For example, the while loop executes the given commands until the given condition remains true; the until loop executes until a given condition becomes true.

Once you have good programming practice you will gain the expertise and thereby, start using appropriate loop based on the situation. Here, while and for loops are available in most of the other programming languages like C, C++ and PERL, etc.

## Conditions
Assume that in the workplace, you are responsible for the decision making of any process that is getting implemented at a production level. There would be some level of checks you would be taking to branch out the next steps of execution. Similarly, if condition also allows deciding to decide what is the next set of commands that needs to be executed if the condition is met. These conditions can themselves be part of a complex script or maybe resonated with loops to solve next level complex problems. The if condition imposes a lot of built-in checks and comparison tools which makes the condition building even easier. In these topics, we are going to learn about if condition in shell script.

## Parsing
Parsing Arguments into bash scripts/ shell scripts is quite similar to the way in which we pass arguments to the functions inside Bash scripts. We’ll see the actual process of passing on the arguments to a script and also look at the way to access those arguments inside the script.

Projects are as below:
- [0-RSA_public_key.pub](https://github.com/eno007/shell/blob/main/loops_conditions_and_parsing/0-RSA_public_key.pub)
**Public key of my actual shell server.**
- [1-for_best_school](https://github.com/eno007/shell/blob/main/loops_conditions_and_parsing/1-for_best_school)
**Script that displays a given text 10 times using ``for`` loop.**
- [2-while_best_school](https://github.com/eno007/shell/blob/main/loops_conditions_and_parsing/2-while_best_school)
**Script that displays given text 10 times using `while` loop.**
- [3-until_best_school](https://github.com/eno007/shell/blob/main/loops_conditions_and_parsing/3-until_best_school)
**Script that displays given text 10 times using `until` loop.**
- [4-if_9_say_hi](https://github.com/eno007/shell/blob/main/loops_conditions_and_parsing/4-if_9_say_hi)
**(Script that displays a given text 10 times, but for the 9th iteration, displays another text using 
 `while` loop and `if` condition.)**
- [5-4_bad_luck_8_is_your_chance](https://github.com/eno007/shell/blob/main/loops_conditions_and_parsing/5-4_bad_luck_8_is_your_chance)
**Script that that loops from 1 to 10 and:**
1. displays "bad luck" for the 4th loop iteration
2. displays "good luck" for the 8th loop iteration
3. displays "Best School" for the other iterations.

**There are used `while` loop and `if`, `elif` and `else` statements.**
- [6-superstitious_numbers](https://github.com/eno007/shell/blob/main/loops_conditions_and_parsing/6-superstitious_numbers)
**Script that displays numbers from 1 to 20 and:**

1. displays 4 and then bad luck from China for the 4th loop iteration
2. displays 9 and then bad luck from Japan for the 9th loop iteration
3. displays 17 and then bad luck from Italy for the 17th loop iteration.

**There is used `while` loop combined with `case` statement**
- [7-clock](https://github.com/eno007/shell/blob/main/loops_conditions_and_parsing/7-clock)
**Script that uses `while` loop and displays the time for 12 hours and 59 minutes:**

1. display hours from 0 to 12
2. display minutes from 1 to 59.
- [8-for_ls](https://github.com/eno007/shell/blob/main/loops_conditions_and_parsing/8-for_ls)
**Script that uses `for` loop and displays:**

1. The content of the current directory
2. In a list format
3. Where only the part of the name after the first dash is displayed.
- [9-to_file_or_not_to_file](https://github.com/eno007/shell/blob/main/loops_conditions_and_parsing/9-to_file_or_not_to_file)
**(Script that uses one of the loops and also conditional statements that gives you information about a given file.

1. This Bash script should check if the file exists and print:
- if the file exists: school file exists
- if the file does not exist: school file does not exist
2. If the file exists, print:
 - if the file is empty: school file is empty
- if the file is not empty: school file is not empty
- if the file is a regular file: school is a regular file
- if the file is not a regular file: (nothing).)**
- [10-fizzbuzz](https://github.com/eno007/shell/blob/main/loops_conditions_and_parsing/10-fizzbuzz)
**Script that displays numbers from 1 to 100.**

1. Displays FizzBuzz when the number is a multiple of 3 and 5
2. Displays Fizz when the number is multiple of 3
3. Displays Buzz when the number is a multiple of 5
4. Otherwise, displays the number
5. In a list format.
- [11-read_and_cut](https://github.com/eno007/shell/blob/main/loops_conditions_and_parsing/11-read_and_cut)
**(Script that displays the content of the file given using `while` loop.)**
- [12-tell_the_story_of_passwd](https://github.com/eno007/shell/blob/main/loops_conditions_and_parsing/12-tell_the_story_of_passwd)
**Script that displays the content of the file /etc/passwd, using the `while` loop + IFS.**
- [13-lets_parse_apache_logs](https://github.com/eno007/shell/blob/main/loops_conditions_and_parsing/13-lets_parse_apache_logs)
**Script that displays the visitor IP along with the HTTP status code from the Apache log file.**
- [14-dig_the-data](https://github.com/eno007/shell/blob/main/loops_conditions_and_parsing/14-dig_the-data)
**Script that groups visitors by IP and HTTP status code, and displays this data.**
