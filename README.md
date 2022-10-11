# Linux-intro-cli-task


-	Use Command ` whoami ` and figure out the output.
You can use man to know more about whoami.

Command: whoami
Output: kali

-	Use Command ` hostname ` and figure out the output.
You can use man to know more about hostname.

Command: hostname
Output: kali

-	Count how many words in any file in your system?

Command: wc sarah.txt
Output: 1 11 55 sarah.txt

-	Find the logged in users in your system?

Command: w
Output: 08:05:52 up  3:28,  1 user,  load average: 0.24, 0.15, 0.06
USER     TTY      FROM             LOGIN@   IDLE   JCPU   PCPU WHAT
kali     tty7     :0               04:43    3:27m 50.59s  0.26s xfce4-session

-	Use history command and run one of the processes that appears in the history without re-write the command?

Command: history 
Output: 1  
    2  man ls
    3  man man
    4  man cel
    5  man cal
    6  man history
    7  cat /etc/shadow
    8  sudo cat /etc/shadow
    9  ls -a /home
   10  whoami
   11  id
   12  hostname
   13  uptime
   14  date
   15  date +"%Y, %m, %d"
   16  cal
   17  echo "HELLo"
   18  history
   19  echo "HELLo"
   20  history| grep -i search tail
   21  touch sarah.txt
   22  cat 1> sarah.txt
   23  cal 1> sarah.txt
   24  man whoami
   25  whoami
   26  man hostname
   27  hostname
   28  man count
   29  man WC
   30  cat>>sarah.txt
   31  wc sarah.txt
   32  w
Command: !25 
Output: whoami
Kali
-	Find since when your system was running?

Command: uptime
Output: 08:08:07 up  3:30,  1 user,  load average: 0.12, 0.14, 0.07

-	Get the data and time in Dubai using CLI?
-	
Command: TZ=Dubai  date 
Output: Tue Oct 11 12:38:02 PM Dubai 2022

-	Store calendar output to a file called calender.txt

Command: in cal >  calender.txt
Output:

-	Use this command echos “Oh there is an error” then save the error(output) if appears to file called logs.txt

Command: echo "Oh there is an error" 2> logs.txt
Output:

 After every task write the command you used 
 and the output you got in this README.md file


**Always remember to use man command to explore the commands you are using!**



