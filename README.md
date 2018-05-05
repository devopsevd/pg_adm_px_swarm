# postgres_with_adminer using portworx

# To deploy the stach
docker stack deploy --compose-file docker-compose.yml pgsql

# To bring the stack down
docker stack rm pgsql

