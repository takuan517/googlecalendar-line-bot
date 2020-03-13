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
<br><img src="https://user-images.githubusercontent.com/50577904/76593480-c623d600-6539-11ea-8ec2-52d2655f63b4.jpg" width="400px"><br>
・「予定を知りたい」を押すと日付を選択できるようになる
<br><img src="https://user-images.githubusercontent.com/50577904/76593579-14d17000-653a-11ea-9fcd-97b846050458.jpg" width="400px"><br>
・予定が確認できる
<br><img src="https://user-images.githubusercontent.com/50577904/76593625-303c7b00-653a-11ea-9be3-5bfd3fc7ed4c.jpg" width="400px"><br>
・「予定を追加追加したい」を押すと入力形式が送られてくる
<br><img src="https://user-images.githubusercontent.com/50577904/76593704-6417a080-653a-11ea-94eb-e762b8e95fd6.jpg" width="400px"><br>
・入力して追加に成功するとurlが送られてくる
<br><img src="https://user-images.githubusercontent.com/50577904/76593757-84dff600-653a-11ea-9dcc-a515a7c52dc6.jpg" width="400px"><br>
・googleカレンダーで確認すると予定が追加されている
<br><img src="https://user-images.githubusercontent.com/50577904/76593787-96c19900-653a-11ea-8c56-26fa378fa3d4.jpg" width="400px"><br>

