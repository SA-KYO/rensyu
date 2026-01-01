# 麺屋 希楽夢（きらむ）ホームページ

京都府宇治田原町にある麺屋 希楽夢の公式ホームページです。

## 技術スタック

- Next.js 16.1.1
- React 18.3.1
- TypeScript
- Tailwind CSS
- Framer Motion
- GSAP

## 開発環境のセットアップ

```bash
npm install
npm run dev
```

開発サーバーが `http://localhost:3000` で起動します。

## ビルド

```bash
npm run build
```

## Netlifyへのデプロイ方法

1. GitHubに新しいリポジトリを作成

2. このプロジェクトをGitHubにプッシュ
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin <your-github-repo-url>
git push -u origin main
```

3. Netlifyにログイン
   - https://app.netlify.com/ にアクセス

4. "Add new site" > "Import an existing project"を選択

5. GitHubリポジトリを接続

6. ビルド設定は自動的に検出されます
   - Build command: `npm run build`
   - Publish directory: `.next`

7. "Deploy site"をクリック

## 画像のアップロードについて

画像ファイルは `/public/images/` ディレクトリに配置してください。
現在コード内で参照されている画像ファイル：

- 透過ロゴ copy.png
- 特製塩らーめん.jpeg
- チャーシュー丼.jpeg
- 外観.png
- メニュー１.jpg
- メニュー２.jpg
- 塩らーめん.jpeg
- 醤油らーめん.jpg
- 白湯らーめん.jpeg
- toku-sio.jpeg
- 麺.jpeg
- 汁.jpeg
- 肉.jpeg
- 卵.jpeg
- 米.jpeg
- ねぎ.jpeg
- 店内.jpeg
- のれん.jpeg
- 醤油らーめん_copy.jpg
- 白湯らーめん_copy.jpeg
- 特製塩らーめん_copy.jpeg
- チャーシュー丼_copy.jpeg
- 自家製麺.jpeg
- リサイズ後.png

## ライセンス

© 2025 らーめん希楽夢 All Rights Reserved.
