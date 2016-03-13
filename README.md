# 「npm link」 or「dependencies」 

## npm linkを使ってエイリアスを作る

1\. mylibへ移動しエイリアス用のパスを保存する

```
cd mylib
npm link
```

2\. 保存されたエイリアスを`app-use-npm-link/node_modules`内に配置する

```
cd ../app-use-npm-link
npm link mylib
```

## dependenciesを使ってライブラリをインストールする

```
cd app-use-dependencies
npm install
```


## 実行

```
cd app-use-npm-link
node index
```

```
cd app-use-dependencies
node index
```