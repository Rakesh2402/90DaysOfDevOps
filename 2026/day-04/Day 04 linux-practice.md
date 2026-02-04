Task

Check running processes
Inspect one systemd service
Capture a small troubleshooting flow

=============================================================================

Guidelines
Follow these rules while creating your practice note:

Run and record output for at least 6 commands
Include 2 process commands (ps, top, pgrep, etc.)
Include 2 service commands (systemctl status, systemctl list-units, etc.)
Include 2 log commands (journalctl -u <service>, tail -n 50, etc.)
Pick one service on your system (example: ssh, cron, docker) and inspect it
Keep it simple and actionable

=============================================================================

Commands to check running processes

ps - shows all the running process in your current terminal session
ps -a - shows all the running process from all terminal session 
ps aux - shows all process with full details

=============================================================================

Commands to check services
Start: systemctl start servicename 
Stop: systemctl stop servicename 
Restart: systemctl restart servicename 
Status: systemctl status servicename
systemctl status ssh - gives status of ssh
systemctl list-units --type=service  - Lists all active services managed by systemd.
                       Helps understand which background services are running.

=============================================================================

Log commands

journalctl -u nginx - shows log of nginx
journalctl | tail -n 50 

