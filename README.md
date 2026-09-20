# Tennis Loop — 公開手順

このフォルダは、ビルド不要の静的Webアプリです。`index.html` を含むフォルダ全体を静的ホスティングにアップロードすれば公開できます。

## Cloudflare Pages（おすすめ）

1. Cloudflareにサインインし、「Workers & Pages」から「Create application」を選びます。
2. 「Pages」→「Upload assets」を選びます。
3. この `tennis-loop` フォルダ内のファイルすべてをアップロードして公開します。
4. 発行された `https://...pages.dev` のURLをiPhoneのSafariで開きます。
5. Safariの共有ボタンから「ホーム画面に追加」を選びます。

## GitHub Pages

1. 新しいGitHubリポジトリを作成します。
2. このフォルダ内のファイルをリポジトリの最上位にアップロードします。
3. リポジトリのSettings → Pagesで、`main` ブランチのルートを公開元に指定します。
4. 発行されたURLをiPhoneのSafariで開き、「ホーム画面に追加」を選びます。

## 注意

- アプリの練習履歴は、利用中のブラウザ内に保存されます。
- 動画は端末内に恒久保存しません。公開版で動画を保管・AI分析するには、別途ストレージとサーバー側の分析機能が必要です。
