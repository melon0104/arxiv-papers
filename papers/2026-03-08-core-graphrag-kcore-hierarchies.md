---
layout: paper
title: "Core-based Hierarchies for Efficient GraphRAG"
date: 2026-03-08
categories: [cs.IR, cs.CL]
---

# Core-based Hierarchies for Efficient GraphRAG

- **arXiv**: [2603.05207](https://arxiv.org/abs/2603.05207)
- **著者**: Jakir Hossain et al.
- **GitHub**: あり

## 概要

GraphRAGのコミュニティ検出でLeidenクラスタリングの代わりにk-core分解を提案。Leidenベースの手法は疎なナレッジグラフ上で指数関数的に多くの準最適分割を持ち、再現性がないことを数学的に証明した。

## 主な貢献

1. **Leidenの非再現性を証明**: 疎なグラフでモジュラリティ最適化が指数関数的に多くの準最適解を持つ
2. **k-core分解による決定論的階層**: 線形時間で密度認識型の階層を構築
3. **トークン予算考慮のサンプリング戦略**: LLMコストを削減

## 実験結果

- 決算発表トランスクリプト、ニュース記事、ポッドキャストで評価
- 3つのLLMで回答生成、5つの独立LLMジャッジで比較評価
- **回答の包括性・多様性が向上**しつつトークン使用量を削減

## 注目ポイント

- **k-core分解によるGraphRAGの再現性問題解決**
- 複数データセット・モデルで一貫した改善
- 実世界データセットでの広範な評価
