---
layout: default
title: "OPERA: Online Data Pruning for Efficient Retrieval Model Adaptation"
---

# OPERA: Online Data Pruning for Efficient Retrieval Model Adaptation

[arXiv:2603.17205](https://arxiv.org/abs/2603.17205) | cs.IR

## 著者
Haoyang Fang et al.

## 一言まとめ
検索モデル適応のためのデータ剪定フレームワーク。動的剪定で**NDCG@10 +1.9%**、**Recall@20 +0.7%**を達成、標準ファインチューニングの**50%未満の訓練時間**で同等性能。

## 概要
ドメイン特化ファインチューニングは密検索器に必須だが、全ての訓練ペアが等しく貢献するわけではない。OPERAはこの異質性を活用し、検索モデル適応の効果と効率を向上。静的剪定(SP)は高類似度ペアのみ保持するが、品質-カバレッジのトレードオフが存在。これを解決する2段階動的剪定(DP)戦略を提案。

## 注目ポイント
- **効率的訓練**: 50%未満の訓練時間で同等性能達成
- **アーキテクチャ非依存**: Qwen3-Embeddingでも効果確認
- **品質-カバレッジトレードオフ解決**: 2段階動的剪定で両立
- **8データセット・6ドメインで検証**: 平均ランク1.38

## 技術的詳細
- 静的剪定(SP): 高類似度ペアのみ保持、NDCG@10 +0.5%
- 動的剪定(DP): クエリ・ドキュメントレベルでサンプリング確率を適応的に調整
- 訓練全体を通じて高品質例を優先しつつ全訓練セットへのアクセスを維持

## 関連リンク
- [arXiv](https://arxiv.org/abs/2603.17205)
- [PDF](https://arxiv.org/pdf/2603.17205)
