# service-monitor-script work well for hadong
This script monitors the service running on your linux based servers  and notify you by mail


This scripts checks running service's which you specify in service.txt and inform you by mail if service is down, This script run as cron jobs, Please use the following details to configure on it on your server


First give the executable permission to shell script by using following command

chmod a+x <SCRIPT-NAME>.sh


add the service name in service.txt file, I have already added mongo to check my mongodb is running or not

add txt file with service name and intially put 0 in it, I have added mongo.txt 

Configure post fix to setup gmail please use this link to configure it

https://rtcamp.com/tutorials/linux/ubuntu-postfix-gmail-smtp/

run the service as cron jobs

