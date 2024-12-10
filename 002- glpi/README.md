# GLPI
This swarm only deploy on a specific swarm node
mkdir -p /data/docker/glpi/html
mkdir -p /data/docker/glpi/mariadb
cd /data/docker/glpi
docker stack deploy -c docker-compose.yml glpi
