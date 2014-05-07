nagios-conf
===========

Configuration for the Nagios monitoring software for our different sandbox services.

In order to apply this configuration files to your Nagios instance, copy all the cfg files provided in any directory in your server (typically `/etc/nagios/conf.d/smart`) and be sure that that directory is included in some `cfg_dir` directive in your `nagios.cfg` file. For example...

```
cfg_dir=/etc/nagios/conf.d
```

Check your configuration in order to ensure that all is ready and without errors...

```
sudo nagios -v /etc/nagios/nagios.cfg
```

And restart your Nagios service...

```
sudo service nagios restart
```
