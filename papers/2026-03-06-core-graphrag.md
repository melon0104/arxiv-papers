---
layout: paper
title: "Core-based Hierarchies for Efficient GraphRAG"
date: 2026-03-06
categories: [cs.IR, cs.CL]
---

# Core-based Hierarchies for Efficient GraphRAG

**arXiv**: [2603.05207](https://arxiv.org/abs/2603.05207)

**著者**: Jakir Hossain et al.

**カテゴリ**: cs.IR, cs.CL

## 概要

GraphRAGにおけるLeidenクラスタリングの限界を理論的に証明し、k-core分解による代替手法を提案。

## 理論的貢献

- **Leidenの非再現性を証明**: 疎なナレッジグラフ（平均次数が定数で、ほとんどのノードが低次数）において、モジュラリティ最適化は指数的に多くの準最適パーティションを許容
- **k-core分解**: 線形時間で決定論的・密度考慮の階層を生成

## 提案手法

- **軽量ヒューリスティックセット**: k-core階層を活用してサイズ制限・接続性保持のコミュニティを構築
- **トークン予算考慮サンプリング戦略**: LLMコストを削減

## 実験結果

- 金融決算トランスクリプト、ニュース記事、ポッドキャストの実世界データセットで評価
- 3つのLLMと5つの独立LLMジャッジによるhead-to-head評価
- **回答の包括性と多様性を一貫して向上**しながらトークン使用量を削減

## 注目ポイント

🔧 k-coreベースGraphRAGがグローバルセンスメイキングのための効果的で効率的なフレームワークであることを実証
