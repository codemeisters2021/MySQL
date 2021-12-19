To run we need:
1. cp .env.local .env
2. If we want phpmyadmin then "cp docker-compose.override.phpmyadmin.yml docker-compose.override.yml"
3. If we want adminer then "cp docker-compose.override.adminer.yml docker-compose.override.yml"
4. Run "docker-compose up -d"

After complete 