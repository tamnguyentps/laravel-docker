# Simple docker-compose for Laravel development

## Installation

1. Clone laravel-docker repository inside your laravel project
2. Change configurations depend on your project
3. Change your `.env` file
```bash
  DB_HOST=db #MYSQL docker
  DB_PORT=3306
  DB_DATABASE=laravel
  DB_USERNAME=root
  DB_PASSWORD=root
```
4. Start docker compose
```sh
docker-compose up -d
```
5. Enjoy your project at ```http://localhost:8580```
