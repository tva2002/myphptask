# Docker test task

### Introduction
This is my docker project created for task php  projects.

Includes php7.4-fpm + nginx/alpine + mariadb + swaggerapi/swagger-ui 


### HOW TO START WITH THIS PROJECT

I will recomend to pull this repository localy and then copy docker files and paths(path docker, files docker-*) to your  project.
I have committed to this repo only one file to `app/` path, only to show that it's working fine.

### RUN project


#### Linux

cp env.dist .env

```docker-compose up```

To run containers in background use option -d

```docker-compose up -d```

To build/rebuild containers

```docker-compose build```

