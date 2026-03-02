# SEO Checker（ローカル）

`tools/seo-checker/seo-checker.html` は、HTML文字列を貼り付けて主要なSEO項目をまとめて確認するためのミニツールです。

## チェックできる項目

- title
- meta description
- h1
- canonical
- robots
- OGP（`og:title` / `og:description` / `og:image` / `og:url`）
- viewport
- 画像の alt
- 見出し段差（例: h2 の次に h4 が来る等）
- JSON-LD（`application/ld+json` のJSON妥当性）

## 使い方

1. ブラウザで `tools/seo-checker/seo-checker.html` を開く
2. 対象ページのHTMLソースをテキストエリアへ貼り付ける
3. **チェック実行** を押す
4. 各項目の判定（OK / WARN / NG）を確認する

## 補足

- このツールはローカルで動作し、外部通信は行いません。
- 判定基準（推奨文字数など）は一般的な目安です。運用方針に応じて調整してください。
