# インストール方法

```
curl -sSL git.io/goods-jsconfig | sh
```

#共通
npm install -g eslint

.eslintrcを実行するディレクトリに置く。

#sublime3にeslintを導入する方法
以下のパッケージを入れる

SublimeLinter

SublimeLinter-contrib-eslint

ESLint-Formatter

# envについて

```
"env": {
  "browser": true, # デフォルト
  "node": true, # nodeを使う場合
  "es6": true # es6の記法を使う場合
},
```

# installスクリトについて

レポジトリ内のファイルをcurlでダウンロードしている。
既存のファイルを編集した際は特に変更しなくてもいいが、新しくファイルを追加した場合はfilesにファイル名を追加する必要がある。
