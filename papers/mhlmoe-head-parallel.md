---
layout: paper
title: "Multi-Head LatentMoE and Head Parallel: Communication-Efficient MoE"
date: 2026-02-06
arxiv_id: "2602.04870"
categories: ["cs.LG"]
---

# Multi-Head LatentMoE and Head Parallel

**arXiv**: https://arxiv.org/abs/2602.04870

## 概要

Expert Parallel (EP)の限界を克服する新しいMoEアーキテクチャと分散訓練手法を提案。

## Expert Parallelの問題点

1. **通信コスト**: 活性化エキスパート数kに対して線形増加
2. **負荷不均衡**: レイテンシとメモリ使用量に影響
3. **決定論的通信の欠如**: データ依存通信でメタデータ交換が必要

## 提案手法

### Multi-Head LatentMoE
- 新しいMoEアーキテクチャ

### Head Parallel (HP)
- **O(1)通信コスト**: kに関係なく一定
- **完全に均衡したトラフィック**
- **決定論的通信**
- EPとの互換性あり

### 最適化
- IO-aware routingとexpert computationで高速化

## 実験結果

- MoE + EPと比較して**最大1.61倍高速**な訓練
- 2倍の粒度でも**1.11倍高速**でより高い性能

## インパクト

数十億パラメータ規模のファウンデーションモデル研究を**より手軽に**

## 所感

MoEの分散訓練における通信ボトルネックは実用上の大きな課題。Head Parallelは理論的にエレガントで実用的な解決策を提供。
