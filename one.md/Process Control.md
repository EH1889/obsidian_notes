In [[Linux]] Process is an instance of a running program. It can be identified by 
```
ps aux

```
to background a job - bg
to foregroudn a job - fg
to kill a job in the bg kill %1, where 1 is the job that is paused 
jobs shows current jobs
To see your loging shell 'echo $$'
ps -f -u <username> # will give all jobs run by User 

Jobs are shown by PID
PID 1 is init
PID 2 is kernel

you can find the pid in the file system
/proc/PID/

running PS 
F stands for flags, ie process Flags
1 is forked but didn't exec
4 means super-user priv
5 means both
0 means neither

Process states
R - running
D- Uninterruptibe sleep
S - interruptable sleep
T - Stopped
Z - Zombie

needs further research
=================

ps -aM adds a layer of secruity data

https://access.redhat.com/sites/default/files/attachments/processstates_20120831.pdf
