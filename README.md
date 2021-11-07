# docker-compose-files
docker compose files for sample apps

# kafka

docker compose for run containers zookeper, broker and kafka dev tools. 

documentation:
- command to keep container alive
  command: ["tail", "-f", "/dev/null"]

- properties
  network_mode: host => share the same network space with the Host.

commands:

- execute docker compose
  docker-compose up
- enter the container
  docker exec -ti <container-name> bash

references:

https://ichi.pro/es/configuracion-de-su-entorno-local-basado-en-eventos-con-kafka-docker-121516151393685

https://stackoverflow.com/questions/43843079/using-tail-f-dev-null-to-keep-container-up-fails-unexpectedly
