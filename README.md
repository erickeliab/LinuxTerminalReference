# LinuxTerminalReference
Basic linux terminal commands for programmers

## What is Linux 

Linux is one of the most used operating system for programmers.  Most of them prefer Linux over other operating systems due to its versatility, power, security, and speed. Linux comprises several different pieces 

1.	Bootloader
2.	Kernel
3.	Init system
4.	Daemons
5.	Graphical server
6.	Desktop environment
7.	Application


## What is Kernel ?

This is the one piece of the whole that is actually called Linux. The kernel is the core of the system and manages the CPU, memory, and peripheral devices. The kernel is the lowest level of the OS.


## What is Linux Terminal/Console ?
The Linux console is a system console internal to the Linux kernel. The Linux console provides a way for the kernel and other processes to send text output to the user, and to receive text input from the user. The user typically enters text with a computer keyboard and reads the output text on a computer monitor.


## BASIC LINUX COMMANDS

| COMMANDS | PURPOSE |
| -------- |-----:|
|Ctrl + l / clear | Clears the screen |
| uname  | Gives the environment name of the system |
| q |quit|
| man |Gives a manual |
| uptime | Gives uptime details of the system (active time)|
| cd | change directory |
| cd.. | one directory back |
| pwd | gives the present working directory |
| ls | list files in the current directory |
| mkdr | make a new directory |
| ls -l | long list of files in the current directory |
| alias | create aliases |
| ls -a | list all files incluiding the hidden files in the directory |
| date | display today's date |
| cal | calculator (for nerds ) |
| w | Users using the system |
| whoami | The current logged in user|
| whereis | Gives the location of the utility/program in current directory |
| rm | Remove |
| rm -r | Recursively delete|
| touch | Creates a file |
| history | Shows the commands applied before on a file/folder|
| cat | The command ran (kinda like history)|
| head | The head of the command |
| !! (sudo) | instead of using sudo use !! at the end of the line |
| python -m SimpleHTTPServer | generates a simple web page over HTTP for the directory structure tree and can be accessed at port 8000 in browser till interrupt signal is sent.|
| $ sudo apt-get install mtr (On Debian based Systems) | In case mtr is not installed into your machine, apt or yum the required package |
| # mtr google.com | Investigate the connection network over google.com |
| Ctrl-x-e | Prompts and starts working in cheat sheet  |
| nl | Number the lines of a file |
| head | The head of the command |




## PERMISSIONS
__There are basically three types of permissions in linux__
1.	Read – permission to view content
2.	Write – permission to modify/add
3.	Execute – permission to ran a program

__These permissions have number values to represent them__
-	Read(r) – 4
-	Write(w) – 2
-	Execute(x) – 1
Sample permission string
__-rwx -r-x -r-x__

__This string is devided into three parts__
1.	(-) or (-D) for a file or directory
2.	(rwx) for a read,write and execute permission for the creator
3.	(r-x) for the read and execute permission for the group of users(sort of)
4.	(r-x) for the read + execute permission for everyone logged into the system

