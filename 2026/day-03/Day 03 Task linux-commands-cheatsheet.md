Day 03 Tasks

Today’s goal is to build your Linux command confidence.

You will create a cheat sheet of commands focused on:

Process management
File system
Networking troubleshooting
This is the command toolkit you will reuse for years.
==================================================================
Expected Output
By the end of today, you should have:

A markdown file named:
linux-commands-cheatsheet.md

==================================================================

Process management commands

ps - shows all the running process in your current terminal session
ps -a - shows all the running process from all terminal session 
ps aux - shows all process with full details
ps aux | grep process_name - find a specific process 
top - real-time view of processes 
htop - interactive version of top 
kill PID - to kill any process by its PID
Killall process_name - kill any process buy its name

================================================================

File system commands

creating files

touch filename.txt - creates file
mkdir name - creates new directory

viewing file

pwd - present working directory6
ls - shows list of files available 
ls -l shows all files including hidden once like (.ssh file)
ls -t sorts file & folder according to date & time 
cat filename.txt - shows content of file 
head filename.txt - displays top 10 line 
tail filename.txt - displays last 10 line
tail -f filename.txt - displays last 10 lines of file and tracks changes appended to them at the end

Copying files

cp file.txt backup.txt - copy file
mv oldname.txt newname.txt - rename/move file
cp -r file.txt backup.txt - copy recursively
rm file.txt - removes file
rm -r dirname - delete directory and contents
rm -rf dirname - force delete

==============================================================

Network Commands

Testing Command

ping google.com - test network connectivity to a host
ping -c 4 google.com - ping 4 times then stop
traceroute google.com - show route packets take to destination

Network configuration 

ip addr or ip a - show IP addresses and network interfaces
ip link - show network interfaces status
ip route - show routing table
ifconfig - older command to show network interfaces 


DNS queries

dig google.com - detailed DNS lookup
curl google.com - fetch web page content

netstat -tulpn - show listening ports and connections
ss -tulpn - modern replacement for netstat
lsof -i :80 - show what's using port 80




