To prepare project:
1. cp .env.local .env
2. If we want phpmyadmin then "cp docker-compose.override.phpmyadmin.yml docker-compose.override.yml"
3. If we want adminer then "cp docker-compose.override.adminer.yml docker-compose.override.yml"
4. Run "docker-compose up -d"


To run mysql command:
After complete download we can run "docker-compose ps" and check what is mysql container name. 
Then we can run "docker exec -it containter_name mysql -uroot -proot database"