# Solr Cloud
solr_version: 8.11.2
# Zookeeper
zk_version: 3.6.2

Requirements
Minimal Version of the ansible for installation: 2.7
Java 8 Build Status
Zookeper cluster installed Build Status
** Solr** standalone servers installed Build Status
Supported OS:
CentOS
7
Ubuntu
Debian

Example Inventory
----------------
```ini
 [solr]
 solr.example.com
 solr2.example.com

 [zookeeper]
 zookeeper1
 zookeeper2
 zookeeper3
 ```
