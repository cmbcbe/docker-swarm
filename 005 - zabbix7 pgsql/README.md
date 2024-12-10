# ZABBIX7 with PostgreSQL
This swarm only deploy on a specific swarm node and depend of  external attached network npm (these managed by docker nginx proxy manager)
mkdir -p /data/docker/zabbix/postgresql
mkdir -p /data/docker/zabbix/db_dumps
mkdir -p /data/docker/zabbix/server/alertscripts
cd /data/docker/zabbix
docker stack deploy -c docker-compose.yml zabbix
