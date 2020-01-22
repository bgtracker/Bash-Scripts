
#!/bin/sh
log=samp.log
dat=`date`
samp="/home/samp/samp03svr"
cd /home/samp/

echo "${dat} watchdog script starting." >>${log}
while true; do
        echo "${dat} Server exited, restarting..." >>${log}
        mv /home/samp/server_log.txt /home/samp/server/logs/server_log.`date '+$
        ${samp} >> $log
        sleep 2
done
