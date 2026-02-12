---
layout: paper
title: "pplx-embed: Diffusion-Pretrained Dense and Contextual Embeddings"
arxiv_id: "2602.11151"
date: 2026-02-12
categories: [cs.LG, cs.CL, cs.IR]
company: "Perplexity AI"
---

# pplx-embed: Diffusion-Based Embeddings

## 基本情報
- **arXiv**: [2602.11151](https://arxiv.org/abs/2602.11151)
- **カテゴリ**: cs.LG, cs.CL, cs.IR
- **著者**: Markus Krimmel et al. (Perplexity AI)

## 概要

Diffusion事前訓練言語モデルバックボーンを用いた多言語埋め込みモデルファミリー。双方向アテンションによる包括的コンテキスト捕捉を実現。

## モデルラインナップ

| モデル | 用途 |
|--------|------|
| pplx-embed-v1 | 標準検索 |
| pplx-embed-context-v1 | 文脈化埋め込み（文書グローバルコンテキストを段落表現に組込） |

## 技術的特徴

- **Mean Pooling**: 双方向コンテキストを活用
- **Late Chunking**: 長文書にわたるグローバルコンテキスト保持

## ベンチマーク性能

競争力のある性能を達成：
- MTEB (Multilingual, v2)
- MTEB (Code)
- MIRACL
- BERGEN
- ToolRet

pplx-embed-context-v1は**ConTEBで新記録**を樹立。

## 本番検証

数千万ドキュメント規模の大規模実世界検索シナリオで強力な性能を実証。
