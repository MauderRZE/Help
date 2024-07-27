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
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

