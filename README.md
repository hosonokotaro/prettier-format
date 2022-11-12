# prettier-format

Prettier の setting 共通化ライブラリです。個人用に作成しました。設定は[こちら](https://github.com/hosonokotaro/prettier-format/blob/master/index.json)

## Install

prettier の install されている環境が前提です。

```
npm i -D @hosonokotaro/prettier-format
```

## package.json

下記の設定を追加します。

```
 "prettier": "@hosonokotaro/prettier-format"
```

一例ですが、scripts に下記の設定をします。

```
"format-code": "prettier --write \"./src/**/**.{ts,tsx}\""
```

上記が完了すれば `npm run format-code` で prettier による format が実行できます。
