---
layout: paper
title: "MultiHaystack: Benchmarking Multimodal Retrieval and Reasoning over 40K Images, Videos, and Documents"
date: 2026-03-09
categories: [cs.CV]
arxiv_id: "2603.05697"
---

# MultiHaystack: Benchmarking Multimodal Retrieval and Reasoning over 40K Images, Videos, and Documents

## 基本情報
- **arXiv ID**: 2603.05697
- **カテゴリ**: cs.CV (Computer Vision)
- **投稿日**: 2026-03-09

## 著者
Dannong Xu, Zhongyu Yang, Jun Chen, Yingfang Yuan, Ming Hu, Lei Sun, Luc Van Gool, Danda Pani Paudel, Chun-Mei Feng

## 概要
マルチモーダル大規模言語モデル（MLLM）はテキスト、画像、動画理解を個別に評価するベンチマークで強い性能を達成。しかし、これらの設定は重要な実世界要件—**大規模異種マルチモーダルコーパスからの関連エビデンス検索とその後の推論**—を評価しない。

既存ベンチマークは検索を小規模・単一モダリティ候補セットに制限し、検索空間を大幅に単純化してエンドツーエンドの信頼性を過大評価。

**MultiHaystack**を提案：大規模クロスモダル条件下での検索と推論の両方を評価するために設計された初のベンチマーク。

## 技術的詳細
データセット構成：
- **46,000件以上**のマルチモーダル検索候補（ドキュメント、画像、動画）
- **747件**のオープンだが検証可能な質問
- 各質問は検索プール内のユニークな検証済みエビデンスアイテムに根拠付け
- モダリティを跨ぐエビデンス局在化ときめ細かい推論が必要

## 主要結果
発見された重大な限界：
- 対応エビデンス提供時はモデルが競争力を発揮
- フルコーパスからの検索が必要な場合、性能が**急激に低下**
- 最強の検索器**E5-V**でもRecall@1は**40.8%**のみ
- **GPT-5**などのSOTA MLLMも推論精度がエビデンス提供時の80.86%からtop-5検索下で**51.4%**に低下

## 実用的意義
- マルチモーダルRAGシステムの現実的評価
- 検索中心のマルチモーダル研究推進
- 小規模評価で隠された根本的限界の可視化
- 次世代マルチモーダルシステムの方向性提示

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.05697
