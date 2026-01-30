How processes are created and managed
- process are created by using fork() system command & exec(): replaces the current process memory with a new program.
- process different states - R-running, S- Interupted sleep, D- Uniinterupted sleep, z- Zombie, T- Stopped.

List 5 commands you would use daily
-cd, pwd, ls, ls -a, ps, top.

What systemd does and why it matters
- Systemd manages system resources and daemons, and handles components called units. These units have a name, type, and their own configuration file. Finally, Systemd also maintains a system log called the journal.
 -It checks for any remaining hardware that needs drivers loaded.
-It mounts up all the different file systems and disks so they’re accessible.
-It starts launching all the background services you will need, like networking, sound, power management…
-It handles user logins once you get to the graphical prompt.
-It loads up your desktop environment with the panels and menus.

The core components of Linux (kernel, user space, init/systemd)
