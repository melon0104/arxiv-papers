---
layout: paper
title: "FlashEvaluator: Expanding Search Space with Parallel Evaluation"
date: 2026-03-04
categories: [cs.IR, cs.CL, cs.LG]
venue: "Kuaishou Production"
arxiv_id: "2603.02565"
---

# FlashEvaluator: Expanding Search Space with Parallel Evaluation

## 基本情報
- **arXiv**: https://arxiv.org/abs/2603.02565
- **著者**: Chao Feng, Yuanhao Pu, Chenghao Zhang, Shanqi Liu, Shuchang Liu, Xiang Li, Yongqi Liu, Lantao Hu, Kaiqiao Zhan, Han Li, **Kun Gai** (Kuaishou)
- **実運用**: Kuaishou（快手）オンライン推薦システム

## 概要
Generator-Evaluator (G-E)フレームワークにおける評価器の並列化。従来の評価器はシーケンスを独立に処理し、O(K)の線形計算量を持つ。FlashEvaluatorはクロスシーケンストークン情報共有を可能にし、単一フォワードパスで全シーケンスを処理。

## 主要貢献
1. **Cross-sequence token information sharing**: シーケンス間比較を明示的にモデル化
2. **Sublinear computational complexity**: O(K)からサブリニアへ削減
3. **Single forward pass processing**: 全候補シーケンスを一度に評価
4. **Theoretical analysis**: 理論的証明と広範な実験

## 実験結果
- 推薦システムとNLPタスクで検証
- 精度向上とレイテンシ削減を同時達成
- **Kuaishouオンライン推薦システムに本番投入**
- 実質的かつ持続的な収益向上を実現

## なぜ注目？
- **中国大手動画プラットフォームKuaishou本番運用**
- G-Eパラダイムの効率化という汎用的貢献
- NLPと推薦両方に適用可能
