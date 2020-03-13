# スケジュール管理line-bot
## 概要
googleカレンダーの予定を確認したり追加したりできるlinebot
## 開発環境
python 3.7.4  
Flask 1.1.1  
line-bot-sdk 1.8.0
## 使用サービス
* [Heroku](https://www.heroku.com/)
* [LINE Messaging API](https://developers.line.me/ja/services/messaging-api/)
* [Google Cloud Platform](https://console.cloud.google.com/?hl=ja)
## 現在の機能
* googleカレンダーから予定の確認ができる。
* googleカレンダーに予定を入力できる。  
## 動作画面
・適当な文字を送ると「予定を追加追加したい」か「予定を知りたい」のボタンが送られてくる
![S__83247127](https://user-images.githubusercontent.com/50577904/76593480-c623d600-6539-11ea-8ec2-52d2655f63b4.jpg)
・「予定を知りたい」を押すと日付を選択できるようになる
![S__83247128](https://user-images.githubusercontent.com/50577904/76593579-14d17000-653a-11ea-9fcd-97b846050458.jpg)
・予定が確認できる
![S__83247129](https://user-images.githubusercontent.com/50577904/76593625-303c7b00-653a-11ea-9be3-5bfd3fc7ed4c.jpg)
・「予定を追加追加したい」を押すと入力形式が送られてくる
![S__83247131_0](https://user-images.githubusercontent.com/50577904/76593704-6417a080-653a-11ea-94eb-e762b8e95fd6.jpg)
・入力して追加に成功するとurlが送られてくる
![S__83247132](https://user-images.githubusercontent.com/50577904/76593757-84dff600-653a-11ea-9dcc-a515a7c52dc6.jpg)
・googleカレンダーで確認すると予定が追加されている
![S__83247133](https://user-images.githubusercontent.com/50577904/76593787-96c19900-653a-11ea-8c56-26fa378fa3d4.jpg)
