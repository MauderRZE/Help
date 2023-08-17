# docker commands
https://docs.docker.com/engine/reference/commandline/docker/


commadr  | Descryptions | arguments desription | example
------------- | ------------- | ------------- | -|
docker build . -t name of project  | build project | `.` docker build повідомляє Docker, що він повинен шукати Dockerfile в поточному каталозі Команда docker build використовує Dockerfile для створення нового образу контейнера | docker build . -t myproject/app
docker run -d -p 8080:80 -v ${pwd}:/var/www/html php:8.2.6-apache  | запуск apache | `-d ` в фоні `-p` порти `-v` монтування  
docker run --rm -v ${pwd}:/app php:8.2.6-apache php /app/index.php | вивід файла в консоль | `--rm` видаляє контейнери, ящо вони є `-v` монтування  
${pwd} | в power shell current directory


# docker-compose

``` 
docker-compose up
docker-compose down
docker-compose ls
docker-compose ps
```
# зайти в саму ос докера
docker exec -it "php_pro_app" /bin/bash



    
