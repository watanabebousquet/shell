When using vmstat and iostat, please add bellow crontab job for zabbix
#crontab -u zabbix -e

* * * * * /usr/share/zabbix/scripts/zabbix_vmstat_cron.sh
* * * * * /usr/share/zabbix/scripts/zabbix_iostat_cron.sh