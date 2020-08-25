# HackU YAKITORI.rbのフロントエンド

# 使い方
```
// イメージのビルド
$ docker-compose build

// コンテナの起動
$ docker-compose up -d

// コンテナに入る
$ docker-compose exec app sh

// パッケージのインストール
$ yarn install

// サーバーの起動
$ yarn serve
```
# 各ページについて 
## HOMEページ（/） 
### 現状の機能  
AppBarのみ  
###追加すべき機能  
ログインのボタン（後で修正しておくので、トグルボタンで適当に作っておいて欲しいです）  
### 追加したい機能  
### 懸念事項  

## 自習室を探すページ（/studyrooms） 
### 現状の機能  
一時デザインは完成  
部屋の表示  
ロックモードに応じたボタンの表示と適切なダイアログ表示   
###  追加すべき機能  
### 追加したい機能  
### 懸念事項  
ダイアログ遷移時（ロックモード）に、ダイアログを表示していますがその際に同じものが表示されている確率が高いです。部屋に入る処理のときに問題がないかテストをお願いします。   

## 部屋のページ(/studyroom/:studyroomId)
まだ
