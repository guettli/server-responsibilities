# server-responsibilities

You want to host your application on servers provided by someone. Then check this list. Who is responsible for what?

Feedback is welcome


## daily

No manual interaction should be needed for the daily usage.

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
* Uninterruptible power supply


## Initial, Expand, Repair
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
* provide IP addresses
* Create DNS entries for IP adresses.
* create root password
* know root password
* manage crontab entries
* enable/disable services

## Networking
* provide default gateway
* maintain local firewall (running on the server) (default should be "none")
* maintain network firewall (running outside the server)
* maintain local routes (running on the server) (default should be "none")


## monitor
* enough disk space
* enough CPU, RAM, IO
* system logs
* application logs
* RAID

## Hardware
* provide power
* provide network
* stand by hardware

## Backup
* responsible for backup
* responsible for restore from backup
* responsible for checking if restore from backup would work.
* responsible for checking uninterruptible power supply
