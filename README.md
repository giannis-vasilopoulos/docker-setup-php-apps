# docker-setup-php-apps
Docker Development Setup  For PHP Apps

Run in root folder,

docker-compose build && docker-compose up -d


Login to the container,

docker exec -it server /bin/bash -c "TERM=$TERM exec bash"

Thanks [Socialnerds](https://github.com/SocialNerds/Docker-Laravel-episode-50) for this tutorial

Next Steps 
1) Update the DockerFile to PHP 7.2
