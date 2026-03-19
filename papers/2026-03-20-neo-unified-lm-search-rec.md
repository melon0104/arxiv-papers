---
layout: default
title: "NEO: A Unified Language Model for Large Scale Search, Recommendation, and Reasoning"
---

# NEO: A Unified Language Model for Large Scale Search, Recommendation, and Reasoning

[arXiv:2603.17533](https://arxiv.org/abs/2603.17533) | cs.IR

## 著者
Marco De Nadai, Edoardo D'Amico, Max Lefarov, Alexandre Tamborrino, Divita Vohra, Mark VanMiddlesworth, Shawn Lin, Jacqueline Wood, Jan Stypka, Eliza Klyce, Keshi Dai, Timothy Christopher Heath, Martin D. Gould, Yves Raimond, Sandeep Ghael, Tony Jebara, Andreas Damianou, Vladan Radosavljevic, Paul N. Bennett, Mounia Lalmas, Praveen Chandar (Spotify)

## 一言まとめ
検索・推薦・推論を**単一の言語ステアラブル生成モデル**で統合するフレームワーク。1000万アイテム以上のカタログでタスク横断転移を実証。

## 概要
LLMは推薦・検索・推論に適用されつつあるが、大規模異種カタログ上でこれらを同時にサポートする単一エンドツーエンドモデルのデプロイは困難。NEOは事前学習デコーダ専用LLMをツール不要・カタロググラウンデッド生成器へ適応。アイテムをSemantic ID (SID)として表現し、自然言語と型付きアイテム識別子を共有シーケンス内でインターリーブ。

## 注目ポイント
- **検索・推薦・推論の統合**: 単一モデルで複数タスクを処理
- **言語ステアラビリティ**: テキストプロンプトでタスク・出力形式を制御
- **大規模実証**: 1000万アイテム以上、複数メディアタイプで評価
- **タスク横断転移**: 推薦で学習した知識が検索でも有効

## 技術的詳細
- SIDを独立モダリティとして扱い、段階的アライメントと指示チューニングで統合
- 制約付きデコーディングでカタログ妥当なアイテム生成を保証
- タスク特化ベースラインを一貫して上回る性能

## 関連リンク
- [arXiv](https://arxiv.org/abs/2603.17533)
- [PDF](https://arxiv.org/pdf/2603.17533)
