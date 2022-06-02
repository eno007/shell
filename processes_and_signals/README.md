# Processes and signals
In this directory there are going to be 11 tasks that are going to show how different process will be processed from the applied scripts. The scripts will have the first line '#!/usr/bin/env bash' and all the scripts will be checked from `Shellcheck`. Generally you are going to get information about:
1. What is a PID
2. What is a process
3. How to find a process’ PID
4. How to kill a process
5. What is a signal
6. What are the 2 signals that cannot be ignored

## Scripts with commands are as below:
- [0-what-is-my-pid](https://github.com/eno007/shell/blob/main/processes_and_signals/0-what-is-my-pid)                        
**(Script that contains the command `echo $$` and displays its own PID.)**          
- [1-list_your_processes](https://github.com/eno007/shell/blob/main/processes_and_signals/1-list_your_processes)                          
**(Script that will use command `ps -auxf` and that displays a list of currently running processes. Will show all processes, for all users, including those which might not have a TTY, display in a user-oriented format and show process hierarchy. )**           
- [2-show_your_bash_pid](https://github.com/eno007/shell/blob/main/processes_and_signals/2-show_your_bash_pid)                              
**(Script that contains command `ps` `grep` that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.)**        
- [3-show_your_bash_pid_made_easy](https://github.com/eno007/shell/blob/main/processes_and_signals/3-show_your_bash_pid_made_easy)                        
**Script that contains command `pgrep -l` and it is used to displays the PID, along with the process name, of processes whose name contain the word bash.
- [4-to_infinity_and_beyond](https://github.com/eno007/shell/blob/main/processes_and_signals/4-to_infinity_and_beyond)                                
**Script that contains loop `while` to create a script that displays "To infinity and beyond" indefinitely which in between each iteration of the loop, add a "sleep 2".**               
- [5-dont_stop_me_now](https://github.com/eno007/shell/blob/main/processes_and_signals/5-dont_stop_me_now)                            
**Script that contains command `kill` that that stops "4-to_infinity_and_beyond" process.**                                                                                                       
- [6-stop_me_if_you_can](https://github.com/eno007/shell/blob/main/processes_and_signals/6-stop_me_if_you_can)  
**Script that contains command `pkill -f` script that stops "4-to_infinity_and_beyond" process.**                                                                                                          
- [7-highlander](https://github.com/eno007/shell/blob/main/processes_and_signals/7-highlander)                      
**Script that contains command `trap` and loop `while` that displays: "To infinity and beyond" indefinitely, with a "sleep 2" in between each iteration, and "I am invincible!!!" when receiving a SIGTERM signal.'.**   
- [67-stop_me_if_you_can](https://github.com/eno007/shell/blob/main/processes_and_signals/67-stop_me_if_you_can)                        
**Script that contains command `pkill -f` that stops the process of "7-highlander".**                                                                                     
- [8-beheaded_process](https://github.com/eno007/shell/blob/main/processes_and_signals/8-beheaded_process)                          
**Script that contains command `pkill -KILL -f` that stops "7-highlander" process.**                                                                                       
- [10-process_and_pid_file](https://github.com/eno007/shell/blob/main/processes_and_signals/10-process_and_pid_file)    
**Script that contains command `trap` `>>`, loop `while` and a `function()` in order to create the file requested containing its PID, displays 'To infinity and beyond' indefinitely, displays 'I hate the kill command' when receiving a SIGTERM signal, displays 'Y U no love me?!' when receiving a SIGINT signal, deletes the file requested and terminates itself when receiving a SIGQUIT or SIGTERM signal'.**                                                                                    
- [11-manage_my_process](https://github.com/eno007/shell/blob/main/processes_and_signals/11-manage_my_process)                                                                                                    
**Script that contains command `sudo pkill -f` `rm` `echo` and loop `case` with 4 proceses of execution for the input given by user: start, stop, restart and none of above that .** 
- [12-manage_my_process_if](https://github.com/eno007/shell/blob/main/processes_and_signals/12-manage_my_process_if)                                                                                                    
**Script that does the same thing like in script ```11-manage_my_process ``` but with loop `if` .**  
