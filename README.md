# minimal-portfolio-v2

## Overview

ミニマルでシンプルなポートフォリオサイトです。Webエンジニアとして学習中の作品を展示するために作成しました。静的HTMLとCSSのみで構成されており、軽量で高速に動作します。

## Tech Stack

- HTML5
- CSS3（ネストされたCSSセレクタを使用）
- GitHub Actions（自動デプロイ）

## Setup

特別なビルドステップやパッケージのインストールは不要です。

```bash
# リポジトリをクローン
git clone https://github.com/yourusername/minimal-portfolio-v2.git
cd minimal-portfolio-v2
```

## Usage

### ローカルでの確認

ブラウザで `index.html` を直接開くだけで動作します。

```bash
# 例: macOSの場合
open index.html

# または任意のブラウザで開く
```

### デプロイ

GitHub Actionsを使用してGitHub Pagesへ自動デプロイされます。

- `main` ブランチにプッシュすると自動的にデプロイが実行されます
- 手動でワークフローを実行することも可能です

## Directory Structure

```
.
├── .github/
│   └── workflows/
│       └── deploy.yml       # GitHub Pages自動デプロイ設定
├── img/                     # 画像ファイル
│   ├── person.png          # プロフィール画像
│   ├── work-1.jpg          # 作品画像1
│   ├── work-2.jpg          # 作品画像2
│   ├── work-3.jpg          # 作品画像3
│   ├── twitter.png         # SNSアイコン
│   └── instagram.png       # SNSアイコン
├── index.html              # メインHTMLファイル
├── style.css               # スタイルシート
├── favicon.ico             # ファビコン
├── apple-touch-icon.png    # Appleデバイス用アイコン
├── android-chrome-*.png    # Androidデバイス用アイコン
├── site.webmanifest        # PWA設定
└── README.md               # このファイル
```

## License

This repository is for personal/private use only.
