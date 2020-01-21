##Run
```shell
hugo server
```

https://ml-studio-app.github.io/website/

## Themes
- https://github.com/radity/raditian-free-hugo-theme, https://raditian-hugo.radity.com

## Initial deploy
```shell script
rm -rf public

# https://gohugo.io/hosting-and-deployment/hosting-on-github/
git submodule add -b master https://github.com/ml-studio-app/ml-studio-app.github.io.git public
./deploy.sh "Your optional commit message"

# Visit https://ml-studio-app.github.io
```