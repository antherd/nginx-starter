# nginx-starter

See the 中文文档 for [Chinese](./README-CN.md) readme.

Docker Compose One-click nginx starter, website hot update supported.

## How to Use

1. Get the code
```sh
git pull git@github.com:antherd/nginx-starter.git
```
2. Start the docker
```sh
cd nginx-starter
docker-compose up -d
```
3. Visit the site by the browser：[your-ip:80](127.0.0.1:80) or [your-ip](127.0.0.1)

![snapshot.png](image/snapshot.png)

## How to update

Just replace the webpage code in **project** folder. (**NO NEED TO RESTART THE DOCKER**).
