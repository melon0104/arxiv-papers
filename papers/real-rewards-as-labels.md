# REAL: Rewards as Labels - Revisiting RLVR from a Classification Perspective

- **arXiv**: [2602.05630](https://arxiv.org/abs/2602.05630)
- **カテゴリ**: cs.LG, cs.CL
- **投稿日**: 2026-02-05

## 概要

Verifiable Rewardsを用いたRLにおいて、報酬をカテゴリカルラベルとして扱い、ポリシー最適化を分類問題として再定式化するフレームワーク「REAL」を提案。

## 問題提起

GRPOとその変種の2つの問題を特定:
- **Gradient Misassignment in Positives**: 正例での勾配誤割り当て
- **Gradient Domination in Negatives**: 負例での勾配支配

## 主要な貢献

- **ラベルとしての報酬**: スカラー重みではなくカテゴリカルラベルとして扱う
- **Anchor logits**: ポリシー学習を強化
- **単調かつ有界な勾配重み付け**: ロールアウト間でバランスの取れた勾配配分

## 実験結果

- 1.5Bモデル: DAPO比で平均Pass@1が**6.7%向上**
- 7Bモデル: DAPO比6.2%、GSPO比1.7%向上
- バニラバイナリクロスエントロピーでも安定してDAPOを4.5%上回る

## リンク

- [PDF](https://arxiv.org/pdf/2602.05630)
