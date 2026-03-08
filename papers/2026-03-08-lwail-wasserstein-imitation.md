---
layout: paper
title: "Latent Wasserstein Adversarial Imitation Learning"
date: 2026-03-08
categories: [cs.LG]
---

# Latent Wasserstein Adversarial Imitation Learning (LWAIL)

- **arXiv**: [2603.05440](https://arxiv.org/abs/2603.05440)
- **会議**: **ICLR 2026 採択**
- **著者**: Siqi Yang et al.

## 概要

状態のみの分布マッチングに焦点を当てた新しい敵対的模倣学習フレームワーク。動力学認識型潜在空間でワッサースタイン距離を計算することで、少数のエキスパートエピソードからエキスパートレベルの性能を達成。

## 主な貢献

1. **Intention Conditioned Value Function（ICVF）**: 動力学認識型の潜在空間構造を獲得
2. **状態のみのデータで事前訓練**: ランダム生成された状態のみのデータを使用
3. **少数エピソードで高性能**: 1〜数エピソードの状態のみエキスパートデータで十分

## 実験結果

- MuJoCo環境で評価
- 従来のワッサースタインベースIL手法を上回る
- 従来の敵対的IL手法を上回る
- 様々なタスクでより良い結果

## 注目ポイント

- **ICLR 2026採択**
- 状態のみ・少数エピソードでエキスパートレベル達成
- データ効率的な模倣学習
