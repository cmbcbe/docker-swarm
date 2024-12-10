# GUACAMOLE
This swarm only deploy on a specific swarm node and depend of  external attached network npm (these managed by docker nginx proxy manager)
mkdir -p /data/docker/guacamole/mariadb/data
mkdir -p /data/docker/guacamole/guacd/{data,conf}
mkdir -p /data/docker/guacamole/guacamole/{guac-home,conf}
cd /data/docker/guacamole
docker stack deploy -c docker-compose.yml guacamole
