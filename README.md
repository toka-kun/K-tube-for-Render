# K-tube（永久・安定版）

K-tubeは、YouTubeが利用できない環境でも動画を視聴できるように設計された非公式クライアントです。

**デモURL**
https://k-tube-for-public-release.onrender.com

---

## バージョン更新について

このプロジェクトは**永久・安定版**です。

新機能の追加や頻繁なアップデートは、Vercel版で行っています。

### Vercel版

https://github.com/KA1121Studio/k-tube-for-public-release-2

---

## デプロイ方法

ワンクリックで自分の環境へデプロイできます。

### Render

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/KA1121Studio/K-tube-For-public-release)

### Vercel版

https://github.com/KA1121Studio/k-tube-for-public-release-2

---

## 動画取得オプション（任意）

K-tubeは **yt-dlp** に対応しています。

利用する場合は、リポジトリ直下にある `youtube-cookies.txt` に自身のYouTubeクッキーを設定してください。

### ⚠️ 注意 ⚠️

`youtube-cookies.txt` を第三者に公開しないでください。

クッキーが漏洩すると、アカウントが不正利用される可能性があります。

安全のため、本アカウントではなくサブアカウント（捨てアカウント）の利用を推奨します。

---

## 動作環境

* Node.js
* npm

---

## ローカルでの実行方法

### 依存関係のインストール

通常：

```bash
npm install
```

yt-dlpを利用する場合：

```bash
npm install
pip install yt-dlp
```

### サーバーの起動

```bash
npm start
```

---

## お問い合わせ

ご質問や不具合報告などがありましたら、以下までご連絡ください。

https://scratch.mit.edu/users/I-love-Proxy/
