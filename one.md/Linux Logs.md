in [[Linux]] the way to view logs are 

syslog protocol follows RFC 5424
https://datatracker.ietf.org/doc/html/rfc5424

most often found in the /var/log dir
auth.log || secure- keeps log for successful or failed logins

maillog

kern - Kernel logs

dmesg - repo for device driver messages

faillog - failed logins

cron - crond related messages

daemon.log - running d processess

btmp - failed login attempts

utmp - current login state by user

wtmp - each login/logout, contains info about successful loging and boot ties
	sudo lastb


lastlog - every users last login

From loggly.com
popular tools for logging include
rsyslog
syslog-ng
logstash
fluentd

#From class notes
.gz is the normal log rotation for compression
logrotate.conf is where the details can be found

