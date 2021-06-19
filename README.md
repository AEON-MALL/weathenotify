# weathernotify
 
wearthrnotifyが何かを簡潔に紹介する
 
# DEMO


# Features
 
指定した地域の今日、翌日の天気、最低温度、最高温度をLineに通知する
 
# Requirement
  
*json  
*sys  
*urllib
 
# Installation
 
Requirementで列挙したライブラリなどのインストール方法を説明する
 
```bash
pip install jeson
pip install sys
pip install urllib
```
 
# Usage
 実行方法を説明する
```bash
git clone https://github.com/weathrnotify/~
cd weathernotify
python weathernotify.py
```
 
# Note
 
プログラムのYOUR_ACCESS_TOKENの部分を,自分で作成したアクセストークンに変更してプログラムを実行すれば実行されますが、プログラム上にアクセストークンを組み込むのはセキュリティ上よくないので環境変数に組み込むことをお勧めします。  
Herokuに必要なテキストファイル等も同梱しているのでこのままHerokuにアプリを作成してデプロイしてもらっても実行できます。
 
