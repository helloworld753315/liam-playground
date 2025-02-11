# liam-playground
liamを触って遊んでみるためのリポジトリ

## liamでtblsのスキーマを読み込んで出力する

sqliteのデータベーススキーマをschema.jsonに出力しているのでそれをliamに渡してみる。

```sh
npx @liam-hq/cli erd build --format tbls --input schema.json
```
