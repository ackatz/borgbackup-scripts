# borgbackup-scripts

Local and remote (rsync) borgbackup scripts that can send e-mails through SendGrid for successes/failures. 

placed in: /etc/cron.daily

borgbackup log files are also stored under /var/log/borg-backup/local or /var/log/borg-backup/remote.

## Requirements:

https://rsync.net/products/attic.html - cloud storage for borg backup  
https://sendgrid.com - email api provider
