# README

# DMM WEBCAMPコンテンツ【課題：Bookersを作成しよう】

DMM WEBCAMPの学習コンテンツ課題：Bookersを作成しようです。

## 使い方

必須要件
ruby 3.1.2p20
Rails 6.1.7.10
データベース: SQLite3

1.リポジトリのクローン
git clone https://github.com/y-sakurai-code/bookers.git
cd bookers

2.Gemパッケージのインストール
bundle install

3.データベースのセットアップ
rails db:create
rails db:migrate

4.webサーバーの起動
rails s

※ブラウザで http://localhost:3000 にアクセスしてください。