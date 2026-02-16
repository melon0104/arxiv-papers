---
layout: paper
title: "TCMax: Multimodal Classification via Total Correlation Maximization"
date: 2026-02-17
arxiv_id: "2602.13015"
category: cs.LG
tags: [multimodal, classification, information-theory, iclr-2026, github]
---

# Multimodal Classification via Total Correlation Maximization

## 基本情報
- **arXiv**: [2602.13015](https://arxiv.org/abs/2602.13015)
- **採択**: ICLR 2026
- **GitHub**: [hubaak/TCMax](https://github.com/hubaak/TCMax)
- **著者**: Feng Yu, Xiangyu Wu, Yang Yang, Jianfeng Lu

## 🏆 ICLR 2026 採択

## 一言まとめ
マルチモーダル学習における「モダリティ競合」問題を情報理論の観点から分析し、Total Correlationの最大化で解決。

## 課題: Modality Competition
- 同時学習では特定モダリティに過学習し他を無視
- 単一モダリティ学習より性能が低下することも

## 提案手法: TCMax
### 理論的分析
- モダリティ競合を情報理論的に分析
- マルチモーダル特徴とラベル間のTotal Correlationを最大化

### Total Correlation Neural Estimation (TCNE)
- MINE (Mutual Information Neural Estimation) を拡張
- Total Correlationの下界を導出

### TCMax損失関数
- ハイパーパラメータフリー
- 変分境界最適化でTotal Correlationを最大化

## 実験結果
- 同時学習・単一モダリティ学習の両アプローチを上回る
- 複数データセットでSOTA

## キーポイント
- モダリティ競合の情報理論的理解
- ハイパーパラメータ不要の損失関数
- ICLR 2026採択の信頼性
