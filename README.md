# Solr Cloud
solr_version: 8.11.2
# Zookeeper
zk_version: 3.6.2

Requirements
------------
- Minimal Version of the ansible for installation: 2.7
  - **Java 8** [![Build Status](https://travis-ci.org/lean-delivery/ansible-role-java.svg?branch=master)](https://travis-ci.org/lean-delivery/ansible-role-java)
  - **Zookeper** cluster installed [![Build Status](https://travis-ci.org/lean-delivery/ansible-role-zookeeper.svg?branch=master)](https://travis-ci.org/lean-delivery/ansible-role-zookeeper)
  - ** Solr** standalone servers installed [![Build Status](https://travis-ci.org/lean-delivery/ansible-role-solr-standalone.svg?branch=master)](https://travis-ci.org/lean-delivery/ansible-role-solr-standalone)
  - **Supported OS**:
    - CentOS
      - 7
    - Ubuntu
    - Debian

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
