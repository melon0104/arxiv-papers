---
layout: default
title: "OneMall: Generative Recommender at Kuaishou"
---

# OneMall: One Model, More Scenarios -- End-to-End Generative Recommender Family at Kuaishou E-Commerce

arXiv:2601.21770
https://arxiv.org/abs/2601.21770

---

## 概要

Kuaishou（快手）のECプラットフォームで運用されている生成的推薦フレームワーク。商品カード/ショート動画/ライブ配信という異なるシナリオを1つのモデルで統一。4億DAUで実運用中。

## 背景・課題

**Kuaishouとは：**
- 中国の大手ショート動画プラットフォーム（TikTokの競合）
- EC機能も統合（ライブコマース等）
- DAU 4億以上

**ECにおける推薦の複雑さ：**

| シナリオ | 特徴 |
|----------|------|
| 商品カード | 静的、詳細情報重視 |
| ショート動画 | 動的、エンタメ性 |
| ライブ配信 | リアルタイム、インタラクション |

**従来の問題：**
- シナリオごとに別モデル→開発・運用コスト大
- シナリオ間の知識共有ができない
- 検索（Retrieval）とランキング（Ranking）が分断

## 提案手法

### 1. E-commerce Semantic Tokenizer

アイテムをトークン列に変換：
- **実世界セマンティクス**：カテゴリ、ブランド、属性
- **ビジネス固有関係**：購入パターン、共起関係
- シナリオを跨いだ統一表現

### 2. Transformer-based Architecture

**Query-Former：**
- 長いユーザー行動シーケンスを圧縮
- メモリ効率的な長期興味モデリング

**Cross-Attention：**
- 複数の行動タイプ（閲覧、クリック、購入）を融合
- シナリオ間の知識転移

**Sparse MoE（Mixture of Experts）：**
- シナリオごとに専門家を動的選択
- スケーラブルな自己回帰生成

### 3. Reinforcement Learning Pipeline

**End-to-End最適化：**
- 従来：Retrieval → Ranking が分断
- 提案：Rankingモデルの出力を報酬として、Retrievalモデルを直接最適化
- 「良いランキング結果を出すRetrievalとは？」を学習

## 実験結果

**オンラインA/Bテスト：**

| シナリオ | 指標 | 改善 |
|----------|------|------|
| 商品カード | GMV | +13.01% |
| ショート動画 | 注文数 | +15.32% |
| ライブ配信 | 注文数 | +2.78% |

**規模：** 4億DAUで本番運用

## 意義・応用

- 生成的推薦の大規模実証
- マルチシナリオ統一の実現可能性
- Retrieval-Ranking統合のRL手法

## 関連研究

- HSTU（Meta）: 生成的推薦
- SASRec / BERT4Rec: 逐次推薦
- GR（Generative Retrieval）: 生成的検索
