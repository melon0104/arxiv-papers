---
layout: paper
title: "S-GRec: Personalized Semantic-Aware Generative Recommendation with Asymmetric Advantage"
arxiv_id: "2602.10606"
date: 2026-02-12
categories: [cs.IR]
deployed: true
---

# S-GRec: Semantic-Aware Generative Recommendation

## 基本情報
- **arXiv**: [2602.10606](https://arxiv.org/abs/2602.10606)
- **カテゴリ**: cs.IR
- **著者**: Zhenmao Li et al.
- **実運用**: 大規模本番システムでA/Bテスト済み

## 概要

LLMの意味的事前知識を生成型推薦に活用しつつ、リアルタイム推論コストを回避するフレームワーク。オンライン軽量生成器とオフラインLLMベース意味判定器を分離。

## 技術的貢献

### Personalized Semantic Judge (PSJ)
- 2段階処理：解釈可能なアスペクト証拠生成 → ペアワイズフィードバックからのユーザー条件付き集約学習
- 安定した意味報酬を生成

### Asymmetric Advantage Policy Optimization (A2PO)
- ビジネス報酬（eCPM等）をアンカーに最適化
- 意味的優位性は一貫性がある場合のみ注入

## 本番結果

| 指標 | 改善 |
|------|------|
| CTR | 統計的に有意な向上 |
| GMV | **+1.19%** |

リアルタイムLLM推論なしでこれらの改善を達成。
