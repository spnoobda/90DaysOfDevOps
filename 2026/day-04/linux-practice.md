Process commands:
ps -> gives only a real time snapshot of the current running dynamic process. It shows 4 things, PID, memory used, CPU time and the command that started the process
top -> it gives the real time dynamic usages of all the running as well as the inactive processes, a better form of ps in a way.


Service commands:
systemctl status -> can check whether a process is successfully running or not
systemctl list-units -> used to display units that systemd currently has in memory, including services, sockets, mount points, and more


Log commands:
journalctl -u docker --> shows the logs for docker, can be used to check for other services as well
tail -n --> after -n there should be some number and it will show the last 'n' lines of that file or log. For eg: journalctl -u docker -n 3, it will hsow the last 3 lines of the log
