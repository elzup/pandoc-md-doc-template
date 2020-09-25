このプロジェクト pandoc を使用しています。
Markdown で書いた講義資料を HTML に出力できます。
例年通り HTML のみで使う場合は `dist/` ディレクトリのファイルをそのまま使用してください。

```
pandoc --template=template src/index.md > dist/index.html
```
