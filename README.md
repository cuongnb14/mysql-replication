# mysql-replication

## Master-Master

Config Replication with master-master architecture.

This config for only new database (name `demo`) (just initialized) without config MASTER_LOG_FILE and MASTER_LOG_POS (not need).

Start:

`cd master-master && make up`

Then 2 database `demo` of 2 mysql container will be replicated. 
