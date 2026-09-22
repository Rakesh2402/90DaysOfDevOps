How processes are created and managed

Processes in Linux
Processes are instances of running programs. For ex. if you do pin www.google.com then ping process is created. You can list processes using ps(ps ax, ps ef) or top commands.

Process states
running : Active process.
sleeping : Idle process.
Stopped : Process suspended by signal SIGSTOP (Ctrl+Z, Ctrl+C). It can be resumed by a SIGCONT signal.
Zombie : The process has terminated, but its entry in the process table still exists because its parent process has not yet read its exit status.

List 5 commands you would use daily
-cd, pwd, ls, ls -a, ps, top.

What systemd does and why it matters
- Systemd manages system resources and daemons, and handles components called units. These units have a name, type, and their own configuration file. Systemd also maintains a system log called the journal.
 -It checks for any remaining hardware that needs drivers loaded.
-It mounts up all the different file systems and disks so they’re accessible.
-It starts launching all the background services you will need, like networking, sound, power management…
-It handles user logins once you get to the graphical prompt.
-It loads up your desktop environment with the panels and menus.

The core components of Linux (kernel, user space, init/systemd)
