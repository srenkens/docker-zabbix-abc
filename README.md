# zabbix-abc [![](https://badge.imagelayers.io/srenkens/zabbix-abc:latest.svg)](https://imagelayers.io/?images=srenkens/zabbix-abc:latest 'Get your own badge on imagelayers.io')

A custom version of Berngp's excellent Docker Zabbix container. These are the most important changes:

1. It replaces the default installation of curl for a different version that uses OpenSSL instead of NSS because we where having issues monitoring TLS1.1 and TLS1.2 enpoints with strong encryption ciphers. 

1. We've installed the php pear mail package for our custom alertsscripts

