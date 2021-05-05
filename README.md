# Diversion Whitelist for Merlin AdBlocking

**Diversion HomePage** https://diversion.ch/

Extended from https://github.com/PracticalChip/Adblocking

**Direct URL to access this whitelist from Diversion**

https://raw.githubusercontent.com/afterever/Diversion_Whitelist_for_Merlin_AdBlocking/main/RawWhitelist.txt

***Sysstat sar command***

vi /jffs/scripts/services-start //https://www.cyberciti.biz/faq/how-to-add-cron-job-on-asuswrt-merlin-wifi-router/

cru a sa1 "*/10 * * * * /opt/lib/sysstat/sa1 1 1"  //https://www.snbforums.com/threads/rt-86u-usb-2-0-port-not-mounting-at-boot.64123/page-3

cru a sa2 "59 23 * * * /opt/lib/sysstat/sa2 -A"  //https://www.thegeekstuff.com/2011/03/sar-examples/

cru a traffic "18 2 * * Sat cp -af /tmp/mnt/sda1/Traffic /tmp/mnt/USB_AC86U/BACKUP" #Traffic_Weely_Backup
