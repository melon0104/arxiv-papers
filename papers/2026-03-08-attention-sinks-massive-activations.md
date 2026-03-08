---
layout: paper
title: "The Spike, the Sparse and the Sink: Anatomy of Massive Activations and Attention Sinks"
date: 2026-03-08
categories: [cs.AI, cs.CL]
---

# Massive Activations and Attention Sinks Anatomy

- **arXiv**: [2603.05498](https://arxiv.org/abs/2603.05498)
- **著者**: Jiachen Zhu et al.

## 概要

Transformer言語モデルで繰り返し観察される2つの現象を研究：**Massive Activations**（少数トークンが数チャネルで極端な外れ値を示す）と**Attention Sinks**（特定トークンが意味的関連性に関係なく不釣り合いなアテンションを集める）。

## 主な発見

1. **共起はアーキテクチャの人工物**: 現代Transformerの設計選択による
2. **異なる機能**: 関連するが別々の機能を果たす

### Massive Activations
- **グローバルに動作**: レイヤーを超えて持続するほぼ一定の隠れ表現を誘導
- モデルの暗黙的パラメータとして機能

### Attention Sinks
- **ローカルに動作**: ヘッド間でアテンション出力を調整
- 個々のヘッドを短距離依存性にバイアス

## 重要な発見

- **Pre-norm構成がキー**: 両現象の共起を可能にする
- Pre-normを削除すると両現象が分離

## 注目ポイント

- Transformerの内部動作の深い理解に貢献
- アーキテクチャ設計への示唆
- 効率的なモデル設計への応用可能性
