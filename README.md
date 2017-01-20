# Fan_Raspberry
 Script to monitor the temperature of our Raspberry and to start and stop the fan to maintain a suitable temperature


OPERATION:

Connect the cable from the transistor base pin to pin No. 18 of Raspberry.

Then enter the cron configuration file (sudo nano crontab-e and insert the following line

@reboot   /home/pi/folder_where_the_script/fan_raspberry.py

Save the changes and restart the cron service with the following command:

sudo service restart cron

If you indicate that you can not because there is any service that is occupying, execute the following command:

sudo kill (nº process)

And then rerun restart cron service
