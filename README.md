[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/codeforjapan/github-hands-on)

# GitHub入門講座＆ハンズオン

上記のGitpodのバッジをクリックして開始してください。

スライドは[Marp](https://marp.app/)を利用して作成されています。

Markdownで記述し、PDFやhtmlへコンバートできます。

MarkDownで使用できるMarpitの記法は[こちら](https://marpit.marp.app/markdown)を参考にしてください。


## スライドのコンバート
`cd [ディレクトリ名]` でMarkdownファイルのある場所に行き、以下のコマンドを叩いてください。
### HTMLにする
```
npx marp [スライド名].md
npx marp [スライド名].md -o output.html
```
### PDFにする
```
npx marp [スライド名].md --pdf --allow-local-files
npx marp [スライド名].md -o output.pdf --allow-local-files
```
### PowerPointドキュメント（PPTX）にする
```
npx marp [スライド名].md --pptx --allow-local-files
npx marp [スライド名].md -o output.pptx --allow-local-files
```
### ウォッチモード
```
npx marp [スライド名].md -w
```
※ウォッチモードを終了するときは `Ctrl + c`
### サーバーモード
```
npx marp -s ./[ディレクトリ名]
```
※サーバーモードを終了するときは `Ctrl + c`
