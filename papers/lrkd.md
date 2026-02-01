---
layout: default
title: Latent Reasoning Knowledge Distillation (LRKD)
---

# 🛒 Thinking Broad, Acting Fast: Latent Reasoning Distillation

**arXiv:** [2601.21611](https://arxiv.org/abs/2601.21611) | **WWW 2026 Industry Track採択**

## 概要

EC検索における関連性モデリングをLLMのChain-of-Thought推論で改善しつつ、推論時のレイテンシを実用レベルに抑えるフレームワーク。

## 手法

### 1. Multi-Perspective CoT (MPCoT)
- **ユーザー意図視点**: クエリの真の意図を推論
- **属性マッチング視点**: 商品属性との整合性を評価
- **ビジネスルール視点**: 事業固有のルールを考慮
- 3つの視点から多様な推論根拠を生成

### 2. 教師モデル最適化
- SFT + DPOで推論品質を向上
- 複数視点の統合で頑健な判定

### 3. Latent Reasoning Knowledge Distillation (LRKD)
- **推論時に軽量な潜在推論抽出器を使用**
- LLMの複雑な推論能力を低レイテンシで内面化
- CoTの根拠構造を捨てずに活用

## 実験結果

- 大規模EC検索広告プラットフォームでオフライン評価 + オンラインA/Bテスト
- **数千万DAU**のサービスで検証済み
- 商業パフォーマンスとUXの両面で明確な改善

## ポイント

| 項目 | 内容 |
|------|------|
| 問題 | LLM CoTは高精度だが推論遅い |
| 解決 | 潜在空間で推論を蒸留 |
| 結果 | 低レイテンシで推論能力を獲得 |
| 運用 | 数千万DAUの実サービスで検証 |

## 関連技術

- Chain-of-Thought Prompting
- Knowledge Distillation
- E-commerce Query-Product Relevance

[← 一覧に戻る](../index)
