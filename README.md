1/ └─$ whoami
kali

2/ └─$ hostname
kali
NAME
       whoami - print effective userid

SYNOPSIS
       whoami [OPTION]...

DESCRIPTION
       Print  the  user name associated with the current effective user ID.
       Same as id -un.

       --help display this help and exit

       --version
              output version information and exit

AUTHOR
       Written by Richard Mlynarik.

REPORTING BUGS
       GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
       Report   any   translation    bugs    to    <https://translationpro‐
       ject.org/team/>



3/└─$ cat>>hanan.txt
Hello this is HananAlghamdi

4/└─$ wc hanan.txt
 3  9 58 hanan.txt

5/─$ $ history 
    1  
    2  whome
    3  clear
    4  whomi
    5  clear
    6  whoami
    7  hostname
    8  man whoami
    9  cat>>hanan.txt
   10  wc hanan.txt
   11  uptime
   12  w
   ┌──(kali㉿kali)-[~]
└─$ !6
                                                                             
┌──(kali㉿kali)-[~]
└─$ whoami

6/┌──(kali㉿kali)-[~]
└─$ uptime
 12:19:52 up  2:32,  1 user,  load average: 0.03, 0.05, 0.01
 
 7/┌──(kali㉿kali)-[~]
└─$ TZ=Dubai date
Tue Oct 11 04:26:58 PM Dubai 2022

8/┌──(kali㉿kali)-[~]
└─$ ncal>calender.txt
                                                                             
┌──(kali㉿kali)-[~]
└─$ cat calender.txt  
    October 2022      
Su     2  9 16 23 30
Mo     3 10 17 24 31
Tu     4 11 18 25   
We     5 12 19 26   
Th     6 13 20 27   
Fr     7 14 21 28   
Sa  1  8 15 22 29   
                    

9/┌──(kali㉿kali)-[~]
└─$ echo " oh there is an error" 2> logs.txt


