### See Logs

#tail -f /var/log/syslog

### crontab

$ crontab -e

### View

$ crontab -l

#### Sampe Cron file

$* * * * * cd Desktop && /usr/bin/python3.8 test.py >> test.out

### Stop Cron Service

$ /etc/init.d/cron stop

### Start Cron service

$ /etc/init.d/cron start

## Sample-Config

      MAILTO="" (avoidsend mail)
      
      
      * * * * * cd Desktop/Automation/Backup/ && python3 paloalto1.py >> test.out

      0 10 * * * /bin/python3 /Network/Config-Backup/backup.py


https://crontab.guru/

![image](https://user-images.githubusercontent.com/49310101/122632597-b114eb80-d088-11eb-888a-13c94bbdbefa.png)



file:///home/cisco/Desktop/Screenshot%20from%202021-07-07%2014-34-48.png![image](https://user-images.githubusercontent.com/49310101/125158092-5bfe5e00-e18c-11eb-9828-fbed0c2553ac.png)
