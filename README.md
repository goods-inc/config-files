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
