# メモアプリ
このメモアプリは、ユーザーがメモを作成・編集・削除できるシンプルなウェブアプリケーションです。

## インストール方法
以下の手順に従って、アプリをローカル環境でセットアップしてください。

1. このリポジトリをクローンします
```sh
$ git clone https://github.com/e-yanagita-gs/memo_app.git
```
2. 必要なGemをインストールします
```sh
$ cd memo_app
$ bundle install
```
3. アプリケーションを起動します
```sh
$ bundle exec ruby memoapp.rb
```

## 使用方法
アプリの基本的な使い方を説明します。
1. メモアプリにアクセスする:
   - アプリケーションを起動した状態で、ブラウザのアドレスバーに `http://localhost:4567` と入力し、Enterキーを押します。これでメモアプリのホームページが表示されます。

2. メモを追加する:
   - 「追加」ボタンをクリックし、タイトルと内容を入力して「保存」をクリックします。

3. メモを編集する:
   - 編集したいメモをクリックし、「変更」ボタンをクリックします。タイトルと内容を変更して「変更」をクリックします。

4. メモを削除する:
   - 削除したいメモをクリックし、「削除」ボタンをクリックします。
