# nginx-starter

Docker Compose 一键启动 nginx，支持项目热更新。

稍作修改即可支持域名绑定、HTTPS证书安装。

## 如何使用

1. 拉取代码
```sh
git pull git@github.com:antherd/nginx-starter.git
```
2. 启动 docker
```sh
cd nginx-starter
docker-compose up -d
```
3. 浏览器访问网站：[ip:80](127.0.0.1:80) or [ip](127.0.0.1)

![snapshot.png](image/snapshot.png)

## 如何更新

替换 **project** 文件夹中的网页代码即可（**无需重启docker**）。
