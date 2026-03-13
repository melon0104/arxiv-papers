---
layout: paper
title: "EVATok: Adaptive Length Video Tokenization"
date: 2026-03-13
arxiv_id: "2603.12267"
categories: [cs.CV]
---

# EVATok: Efficient Video Adaptive Tokenizers

## 基本情報
- **arXiv ID**: 2603.12267
- **カテゴリ**: cs.CV（コンピュータビジョン）
- **投稿日**: 2026年3月12日
- **注目ポイント**: 🏆 **CVPR 2026採択**

## 概要
自己回帰動画生成モデル用の適応長トークン化フレームワーク「EVATok」を提案。静的・反復的セグメントと動的セグメントで最適なトークン割り当てを実現。

## 主要な貢献
1. **最適トークン割り当て**: 品質-コストトレードオフを最大化
2. **軽量ルーター**: 高速な割り当て予測
3. **適応トークナイザ**: ルーター予測に基づくエンコード

## 性能向上
| 指標 | 結果 |
|------|------|
| UCF-101 Class-to-Video | SOTA |
| 平均トークン使用量削減 | 最低24.4% |
| vs LARP（先行SOTA） | 24.4%以上削減 |

## 技術的工夫
動画意味エンコーダを統合した高度な訓練レシピにより、動画再構成と下流AR生成の両方で大幅な効率・品質改善を達成。

## リンク
- [arXiv](https://arxiv.org/abs/2603.12267)
- [プロジェクトページ](https://silentview.github.io/EVATok/)
