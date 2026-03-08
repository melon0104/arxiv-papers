---
layout: paper
title: "POET-X: Memory-efficient LLM Training by Scaling Orthogonal Transformation"
date: 2026-03-08
categories: [cs.LG, cs.AI, cs.CL]
---

# POET-X: Memory-efficient LLM Training by Scaling Orthogonal Transformation

- **arXiv**: [2603.05500](https://arxiv.org/abs/2603.05500)
- **著者**: Weiyang Liu et al.
- **プロジェクト**: https://spherelab.ai/poetx/

## 概要

直交等価変換によるメモリ効率的なLLM事前訓練手法POET-Xを提案。元のPOETの安定性を維持しながら、計算オーバーヘッドとメモリ消費を大幅に削減。

## 主な貢献

1. **スケーラブルな直交変換**: 計算コストを大幅に削減しながらスペクトル保存
2. **単一GPUで10億パラメータ訓練**: H100 1台で1Bパラメータの事前訓練が可能
3. **AdamW比較**: 同条件でAdamWはOOM（メモリ不足）

## 技術的詳細

- 各重み行列を直交等価変換で最適化
- POETの汎化・安定性の利点を維持
- スループットとメモリ効率の大幅な改善

## 実験結果

- **単一H100で10億パラメータの事前訓練を実現**
- AdamWは同条件でOOM
- 汎化性能と訓練安定性を維持

## 注目ポイント

- 大規模モデル訓練の民主化に貢献
- リソース制約下でのLLM開発に有用
