---
layout: paper
title: "EST: Towards Efficient Scaling Laws in Click-Through Rate Prediction via Unified Modeling"
arxiv_id: "2602.10811"
date: 2026-02-12
categories: [cs.IR]
deployed: true
company: "Alibaba/Taobao"
---

# EST: Efficiently Scalable Transformer for CTR Prediction

## 基本情報
- **arXiv**: [2602.10811](https://arxiv.org/abs/2602.10811)
- **カテゴリ**: cs.IR
- **著者**: Yong Bai et al. (Alibaba)
- **実運用**: Taobao Display Advertising

## 概要

CTR予測におけるスケーリング則を効率的に実現するTransformerアーキテクチャ。完全な統一モデリングにより、情報ボトルネックなしで全raw入力を処理。

## 技術的貢献

### Lightweight Cross-Attention (LCA)
- 冗長なself-interactionを削減
- 高インパクトなクロス特徴依存に集中

### Content Sparse Attention (CSA)
- コンテンツ類似度で高シグナル行動を動的選択
- 行動/非行動特徴間の情報密度非対称性に対処

## 本番結果

| 指標 | 改善 |
|------|------|
| RPM (Revenue Per Mile) | **+3.27%** |
| CTR | **+1.22%** |

## 意義

安定したパワーロースケーリング関係を示し、モデルスケールによる予測可能な性能向上を実現。産業規模CTR予測の実用的パスを確立。
