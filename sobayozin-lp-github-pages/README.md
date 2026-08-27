# SobaYozin LP

SobaYozin 限定βのランディングページです。

## GitHub Pages で公開する

1. このフォルダの内容を GitHub リポジトリの `main` ブランチへ配置します。
2. GitHub の `Settings` → `Pages` を開きます。
3. `Build and deployment` の `Source` を **GitHub Actions** にします。
4. `main` へ push すると `.github/workflows/pages.yml` が自動で公開します。

公開URLは通常 `https://<GitHubユーザー名>.github.io/<リポジトリ名>/` です。

## 構成

- `index.html` : LP本体
- `assets/` : SobaYozin画面画像
- `.github/workflows/pages.yml` : GitHub Pages公開用
- `.nojekyll` : 静的ファイルをそのまま配信するための設定

## 注意

現在のCTAは個別DMでのβ案内を前提にしています。公開後、問い合わせフォームやDM URLが決まったら `index.html` の連絡先部分を更新してください。
