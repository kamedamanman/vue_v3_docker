# vue_v3_docker

Dockerでvue3の開発環境をつくるためのリポジトリ

## 1. Docker install

[公式より](https://matsuand.github.io/docs.docker.jp.onthefly/get-docker/)

## 2. コンテナ起動

```bash
cd vue_v3_docker
mkdir server
docker-compose up -d --build  
docker-compose exec web /bin/sh 
```

webのコンテナから

```bash
vue create first-app（アプリの名前）
```
