# mysql-replication

## Master-Master

Config Replication for master-master.

This config for only new database (demo) (just initialized) without config MASTER_LOG_FILE and MASTER_LOG_POS (not need).

Start:

`cd master-master && make up`

Then 2 database demo of 2 mysql container will be replicated. 