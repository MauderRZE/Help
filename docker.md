# docker commands
https://docs.docker.com/engine/reference/commandline/docker/


commadr  | Descryptions
------------- | -------------
docker build . -t name of project  | Content Cell
Content Cell  | Content Cell 
``` docker build . -t name of project ```
``` docker run -d -p 8080:80 -v ${pwd}:/var/www/html imagine (for example - php:8.2.6-apache)   ``` - запуск apache
``` docker run --rm -v ${pwd}:/path(its path/to/directory for example - ${pwd}:/app)   php: name of image from docker hum (for example - php:8.2.6-apache) php (puth to directory to file)```
exaple run file docker in terminal ps ``docker run --rm -v ${pwd}:/app php:8.2.6-apache php /app/index.php``
``` ${pwd} - в power shell current directory```


# docker-compose

``` 
docker-compose up
docker-compose down
docker-compose ls
docker-compose ps
```

