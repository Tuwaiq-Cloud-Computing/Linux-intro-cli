# Linux-intro-cli-task


-	Use Command ` whoami ` and figure out the output.
You can use man to know more about whoami.

Command: whoami
Output: Kali


-	Use Command ` hostname ` and figure out the output.
You can use man to know more about hostname.
 Command: hostname
 Output: Kali

-	Count how many words in any file in your system?
 Command: wc sara.txt
 Output: 2 2 10sara.txt


-	Find the logged in users in your system?
 Command: who 
 Output: kali     tty7         2022-10-11 06:12 (:0)
         kali     pts/1        2022-10-11 07:14
         kali     pts/5        2022-10-11 07:49
  
-	Use history command and run one of the processes that appears in the history without re-write the command?
  Command: history 
            !57
  Output:     hostname

-	Find since when your system was running?
  Command: uptime 
  Output:  08:08:38 up  1:56,  2 users,  load average: 0.06, 0.10, 0.04
  
-	Get the data and time in Dubai using CLI?
  Command: TZ=Dubai  date 
  Output: Tue Oct 11 3:30:08 PM Dubai 2022

-	Store calendar output to a file called calender.txt
 Command: touch calender.txt
          cal > calender.txt
 Output: show the calendar in the file 
 
-	Use this command echos “Oh there is an error” then save the error(output) if appears to file called logs.txt
 Command:  echo "Oh there is an error" 2> logs.txt
 
 After every task write the command you used 
 and the output you got in this README.md file


**Always remember to use man command to explore the commands you are using!**



