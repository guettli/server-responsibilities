# server-responsibilities

You want to host your application on servers provided by someone. Then this checklist might help. Who is responsible for what?

Details like [SLA (service-level agreements)](https://en.wikipedia.org/wiki/Service-level_agreement) can be build on top of each topic.

Feedback is welcome

## Daily
No manual interaction should be needed for the daily usage. |

| Topic | Responsible | Note |
|-------|-------------|------|
| provide dns server | |
| provide ntp server | |
| run dns client | |
| run ntp client | |
| provide database | |
| run database client | |
| run web server | |
| provide RPM/DPKG repository | |
| run mail server | |
| provide smarthost for mail server. | |
| provide IMAP/POP3 services | |
| provide storage server | |
| run storage client | |
| run ssh server | |
| Uninterruptible power supply | |


## Initial, Expand, Repair
| Topic | Responsible | Note |
|-------|-------------|------|
| provide more disc space (if needed) | |
| provide more CPU, RAM, IO | |
| replace hardware parts | |
| upgrade operating system | |
| create new linux users | |
| manage RAID | |
| create Cert (for example for https) | |
| create SSH-server cert | |
| unsure ssh-server cert does not change (on upgrade, or server move) | |
| install new packages (rpm, dpkg) | |
| upgrade packages (fixes) | |
| provide IP addresses | |
| Create DNS entries for IP adresses. | |
| create root password | |
| know root password | |
| manage crontab entries | |
| enable/disable services | |


## Networking
| Topic | Responsible | Note |
|-------|-------------|------|
| provide default gateway | |
| maintain local firewall (running on the server) (default should be "none") | |
| maintain network firewall (running outside the server) | |
| maintain local routes (running on the server) (default should be "none") | |


## Monitor
| Topic | Responsible | Note |
|-------|-------------|------|
| enough disk space | |
| enough CPU, RAM, IO | |
| system logs | |
| application logs | |
| RAID | |


## Hardware
| Topic | Responsible | Note |
|-------|-------------|------|
| provide power | |
| provide network | |
| stand by hardware | |

## Backup
| Topic | Responsible | Note |
|-------|-------------|------|
| responsible for backup | |
| responsible for restore from backup | |
| responsible for checking if restore from backup would work. | |
| responsible for checking uninterruptible power supply | |
| Backup for database. | |
