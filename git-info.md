### Create new branch from different branch

> [!IMPORTANT]
> git checkout -b myFeature dev

Creates the MyFeature branch off dev. Do your work and then
```
git commit -am "Your message"
```
Now merge your changes to dev without a fast-forward
```
git checkout dev
git merge --no-ff myFeature
```
Now push the changes to the server
```
git push origin dev
git push origin myFeature
```

## delete remote branch 
```
git push origin --delete <branchName>
```

### удалить файл из области индексирования “Staging Area”, но при этом оставить его в области рабочего проекта “Working Directory”
```
git rm --cached <folder> -f
```
### Git log pretty (custom)
```
git log --pretty=format:"%h %ad | %s%d [%an]" --date=short
```
### Откат комітов
```
git revert  - удаляє всі зміни, і потім робе коміт про видалення
git reset --soft удаляє коміти, но зміни залишаються
git reset --hard удаляє і коміти і зміни в файлах
```

### Примусово запушити зміни з локального репозиторія в віддалений
```
git push --force
```
