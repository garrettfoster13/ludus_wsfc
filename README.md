# Windows Server Failover Collection for Ludus

This collection builds an Active Directory (AD) environment with a three node Windows Server Failover Cluster (WSFC) deployment. 


# Installation
```
ludus ansible collection add garrettfoster13.ludus_wsfc
ludus range config set -f <config>.yml
ludus range deploy
```