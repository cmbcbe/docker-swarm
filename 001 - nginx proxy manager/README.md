# nginx proxy manager
This swarm only deploy on a specific swarm node
mkdir -p /data/docker/npm/data
mkdir -p /data/docker/npm/letsencrypt
cd /data/docker/npm/data
docker stack deploy -c docker-compose.yml npm
