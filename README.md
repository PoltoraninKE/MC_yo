# Запуск с помощью команды 
docker run -d -it -p 25565:25565 -e EULA=TRUE itzg/minecraft-server

# Октрыть папку докер имаджа с помощью 
docker exec -t -i DOCKER_IMAGE_NAME /bin/bash