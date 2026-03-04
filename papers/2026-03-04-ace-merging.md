---
layout: paper
title: "ACE-Merging: Data-Free Model Merging with Adaptive Covariance Estimation"
date: 2026-03-04
categories: [cs.CL]
venue: "CVPR 2026"
arxiv_id: "2603.02945"
---

# ACE-Merging: Data-Free Model Merging with Adaptive Covariance Estimation

## 基本情報
- **arXiv**: https://arxiv.org/abs/2603.02945
- **著者**: Bo Xu, Haotian Wu, Hehai Lin, Weiquan Huang, Beier Zhu, Yao Shu, Chengwei Qin
- **採択**: CVPR 2026 Main Track

## 概要
複数のタスク固有エキスパートモデルを単一モデルに統合するデータフリーモデルマージング手法。入力共分散（最適マージングの鍵）をファインチューニング済みモデルのパラメータ差分から暗黙的に推定可能であることを理論的に証明。

## 主要貢献
1. **理論的証明**: データフリー設定でも入力共分散が推定可能
2. **ACE-Merging framework**: 適応的共分散推定によるタスク間干渉軽減
3. **Closed-form solution**: 従来の反復・ヒューリスティック手法と対照的な原理的解法
4. **Vision and Language**: 両ドメインでSOTA

## 実験結果
- Vision/Languageベンチマークで広範な評価
- データフリー手法の中で新たなSOTA
- GPT-2で7タスク平均**+4%絶対改善**
- 効率的なクローズドフォーム定式化で低計算コスト

## なぜ注目？
- **CVPR 2026 Main Track採択**
- 理論的に裏付けられたデータフリーマージング
- マルチタスク学習の実用的ソリューション
