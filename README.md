# arXiv AI Papers

検索・推薦・マッチング系のAI論文サマリー

## Setup

1. GitHubでリポジトリ作成 (`arxiv-papers`)
2. Push:
   ```bash
   git remote add origin git@github.com:YOUR_USERNAME/arxiv-papers.git
   git branch -M main
   git push -u origin main
   ```
3. Settings → Pages → Source: `main` branch, `/ (root)`
4. 数分後に `https://YOUR_USERNAME.github.io/arxiv-papers/` で公開

## 更新方法

`index.md` を編集してpushするだけ。

## ローカルプレビュー

```bash
bundle install
bundle exec jekyll serve
# http://localhost:4000/arxiv-papers/
```

## 構造

```
├── _config.yml    # Jekyll設定
├── index.md       # メインページ
└── README.md      # このファイル
```
