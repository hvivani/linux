service/testjob example with upstart

What is upstart ?
Upstart is an event-based replacement for the /sbin/init daemon which handles starting of tasks and services during boot, stopping them during shutdown and supervising them while the system is running.

Where the configuration files resides ?
/etc/init

Useful commands:

sudo initctl reload-configuration
 
sudo initctl start testjob
 
sudo initctl stop testjob
 
sudo initctl status testjob
