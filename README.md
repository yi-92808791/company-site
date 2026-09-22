# スカイライン・テクノロジーズ 企業サイト

「動くプロダクト」を、いちばん早く現実にするチームであるスカイライン・テクノロジーズのコーポレートサイトです。
企画から開発・運用までを一気通貫で支援する6つの専門領域、開発の進め方、導入実績、メンバー紹介などを掲載しています。

## 構成

- `index.html` — サイト本体（単一HTMLファイル、ライト/ダークテーマ対応）

## 動作環境

外部ライブラリのビルドは不要です。モダンブラウザ（Google Chrome、Safari、Firefox など）があれば表示できます。

## ブラウザで開く手順

1. 本リポジトリをローカルに取得します。

   ```bash
   git clone <このリポジトリのURL>
   cd company-site
   ```

2. `index.html` をブラウザで開きます。

   - Finder等から `index.html` をダブルクリックする
   - もしくはターミナルから以下を実行する

     ```bash
     open index.html
     ```

     ※ Windows の場合は `start index.html`、Linux の場合は `xdg-open index.html` を使用してください。

3. ローカルサーバー経由で確認したい場合は、以下のいずれかを実行してブラウザで `http://localhost:8000` を開きます。

   ```bash
   python3 -m http.server 8000
   ```
