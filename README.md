## Install Backstage dependencies
```
1. curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
2. mvn install 16
3. mvn use 16
4. npm i @backstage/create-app
5. npx @backstage/create-app
```


## Deploy to K8s
```
1. kubectl -f postgres/
2. kubectl -f app/
```