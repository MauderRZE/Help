### Create new branch from different branch
```
git checkout -b myFeature dev
```
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
> [!IMPORTANT]

