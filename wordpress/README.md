# WordPress

[ブログから大規模サイトまで作れる CMS | WordPress.org 日本語](https://ja.wordpress.org/)

## セットアップ

1. ファイルの取得する
  - WordPress.org からダウンロードします [ダウンロード | WordPress.org 日本語](https://ja.wordpress.org/download/)
  - .gitignoreをコピーし設置する [github/gitignore](https://github.com/github/gitignore)
    - [gitignore/WordPress.gitignore](https://github.com/github/gitignore/blob/master/WordPress.gitignore)
2. WordPressをインストールする [WordPress のインストール | WordPress.org 日本語](https://ja.wordpress.org/support/article/how-to-install-wordpress/)
  - 新規データベースを作成します
  - `wp-config-sample.php` をコピーし `wp-config.php` を作成します
    - このとき、DBを `localhost` にすると接続エラーが起きます。ローカルのDBを利用する場合、 `127.0.0.1` を利用します
3. サーバを起動する
  - WEBサーバを起動します
    - PHPの場合、 `php -S localhost:8000` などで起動できます

## 開発

## テーマの作成

## 方針

- WordPressでは標準的な構成を尊重します
- 画像およびCSS、JSに関しては、nodejsを利用したビルドを行います

### 資料

- [Theme Development « WordPress Codex](https://codex.wordpress.org/Theme_Development)
- [テーマの作成 - WordPress Codex 日本語版](https://wpdocs.osdn.jp/%E3%83%86%E3%83%BC%E3%83%9E%E3%81%AE%E4%BD%9C%E6%88%90)
