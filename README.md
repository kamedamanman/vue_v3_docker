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

## 4.サンプルを動かしてみよう

[Vue.js](https://vuejs.org/examples/#cells)

[Vue.js Examples](https://vuejsexamples.com/)

[Vue.js Projects and Examples Showcase](https://vuejsprojects.com/)

[vuejsfeed](https://vuejsfeed.com/)

[made with vue.js（vueで作られているサイト一覧）](https://madewithvuejs.com/)

### 参考

[Docker日本語ドキュメント](http://docs.docker.jp/)

[Docker compose](http://docs.docker.jp/compose/toc.html)

[Vue 3 日本語ドキュメント](https://v3.ja.vuejs.org/guide/introduction.html)
