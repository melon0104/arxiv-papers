---
layout: paper
title: "Latent Policy Steering through One-Step Flow Policies"
date: 2026-03-06
categories: [cs.RO, cs.LG]
---

# Latent Policy Steering through One-Step Flow Policies

**arXiv**: [2603.05296](https://arxiv.org/abs/2603.05296)

**著者**: HoKyun Im et al.

**カテゴリ**: cs.RO, cs.LG

## 概要

オフライン強化学習において、微分可能なone-step MeanFlowポリシーを通じて元のアクション空間のQ勾配を逆伝播することで、高忠実度の潜在ポリシー改善を可能にする「Latent Policy Steering (LPS)」を提案。

## 技術的貢献

- **プロキシ潜在クリティックの排除**: 元のアクション空間のクリティックがエンドツーエンドの潜在空間最適化をガイド
- **行動制約付き生成事前分布**: one-step MeanFlowポリシーが行動制約付き生成事前分布として機能
- **ロバストな手法**: 最小限のチューニングでそのまま使用可能

## 実験結果

- OGBenchおよび実世界ロボットタスクでSOTA性能
- 行動クローニングと強力な潜在ステアリングベースラインを一貫して上回る

## プロジェクトページ

https://jellyho.github.io/LPS/

## 注目ポイント

🤖 オフラインRLの「リターン最大化 vs 行動制約」のトレードオフを構造的に解決
