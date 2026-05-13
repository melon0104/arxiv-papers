---
layout: paper
title: "ZipRerank: Very Efficient Listwise Multimodal Reranking for Long Documents"
date: 2026-05-14
category: cs.IR
arxiv_id: "2605.11864"
url: https://arxiv.org/abs/2605.11864
authors:
  - Yiqun Sun
  - Pengfei Wei
  - Lawrence B. Hsieh
tags: [reranking, multimodal, RAG, vision-language, efficiency]
---

# ZipRerank: Very Efficient Listwise Multimodal Reranking for Long Documents

## 概要

マルチモーダルRAGにおけるリストワイズ再ランキングの計算コスト問題を解決する研究。VLMベースのリランカーは精度が高いが、長い視覚トークン列と多段階のオートレグレッシブデコードによって実用性が制限される。

ZipRerankは2つのボトルネックに直接対処する高効率なリストワイズマルチモーダルリランカー。クエリ-画像関連性スコアリングによる軽量な入力長削減と、直接分類による推論効率化を実現。

## 選定理由

- cs.IR（情報検索）の核心トピック：マルチモーダルRAGの再ランキング
- 実用性（効率化）を重視した産業応用重要論文
- M-RAG（マルチモーダルRAG）の発展に貢献

## キーポイント

- **課題**: VLMベースリランカーは精度高いが計算コスト高
- **手法**: クエリ-画像軽量スコアリングで入力削減 + 直接分類でデコード効率化
- **効果**: 精度を維持しながら大幅な計算コスト削減

## arXiv

https://arxiv.org/abs/2605.11864
