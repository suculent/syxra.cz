# syxra.cz

## Deployment

  docker build -t suculent/syxracz .
  docker stack deploy -c ./stack.yml syxra-cz
