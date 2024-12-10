# GLPI
This swarm only deploy on a specific swarm node and depend of  external attached network npm (these managed by docker nginx proxy manager)
mkdir -p /data/docker/glpi/html
mkdir -p /data/docker/glpi/mariadb
cd /data/docker/glpi
docker stack deploy -c docker-compose.yml glpi
