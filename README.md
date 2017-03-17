# dotstamp_deploy_ansible

<img src="https://raw.githubusercontent.com/wheatandcat/dotstamp_client/master/dist/images/common/about.png" data-canonical-src="https://raw.githubusercontent.com/wheatandcat/dotstamp_client/master/dist/images/common/about.png" width="200" />

## 概要
.stampのデプロイ環境構築　  
webサービス：[.stamp](http://dotstamp.com/)

## デプロイ
ブルーグリーンデプロイメントを採用しています

## projectリポジトリ一覧
* サーバーサイド:[dotstamp_server](https://github.com/wheatandcat/dotstamp_server)
* クライアントサイド：[dotstamp_client](https://github.com/wheatandcat/dotstamp_client)
* 環境構築：[dotstamp_ansible](https://github.com/wheatandcat/dotstamp_ansible)
* デプロイスクリプト：[dotstamp_deploy_script](https://github.com/wheatandcat/dotstamp_deploy_script)
* デプロイ環境構築：[dotstamp_deploy_ansible](https://github.com/wheatandcat/dotstamp_deploy_ansible)

## 必要なもの
* Ansible

## デプロイコマンド
※プライベートリポジトリを含んでいるので、そのままでは実行できないのでご注意下さい  
※コマンドはデプロイ環境実行

rootユーザでデプロイ実行
```
sh deploy.sh
```
## ライセンス
BSDライセンス
