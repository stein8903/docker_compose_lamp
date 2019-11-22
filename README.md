# PHP7が使えるdocker
## 場所
下記のhtmlのディレクトリーの中にphpを入れると動く
./html/

## url
### htmlの中身
http://localhost/
### phpMyAdmin
http://localhost:8080/

## 使い方
cloneしてきたdocker_compose_lampに移動して下記の手順でdockerを立ち上げる
### サービスをビルド
```
docker-compose build
```
### サービスのコンテナを起動
```
docker-compose up -d
```
### web接続
```
docker-compose exec web bash
```