# wp-themedevelop

Wordpressのテーマ開発環境をDockerを用いて用意する。

このフォルダに異動し、以下のコマンドを実行。
```terminal
$ docker-compose up -d
```

## メモ

1.  デバックモードにする。

`/var/www/html/wp-config.php` の `WP_DEBUG` を true にする。
```php
define( 'WP_DEBUG', true );
```
