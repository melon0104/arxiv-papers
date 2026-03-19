---
layout: default
title: "GLIDE: Deploying Semantic ID-based Generative Retrieval for Large-Scale Podcast Discovery at Spotify"
---

# GLIDE: Deploying Semantic ID-based Generative Retrieval for Large-Scale Podcast Discovery at Spotify

[arXiv:2603.17540](https://arxiv.org/abs/2603.17540) | cs.IR

## 著者
Edoardo D'Amico, Marco De Nadai, Praveen Chandar, Divita Vohra, Shawn Lin, Max Lefarov, Paul Gigioli, Gustavo Penha, Ilya Kopysitsky, Ivo Joel Senese, Darren Mei, Francesco Fabbri, Oguz Semerci, Yu Zhao, Vincent Tang, Brian St. Thomas, Alexandra Ranieri, Matthew N.K. Smith, Aaron Bernkopf, Bryan Leung, Ghazal Fazelnia, Mark VanMiddlesworth, Timothy Christopher Heath, Petter Pehrson Skiden, Alice Y. Wang, Doug J. Cole, Andreas Damianou, Maya Hristakeva, Reid Wilbur, Tarun Chillara, Vladan Radosavljevic, Pooja Chitkara, Sainath Adapa, Juan Elenter, Bernd Huber, Jacqueline Wood, Saaketh Vedantam, Jan Stypka, Sandeep Ghael, Martin D. Gould, David Murgatroyd, Yves Raimond, Mounia Lalmas, Paul N. Bennett (Spotify)

## 一言まとめ
**Spotifyが本番環境にデプロイ**したSemantic ID生成型推薦システム。数百万ユーザー規模のA/Bテストで非習慣的ポッドキャスト視聴**+5.4%**、新番組発見**+14.3%**向上。

## 概要
ポッドキャスト視聴は定番番組への依存と進化するユーザー意図が共存する。GLIDEは推薦を「Semantic IDを用いた指示従属タスク」として定式化し、大規模カタログ上でグラウンデッド生成を実現。最近の視聴履歴と軽量コンテキストをコンディショニングし、長期ユーザー埋め込みをソフトプロンプトとして注入することで、推論制約下でも安定した嗜好を捕捉。

## 注目ポイント
- **実運用実績**: Spotifyホーム画面で数百万ユーザー規模のA/Bテスト実施
- **定量的成果**: 非習慣的ストリーミング+5.4%、新番組発見+14.3%
- **Semantic ID**: カタログ上の生成をグラウンディング、幻覚を防止
- **厳格な制約対応**: 本番のコスト・レイテンシ要件を満たす設計

## 技術的詳細
- 推薦を指示従属タスクとして定式化
- 長期ユーザー埋め込みをソフトプロンプトとして注入
- オフライン検索指標、人間評価、LLMベース評価で検証
- 本番のレイテンシ・コスト制約下で動作

## 関連リンク
- [arXiv](https://arxiv.org/abs/2603.17540)
- [PDF](https://arxiv.org/pdf/2603.17540)
