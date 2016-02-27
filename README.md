# uTorrent-Sever-init-script
A simple init script to start/stop/restart utserver.
 
Based on [this script](https://gist.github.com/vortex-5/1221418)
 
Installation
--
wget --no-check-certificate -O /etc/init.d/utserver https://raw.githubusercontent.com/Artyum1/uTorrent-Sever-init-script/master/utserver-init-script.sh
 
chmod +x /etc/init.d/utserver

**Don't forget to change lines 25 & 26.**
 
How to use
--
service utserver start|stop|status|restart|force-reload|log
 
To make it start at boot
--
update-rc.d utserver defaults
