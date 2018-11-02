# server-responsibilities

You want to host your application on servers provided by someone. Then check this list. Who is responsible for what?


daily

* provide dns server
* provide ntp server
* run dns client
* run ntp client
* provide database
* run database client
* run web server
* install fixes RPM/DPKG
* provide RPM/DPKG repository
* run mail server
* provide smarthost for mail server.
* provide IMAP/POP3 services
* provide storage server
* run storage client

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
* Create Cert (for example for https)

Networking
* Provide default gateway
* Maintain firewall

Hardware
* Provide power
* Provide network
* stand by hardware

Backup
* responsible for backup
* responsible for restore from backup
* responsible for checking if restore from backup would work.
