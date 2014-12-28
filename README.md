jdg-disaster-recovery-primary
=============================

These are a working example of configuration files needed to setup JBoss Data Grid for a disaster recovery between datacenters.

Sample JBoss Data Grid code is not included. However, the files to setup disaster recovery recovery between datacenters are all included:
- Cache configuration
- JGroups Global (jgroups config within the local cluster)
- JGroups Relay (jgroups config between datacenters)
- Relay file

In any disaster recovery scenario it is necessary to setup a local cluster and remote cluster for backup. The local cluster configuration files are considered the primary cluster and are located in src/main/resources/primary. The backup cluster files are located in src/main/resources/backup
