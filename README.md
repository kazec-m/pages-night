# ブラウザだけでWebサイトを公開してみよう！

GitHub Pages Lightning Talk（LT）

## 1. 今日のゴール

ローカル環境を用意せず、GitHubのブラウザ画面だけでWebサイトを公開する。

## 2. GitHub Pagesとは？

GitHubのリポジトリにあるHTML、CSS、JavaScriptなどを静的Webサイトとして公開できるサービスです。

## 3. 実際にやってみよう

1. GitHubで公開用のリポジトリを作成する（今回はPublic）。
2. `Add file` → `Create new file` から `index.html` を作成する。
3. 「おつかれさま」と入力し、`Commit changes` で保存する。
4. `Settings` → `Pages` を開く。
5. `Source` を `Deploy from a branch` に設定し、`main` と `/ (root)` を選んで保存する。
6. デプロイが完了したら、公開URLにアクセスする。

## 4. HTMLを書いてみよう

最初は文字だけでもブラウザに表示されます。次はHTMLの基本構造を使って `about.html` を作ってみましょう。

```html
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GitHub Pages LT</title>
</head>
<body>
  <h1>おつかれさま</h1>
</body>
</html>
```

## 5. ちょっとアレンジ

- `Add file` → `Upload files` から画像をアップロードする。
- `img` タグで画像を表示する。
- `a` タグでGitHubへのリンクを設置する。
- 画像のファイル名とHTML内のパスを一致させる（大文字・小文字にも注意）。

## 6. デモサイト

| ページ | ソースコード |
| --- | --- |
| [文字だけのページ](https://kazec-m.github.io/pages-night/) | [index.html](./index.html) |
| [HTMLで構成したページ](https://kazec-m.github.io/pages-night/about.html) | [about.html](./about.html) |

## 7. 参考資料

### GitHub公式

- [新しいファイルの作成](https://docs.github.com/ja/repositories/working-with-files/managing-files/creating-new-files)
- [GitHub Pagesサイトの公開元を設定する](https://docs.github.com/ja/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
- [GitHub公式ロゴ素材](https://github.com/logos)

### 参考記事

- [Zenn：GitHub Pagesで静的サイトを公開するまで](https://zenn.dev/nosho/articles/83179b0df62641)
- [Qiita：HTMLとCSSの基礎](https://qiita.com/kage1020/items/b5c833cb928934d0d1e6)
- [Qiita：GitHub PagesでWebサイトを立ち上げる](https://qiita.com/shirokuma89dev/items/05aa2a5942363ee43fad)
- [The smallest possible valid (X)HTML documents](https://mathiasbynens.be/notes/minimal-html)

---

このリポジトリはGitHub PagesのLT用サンプルです。
