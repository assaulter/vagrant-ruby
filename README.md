vagrant-ruby
============

Rakeで色々遊ぶ環境が欲しかったので、rbenvでrubyを入れるchef-soloのcookbookを作成。

## 作業手順(改善予定)
* 対象サーバーにknife soloを入れる

```
$ knife solo prepare ホスト名
```

* サーバー内でbundlerをrbenvが管理するgemにインストール

```
$ rbenv exec gem install bundler
```