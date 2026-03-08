---
layout: paper
title: "Observing and Controlling Features in Vision-Language-Action Models"
date: 2026-03-08
categories: [cs.RO]
---

# Observing and Controlling Features in Vision-Language-Action Models

- **arXiv**: [2603.05487](https://arxiv.org/abs/2603.05487)
- **著者**: Hugo Buurmeijer et al.
- **評価対象**: π₀.₅, OpenVLA

## 概要

Vision-Language-Action (VLA) モデルの内部表現の**特徴可観測性**と**特徴制御可能性**を分析。LLMの機械的解釈可能性の知見をVLAに転移する試み。

## 主な貢献

1. **特徴可観測性**: 表現空間で線形にエンコードされた特徴を線形分類器で観測
2. **特徴制御可能性**: 最適制御に基づく最小限の線形介入で内部表現を配置し、VLA出力を所望の領域に誘導

## 実験結果

- **π₀.₅とOpenVLA**で検証（シミュレーション実験）
- ターゲット化された軽量介入でロボットの振る舞いを確実に誘導
- クローズドループ能力を保持

## 注目ポイント

- **VLAが解釈可能な内部構造を持つことを実証**
- ファインチューニングなしでオンライン適応が可能
- ユーザー嗜好やタスク要件へのリアルタイム整合
- π₀.₅（Physical Intelligence）とOpenVLAという最新VLAで検証
