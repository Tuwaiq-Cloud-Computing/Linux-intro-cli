# Linux-intro-cli-task


-	Use Command ` whoami ` and figure out the output.
You can use man to know more about whoami.

Command: ` Command ` <br/>
Output: -------------------


-	Use Command ` hostname ` and figure out the output.
You can use man to know more about hostname.
-	Count how many words in any file in your system?
-	Find the logged in users in your system?
-	Use history command and run one of the processes that appears in the history without re-write the command?
-	Find since when your system was running?
-	Get the data and time in Dubai using CLI?
-	Store calendar output to a file called calender.txt
-	Use this command echos “Oh there is an error” then save the error(output) if appears to file called logs.txt

 After every task write the command you used 
 and the output you got in this README.md file


**Always remember to use man command to explore the commands you are using!**


Command: whoami
Output: kali

Command: hostname
Output: kali

Command: wc Faisal   
Output: 0 0 0 Faisal

Command: w
Output: 07:58:07 up 16 min,  1 user,  load average: 0.03, 0.03, 0.01
USER     TTY      FROM             LOGIN@   IDLE   JCPU   PCPU WHAT
kali     tty7     :0               07:42    1:46m 11.86s  0.30s xfce4-sessio

Command: history
!30
Clear 
Output: 

Command: uptime
Output: 08:09:34 up 27 min,  1 user,  load average: 0.04, 0.05, 0.01

Command: TZ=emirates/DUBAI date

Output:Tue Oct 11 12:04:23 PM emirates 2022

Command: cat >> /home/kali/desktop/calendar.txt
Output:cat >>/home/kali/desktop/calendar.txt 

Command: echos 'oh there is an error'2> logs.txt
Output: Command 'echos' not found, did you mean:
  command 'echo' from deb coreutils
Try: sudo apt install <deb name>



