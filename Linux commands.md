# create file in linux comands
```

touch index.php
cat > index.php
echo > index.php

Создание файла с использованием Heredoc
cat << EOF > index.php

Копирование больших файлов
dd if=(path from) of=(path where) bs=1 count=0 seek=1G
example :
dd if=/dev/zero of=1G.test bs=1 count=0 seek=1G

create file 1g with space 1gb
fallocate -l 1G 1G.test
```
# delete in linux

How to delete a folder with contents
```
rm -r test
```
How to delete an empty folder
The ```rmdir``` command is specifically used to delete empty directories
```
rmdir test1 test2 test3
```
# Перейменування файлів або переміщення в linux
```
mv file file1
cp file file
```
# permitions

>chek permit to directory "test"
```ls  -ld <имя файла>```

>change permiton
```$ chmod g+rwx -R <имя файла>```

> add read and write permition
```chmod g+rw <имя файла>```

> remowe read and write permition
```chmod g-rw <имя файла>``` 
# change owner of file
```
chown -R root(it user):root(it groupe) ./dir3( path directory or file)
```
# Версия линукс
```lsb_release -a```
# users and groups

>перевітити до яких груп відноситься користувач
```groups <имя пользователя> ```

>add new user
```adduser <имя пользователя>```

>add to groupe 
```usermod -aG sudo sanyok```

>Список всіх користвачів Linux 
```awk -F':' '{ print $1}' /etc/passwd```



# Log file in linux commands
```~/.bash_history```

# networks 

>вивод информации по сетевой карте
```sudo ethtool enp1s0```

# Брандмауер 

> check status 
``` ufw status```

> check lists
```ufw app list```

> add servise
```ufw allow OpenSSH ```

> enable firewall
```ufw enable```

# apache2

>```systemctl status apache2
>```sudo systemctl stop apache2
>sudo systemctl start apache2
>sudo systemctl restart apache2```

>перезагрузка без розрива соединения
>```sudo systemctl reload apache2```

>disable or enable apach service when system start
>```sudo systemctl disable apache2```

>Создание виртуального хоста
```sudo nano /etc/apache2/sites-available/your_domain.conf```

>Активируем файл виртуального хоста ```a2ensite```:
```sudo a2ensite your_domain.conf```

>Отключить сайт по умолчанию 
```sudo a2dissite 000-default.conf```

# host

> ```hostname, hostname -i, hostname -I```
# Зовнішній IP

>```curl -4 icanhazip.com```



