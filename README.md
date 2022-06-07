# vue_v3_docker

Dockerでvue3の開発環境をつくるためのリポジトリ

## 1. DockerDesktop install

[installはこちら](https://matsuand.github.io/docs.docker.jp.onthefly/get-docker/)

## 2. コンテナ起動

```bash
cd vue_v3_docker
mkdir server
docker-compose up -d --build  
docker-compose exec web /bin/sh 
```

webのコンテナから

```bash
vue create first-app（first-appはアプリの名前）
cd first-app
yarn serve
```

## 3.スタートページの確認

[http://localhost:8080/](http://localhost:8080/)

### 参考

[Docker日本語ドキュメント](http://docs.docker.jp/)

[Docker compose](http://docs.docker.jp/compose/toc.html)

[Vue 3 日本語ドキュメント](https://v3.ja.vuejs.org/guide/introduction.html)
