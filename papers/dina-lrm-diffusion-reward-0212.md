---
layout: paper
title: "DiNa-LRM: Beyond VLM-Based Rewards: Diffusion-Native Latent Reward Modeling"
arxiv_id: "2602.11146"
date: 2026-02-12
categories: [cs.CV, cs.AI]
github: "https://github.com/HKUST-C4G/diffusion-rm"
---

# DiNa-LRM: Diffusion-Native Reward Model

## 基本情報
- **arXiv**: [2602.11146](https://arxiv.org/abs/2602.11146)
- **カテゴリ**: cs.CV, cs.AI
- **著者**: Gongye Liu et al.
- **コード**: [GitHub](https://github.com/HKUST-C4G/diffusion-rm)

## 概要

VLMベース報酬の代替として、ノイズ付きdiffusion状態上で直接嗜好学習を行うdiffusionネイティブ潜在報酬モデル。

## 技術的貢献

### Noise-Calibrated Thurstone Likelihood
- diffusionノイズ依存の不確実性を導入

### アーキテクチャ
- 事前訓練済み潜在diffusionバックボーン
- タイムステップ条件付き報酬ヘッド
- 推論時ノイズアンサンブル対応

## 性能

画像アラインメントベンチマーク：
- 既存diffusionベース報酬ベースラインを大幅に上回る
- SOTAなVLMと同等性能を**計算コストの数分の一**で達成

## 嗜好最適化での効果

- 最適化ダイナミクスの改善
- より高速でリソース効率的なモデルアラインメント
