---
layout: paper
title: "DOS: Dual-Flow Orthogonal Semantic IDs for Recommendation in Meituan"
date: 2026-02-06
arxiv_id: "2602.04460"
categories: ["cs.IR"]
venue: "WWW'26"
industry: "Meituan"
deployed: true
---

# DOS: Dual-Flow Orthogonal Semantic IDs for Recommendation

**arXiv**: https://arxiv.org/abs/2602.04460

**採択**: WWW 2026（short paper）

**運用**: Meituan（美団）アプリで**数億ユーザー**にデプロイ済み

## 概要

生成型推薦システムにおけるSemantic IDの問題点を解決する「DOS」手法を提案。

## 技術的貢献

### 問題点
1. 生成タスクとSemantic ID codebook空間のギャップ
2. 既存の量子化手法によるセマンティック損失

### 解決策
- **Dual-Flow Framework**: ユーザー・アイテム双方向の協調シグナルで空間を整合
- **Orthogonal Residual Quantization**: セマンティック空間を適切な向きに回転させ、意味保存を最大化

## 実験結果

- オフライン実験で有効性を確認
- オンラインA/Bテストで性能向上を実証
- **数億ユーザー規模で本番運用中**

## 所感

LLMベースの生成型推薦でSemantic IDは重要だが、生成空間との整合性問題は見落とされがち。DOSはこの問題に正面から取り組み、実際にMeituanで大規模運用されている点が説得力を持つ。
