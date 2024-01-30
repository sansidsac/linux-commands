# linux-commands
oem@DALAB44:~$pwd
/home/oem

oem@DALAB44:~$ cd SREEKUMAR

oem@DALAB44:~/SREEKUMAR$ ls
sample

oem@DALAB44:~/SREEKUMAR$ ls -l
total 4
-rw-rw-r-- 1 oem oem 9 Jan 29 12:05 sample

oem@DALAB44:~/SREEKUMAR$ ls -h
sample

oem@DALAB44:~/SREEKUMAR$ ls -t
sample

oem@DALAB44:~/SREEKUMAR$ lsns
        NS TYPE   NPROCS   PID USER COMMAND
4026531834 time       72   998 oem  /lib/systemd/systemd --user
4026531835 cgroup     72   998 oem  /lib/systemd/systemd --user
4026531836 pid        72   998 oem  /lib/systemd/systemd --user
4026531837 user       72   998 oem  /lib/systemd/systemd --user
4026531838 uts        72   998 oem  /lib/systemd/systemd --user
4026531839 ipc        72   998 oem  /lib/systemd/systemd --user
4026531840 net        72   998 oem  /lib/systemd/systemd --user
4026531841 mnt        69   998 oem  /lib/systemd/systemd --user
4026532815 mnt         2  1044 oem  /snap/snapd-desktop-integration/83/usr/bin/snapd-desktop-integration
4026532818 mnt         1  1702 oem  /snap/snap-store/959/usr/bin/snap-store --gapplication-service

oem@DALAB44:~/SREEKUMAR$ touch text.txt

oem@DALAB44:~/SREEKUMAR$ ls
sample  text.txt

oem@DALAB44:~/SREEKUMAR$ rm sample

oem@DALAB44:~/SREEKUMAR$ ls
text.txt

oem@DALAB44:~/SREEKUMAR$ echo "textttt"
textttt

oem@DALAB44:~/SREEKUMAR$ ls -h
text.txt

oem@DALAB44:~/SREEKUMAR$ ls -t
text.txt

oem@DALAB44:~/SREEKUMAR$ touch text2.txt

oem@DALAB44:~/SREEKUMAR$ touch text3.txt

oem@DALAB44:~/SREEKUMAR$ cat text.txt text2.txt > text3.txt

oem@DALAB44:~/SREEKUMAR$ ls -r
text.txt  text3.txt  text2.txt

oem@DALAB44:~/SREEKUMAR$ ls -f
text3.txt  text.txt  text2.txt  .  ..

oem@DALAB44:~/SREEKUMAR$ touch sample.txt

oem@DALAB44:~/SREEKUMAR$ ls [s]*
sample.txt

oem@DALAB44:~/SREEKUMAR$ ls [t-z]*
text2.txt  text3.txt  text.txt

oem@DALAB44:~/SREEKUMAR$ man cat

oem@DALAB44:~/SREEKUMAR$ who
oem      tty2         2024-01-29 11:55 (tty2)

oem@DALAB44:~/SREEKUMAR$ whoami
oem

oem@DALAB44:~/SREEKUMAR$ uname -a
Linux DALAB44 6.2.0-37-generic #38~22.04.1-Ubuntu SMP PREEMPT_DYNAMIC Thu Nov  2 18:01:13 UTC 2 x86_64 x86_64 x86_64 GNU/Linux

oem@DALAB44:~/SREEKUMAR$ grep "ell" text.txt
hello

oem@DALAB44:~/SREEKUMAR$ rm sample.txt

oem@DALAB44:~/SREEKUMAR$ cp text.txt text2.txt 

oem@DALAB44:~/SREEKUMAR$ mv text.txt text1.txt

oem@DALAB44:~/SREEKUMAR$ wc -l text1.txt
1 text1.txt

oem@DALAB44:~/SREEKUMAR$ cal 2004
                            2004
      January               February               March          
Su Mo Tu We Th Fr Sa  Su Mo Tu We Th Fr Sa  Su Mo Tu We Th Fr Sa  
             1  2  3   1  2  3  4  5  6  7      1  2  3  4  5  6  
 4  5  6  7  8  9 10   8  9 10 11 12 13 14   7  8  9 10 11 12 13  
11 12 13 14 15 16 17  15 16 17 18 19 20 21  14 15 16 17 18 19 20  
18 19 20 21 22 23 24  22 23 24 25 26 27 28  21 22 23 24 25 26 27  
25 26 27 28 29 30 31  29                    28 29 30 31           
                                                                  

       April                  May                   June          
