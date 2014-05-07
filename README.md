nagios-conf
===========

Configuration for the Nagios monitoring software for our different sandbox services.

In order to configure your Linux Nagios3 instance, copy all the cfg files provided into your /etc/nagios3 directory and add the following lines to your nagios.cfg file



```
cfg_file=/etc/nagios3/servers.cfg
cfg_file=/etc/nagios3/hostgroups.cfg
cfg_file=/etc/nagios3/services.cfg
cfg_file=/etc/nagios3/servicegroups.cfg
cfg_file=/etc/nagios3/templates.cfg
```