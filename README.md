# 合同会社BROTHERS ツールページ

このリポジトリは合同会社BROTHERSが運用するツール系ページ群を GitHub Pages で管理するためのものです。
ビルド不要な静的 HTML をそのまま公開しており、WHOLE SITE の公開 URL は [https://tools.ikedabrothers.jp](https://tools.ikedabrothers.jp) です。

## サイト構成

### 公開

- `CNAME`: `tools.ikedabrothers.jp` でのホスティングに使うエントリ。
- `index.html`: トップランディング。ツールや関連情報を並べてブランド導線を担うメインコンテンツ。
- `x-auto-follow/`: X の自動フォローツールに関する説明ページ。

### 非公開

- `_config.yml`: GitHub Pages（Jekyll）の設定。
- `README.md`: 本ドキュメント。開発者向けリポジトリ説明。
- `AGENT.md`: AI向け運用ルールと連絡方針のメモ。

追加で公開したくないファイルが出たら `_config.yml` の `exclude` に追記してください。

## 運用ガイド

- 新しいツールを追加するときは `index.html` のカードを増やし、必要なポリシー／プライバシーリンクも整備してください。
- 連絡手段はメール／Googleフォーム優先。電話番号は原則非公開で、フォーム経由のやり取りを継続します。
