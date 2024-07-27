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
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)
