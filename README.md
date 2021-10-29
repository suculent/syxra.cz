# syxra.cz

This is an example of how I deploy static sites on my cloud these days. The cloud consists of multiple servers running Docker Swarm with Traefik load-balancer and Swarmpit as a deployment manager.

## [Re]deployment

  git pull
  docker build -t suculent/syxracz .
  docker stack deploy -c ./stack.yml syxra-cz

	