Su Mo Tu We Th Fr Sa  Su Mo Tu We Th Fr Sa  Su Mo Tu We Th Fr Sa  
             1  2  3                     1         1  2  3  4  5  
 4  5  6  7  8  9 10   2  3  4  5  6  7  8   6  7  8  9 10 11 12  
11 12 13 14 15 16 17   9 10 11 12 13 14 15  13 14 15 16 17 18 19  
18 19 20 21 22 23 24  16 17 18 19 20 21 22  20 21 22 23 24 25 26  
25 26 27 28 29 30     23 24 25 26 27 28 29  27 28 29 30           
                      30 31                                       

        July                 August              September        
Su Mo Tu We Th Fr Sa  Su Mo Tu We Th Fr Sa  Su Mo Tu We Th Fr Sa  
             1  2  3   1  2  3  4  5  6  7            1  2  3  4  
 4  5  6  7  8  9 10   8  9 10 11 12 13 14   5  6  7  8  9 10 11  
11 12 13 14 15 16 17  15 16 17 18 19 20 21  12 13 14 15 16 17 18  
18 19 20 21 22 23 24  22 23 24 25 26 27 28  19 20 21 22 23 24 25  
25 26 27 28 29 30 31  29 30 31              26 27 28 29 30        
                                                                  

      October               November              December        
Su Mo Tu We Th Fr Sa  Su Mo Tu We Th Fr Sa  Su Mo Tu We Th Fr Sa  
                1  2      1  2  3  4  5  6            1  2  3  4  
 3  4  5  6  7  8  9   7  8  9 10 11 12 13   5  6  7  8  9 10 11  
10 11 12 13 14 15 16  14 15 16 17 18 19 20  12 13 14 15 16 17 18  
17 18 19 20 21 22 23  21 22 23 24 25 26 27  19 20 21 22 23 24 25  
24 25 26 27 28 29 30  28 29 30              26 27 28 29 30 31     
31                                                                

oem@DALAB44:~/SREEKUMAR$ ps
    PID TTY          TIME CMD
   3381 pts/0    00:00:00 bash
   5695 pts/0    00:00:00 ps

oem@DALAB44:~/SREEKUMAR$ locate /home/oem/SREEKUMAR/text1.txt
/home/oem/SREEKUMAR/text1.txt

oem@DALAB44:~/SREEKUMAR$ ln text1.txt sample.txt
oem@DALAB44:~/SREEKUMAR$ cat sample.txt
hello

oem@DALAB44:~/SREEKUMAR$ wget www.youtube.com
--2024-01-30 10:25:17--  http://www.youtube.com/
Resolving www.youtube.com (www.youtube.com)... 142.250.182.142, 142.250.183.238, 142.250.193.110, ...
Connecting to www.youtube.com (www.youtube.com)|142.250.182.142|:80... connected.
HTTP request sent, awaiting response... 301 Moved Permanently
Location: https://www.youtube.com/ [following]
--2024-01-30 10:25:18--  https://www.youtube.com/
Connecting to www.youtube.com (www.youtube.com)|142.250.182.142|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: unspecified [text/html]
Saving to: ‘index.html’
index.html                                             [  <=>                                                                                                           ] 729.89K  2.27MB/s    in 0.3s    
2024-01-30 10:25:18 (2.27 MB/s) - ‘index.html’ saved [747403]

oem@DALAB44:~/SREEKUMAR$ sort text1.txt index.html
0&&ua.indexOf("Trident")<0&&ua.indexOf("MSIE")<0}ytcsi.setStart(w.performance?w.performance.timing.responseStart:null);var isPrerender=(d.visibilityState||d.webkitVisibilityState)=="prerender";var vName=!d.visibilityState&&d.webkitVisibilityState?"webkitvisibilitychange":"visibilitychange";if(isPrerender){var startTick=function(){ytcsi.setStart();d.removeEventListener(vName,startTick)};d.addEventListener(vName,startTick,false)}if(d.addEventListener)d.addEventListener(vName,function(){ytcsi.tick("vc")},
oem@DALAB44:~/SREEKUMAR$ sort index.html > new-index.html

oem@DALAB44:~/SREEKUMAR$ whereis ls
ls: /usr/bin/ls /usr/share/man/man1/ls.1.gz


oem@DALAB44:~/SREEKUMAR$ df
Filesystem     1K-blocks     Used Available Use% Mounted on
tmpfs             780616     2544    778072   1% /run
/dev/nvme0n1p2 490617784 35957816 429664488   8% /
tmpfs            3903072   624012   3279060  16% /dev/shm
tmpfs               5120        4      5116   1% /run/lock
/dev/nvme0n1p1    523248     6224    517024   2% /boot/efi
tmpfs             780612       64    780548   1% /run/user/30000
tmpfs             780612      120    780492   1% /run/user/29999
