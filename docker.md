# docker commands
https://docs.docker.com/engine/reference/commandline/docker/


commadr  | Descryptions | arguments desription
------------- | ------------- | -------------
docker build . -t name of project  | build project | `.` docker build повідомляє Docker, що він повинен шукати Dockerfile в поточному каталозі
docker run -d -p 8080:80 -v ${pwd}:/var/www/html php:8.2.6-apache  | запуск apache
docker run --rm -v ${pwd}:/app php: php:8.2.6-apache php /app/index.php| вивід файла в консоль
${pwd} | в power shell current directory


# docker-compose

``` 
docker-compose up
docker-compose down
docker-compose ls
docker-compose ps
```


    
