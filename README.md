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
#delete in linux
How to delete a folder with contents
```
rm -r test
```
How to delete an empty folder
The ```rmdir``` command is specifically used to delete empty directories
```
rmdir test1 test2 test3
```



