---
layout: paper
title: "IndexCache: Accelerating Sparse Attention via Cross-Layer Index Reuse"
date: 2026-03-13
arxiv_id: "2603.12201"
categories: [cs.CL, cs.LG]
---

# IndexCache: Accelerating Sparse Attention

## 基本情報
- **arXiv ID**: 2603.12201
- **カテゴリ**: cs.CL, cs.LG
- **投稿日**: 2026年3月12日
- **注目ポイント**: 🏛️ **Tsinghua（清華大学）**, **GLM-5モデル**

## 概要
DeepSeek Sparse Attention (DSA)のインデクサ計算を、レイヤー間の冗長性を活用して最大75%削減。GLM-5を含む本番規模モデルで検証。

## 主要な貢献
1. **クロスレイヤー冗長性の発見**: 連続レイヤーのtop-k選択が高度に類似
2. **Training-free IndexCache**: 校正セットで言語モデリング損失を直接最小化するgreedy search
3. **Training-aware IndexCache**: 平均アテンション分布に対するマルチレイヤー蒸留損失

## 性能向上
| 指標 | 改善 |
|------|------|
| インデクサ計算削減 | 75% |
| Prefill高速化 | 最大1.82x |
| Decode高速化 | 最大1.48x |

## 意義
長コンテキストエージェントワークフローにおいて、アテンション効率は推論速度とコストの両面で重要。本手法は品質劣化なしに大幅な高速化を実現。

## リンク
- [arXiv](https://arxiv.org/abs/2603.12201)
- [PDF](https://arxiv.org/pdf/2603.12201)
