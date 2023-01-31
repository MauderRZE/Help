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
# change permiton
$ chmod g+rwx -R <имя файла>

> add read and write permition
```chmod g+rw ```

> remowe read and write permition
```chmod g-rw ``` 
# change owner of file
```
chown -R root(it user):root(it groupe) ./dir3( path directory or file)
```
# Версия линукс
```lsb_release -a```
# users and groups

>перевітити до яких груп відноситься користувач root
```groups root ```

>add new user
```adduser Sanyok```

>add to groupe 
```usermod -aG sudo sanyok```

>Список всіх користвачів Linux 
```awk -F':' '{ print $1}' /etc/passwd```



# Log file in linux commands
```~/.bash_history```

# networks 

>вивод информации по сетевой карте
```sudo ethtool enp1s0```




