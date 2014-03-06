# 開発memo

Webサービス開発中に必要になったコマンド

## ruby on rails

### コントローラ作成

```
rails g controller index index
```

最後のindexはmethodを作ってくれるオプション

### コントローラ削除

```
rails destroy controller index index
```

### 後でテスト追加(rspec)

```
rails g integration_test テスト名
```

### ルーティング内容確認

```
rake routes
```

### 動的(ダイナミック)ファインダ

```
Model.find_all_by_xxx
Model.fine_by_xxx
```

## Heroku

### migration

```
heroku run rake db:migrate
```

### log

```
heroku logs
```

## ruby

### rbenv

[Rails開発環境の構築(rbenvでRuby導入からBundler, Rails導入まで)](http://qiita.com/emadurandal/items/a60886152a4c99ce1017)

