# GITEA
This swarm only deploy on a specific swarm node and depend of  external attached network npm (these managed by docker nginx proxy manager)
mkdir -p /data/docker/gitea
cd /data/docker/gitea
docker stack deploy -c docker-compose.yml gitea
