---
layout: paper
title: "CharacterFlywheel: Scaling Iterative Improvement of Engaging and Steerable LLMs in Production"
date: 2026-03-03
arxiv_id: "2603.01973"
arxiv_url: "https://arxiv.org/abs/2603.01973"
pdf_url: "https://arxiv.org/pdf/2603.01973"
authors: ["Yixin Nie", "Lin Guan", "Zhongyao Ma", "Anchit Gupta", "Yipin Zhou", "Xiao Li", "Zhengping Zhou", "Raymond Zeng", "Gelin Zhou", "Shigan Chu", "Ajay Thampi"]
categories: ["cs.CL", "cs.AI", "cs.SI"]
venue: "Production (Meta)"
---

## 一言まとめ

**Meta本番デプロイ**: Instagram/WhatsApp/Messengerのソーシャルチャット向けLLM改善フライホイール。LLaMA 3.1から15世代の反復改善で**エンゲージメント最大+19.4%**、指示追従**59.2%→84.8%**に向上。

## 概要

**CharacterFlywheel**は、本番ソーシャルチャットアプリケーション（Instagram、WhatsApp、Messenger）向けLLMを反復的に改善するフライホイールプロセス。LLaMA 3.1を起点に、内部・外部の実ユーザートラフィックからのデータを使用して15世代にわたりモデルを精錬。

### 主要結果（2024年7月〜2025年4月）

- **エンゲージメント**: 8モデル中7モデルでベースライン比正のリフト
  - エンゲージメント幅: 最大**+8.8%**
  - エンゲージメント深度: 最大**+19.4%**
- **ステアラビリティ**: 
  - 指示追従: **59.2% → 84.8%**
  - 指示違反: **26.6% → 5.8%**

### CharacterFlywheelプロセス

1. **データキュレーション**: 実ユーザートラフィックからの高品質データ収集
2. **報酬モデリング**: エンゲージメント指標の推定と補間
3. **SFT**: 教師ありファインチューニング
4. **RL**: 強化学習による最適化
5. **オフライン/オンライン評価**: 各最適化ステップでの信頼性確保

### 過学習防止と大規模本番運用

- 過学習防止手法
- 数百万ユーザー規模での本番ダイナミクス対応

## 所感

LLMの本番運用における反復改善の実践知が詰まったレポート。特にエンゲージメント最適化とステアラビリティ（指示追従性）の両立は、チャットボット開発の要。Meta規模での実証データは非常に貴重。
