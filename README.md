# desafioDocker02
Desafio 2 do curso de docker

comando para rodar o container:
docker run -d \
  --name curso_mysql \
  -e MYSQL_DATABASE=docker_db \
  -e MYSQL_USER=docker_usr \
  -e MYSQL_PASSWORD=docker_pwd \
  -e MYSQL_ROOT_PASSWORD=root_pwd \
  -p 3306:3306 \
  mysql:8.0



**************
Com docker compose:

use o arquivo compose.yml 

Rode com o comando:
docker compose up -d

