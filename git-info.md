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

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.
