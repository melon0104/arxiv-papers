---
layout: default
title: Scaling Embeddings vs Experts
---

# Scaling Embeddings Outperforms Scaling Experts in Language Models

**arXiv:** [2601.21204](https://arxiv.org/abs/2601.21204) | **カテゴリ:** cs.CL, cs.AI, cs.LG

## 概要

MoEアーキテクチャの限界を超える新しいスケーリング次元として**埋め込みスケーリング**を提案。エキスパートスケーリングよりも優れたPareto frontierを達成する条件を体系的に分析。システム最適化と投機的デコーディングにより、スパース性を実際の推論高速化に変換。

## 主要な貢献

1. **埋め込みスケーリング**: MoEに直交するスパース性スケーリング次元
2. **アーキテクチャ因子分析**: パラメータ予算、モデル幅/深さとの相互作用
3. **LongCat-Flash-Lite**: 68.5Bパラメータ、~3B活性化で訓練

## 結果

- 30B以上のパラメータを埋め込みに割り当て
- パラメータ同等のMoEベースラインを上回る
- 特に**エージェント・コーディング領域**で強い競争力

## 選定理由

✅ MoEスケーリングの新しいパラダイム

[← 戻る](/)
