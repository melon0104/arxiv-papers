---
layout: paper
title: "FlashSchNet: Fast and Accurate Coarse-Grained Neural Network Molecular Dynamics"
date: 2026-02-17
arxiv_id: "2602.13140"
category: cs.LG
tags: [molecular-dynamics, gnn, optimization, gpu, github]
---

# FlashSchNet: Fast and Accurate Coarse-Grained Neural Network Molecular Dynamics

## 基本情報
- **arXiv**: [2602.13140](https://arxiv.org/abs/2602.13140)
- **GitHub**: [UNITES-Lab/flash-molecular-dynamics](https://github.com/UNITES-Lab/flash-molecular-dynamics)
- **著者**: Pingzhi Li, Hongxuan Li, Zirui Liu, Xingcheng Lin, Tianlong Chen

## 一言まとめ
GNNベース分子動力学シミュレーションを高速化するIO-aware最適化。RTX PRO 6000で1000 ns/dayのスループットを達成。

## 課題
- GNNポテンシャル（SchNetなど）は精度と転移性は高いが古典力場より遅い
- 断片化カーネルとメモリバウンドパイプラインがGPUを低活用

## 提案手法: FlashSchNet
### IO-aware設計原則
HBM（高帯域メモリ）とオンチップSRAM間のR/Wを精密に管理

### 4つの最適化技術
1. **Flash Radial Basis**: ペアワイズ距離計算、ガウス基底展開、コサイン包絡を単一タイルドパスに融合
2. **Flash Message Passing**: カットオフ、近傍収集、フィルタ乗算、リダクションを融合
3. **Flash Aggregation**: Scatter-AddをCSRセグメントリダクションで再定式化
4. **チャネルワイズ16bit量子化**: 精度損失なしでスループット向上

## 実験結果
### NVIDIA RTX PRO 6000
- **スループット**: 1000 ns/day（64並列レプリカ、269ビーズタンパク質）
- **CGSchNetベースライン比**: 6.5倍高速
- **ピークメモリ**: 80%削減
- 古典力場（MARTINI等）を超えつつSchNetレベルの精度を維持

## キーポイント
- 初のIO-aware GNN-MD最適化
- 古典力場を超える速度と精度の両立
- 実用的なコード公開
