# server-responsibilities

You want to host your application on servers provided by someone. Then check this list. Who is responsible for what?


daily (no manual interaction)

* provide dns server
* provide ntp server
* run dns client
* run ntp client
* provide database
* run database client
* run web server
* provide RPM/DPKG repository
* run mail server
* provide smarthost for mail server.
* provide IMAP/POP3 services
* provide storage server
* run storage client
* run ssh server

monitor
* enough disk space
* enough CPU, RAM, IO
* system logs
* application logs
* RAID

Initial, Expand, Repair
* provide more disc space (if needed)
* provide more CPU, RAM, IO
* replace hardware parts
* upgrade operating system
* create new linux users
* manage RAID
* create Cert (for example for https)
* create SSH-server cert
* unsure ssh-server cert does not change (on upgrade, or server move)
* install new packages (rpm, dpkg)
* upgrade packages (fixes)
* provide additional IP addresses

Networking
* provide default gateway
* maintain firewall

Hardware
* provide power
* provide network
* stand by hardware

Backup
* responsible for backup
* responsible for restore from backup
* responsible for checking if restore from backup would work.
