# ghcp-school-intro

神山まるごと高専の紹介ページです。GitHub Pages で公開することを前提に、`docs/` 配下に静的ファイルを配置しています。

## コンセプト

- ハッカー育成イメージを強めに出したビジュアル
- 日本語 + 英語併記
- 学校の特徴、カリキュラム、CTF演習、学生プロジェクト、アクセス、入学情報を1ページで案内

## ディレクトリ構成

```text
docs/
	index.html
	assets/
		styles.css
		main.js
```

## ローカル確認

静的サイトのため、`docs/index.html` をブラウザで開くだけで確認できます。

## GitHub Pages 公開手順（main /docs）

1. GitHub のリポジトリ画面を開く
2. `Settings` -> `Pages` を開く
3. `Build and deployment` の `Source` を `Deploy from a branch` に設定
4. `Branch` を `main`、フォルダを `/docs` に設定して保存
5. 数分待って公開URLにアクセス

## 更新手順

1. `docs/` 配下を編集
2. 変更を `main` に push
3. GitHub Pages の再デプロイ完了後、公開URLで確認