---
layout: paper
title: "PAR: Protein Autoregressive Modeling via Multiscale Structure Generation"
date: 2026-02-06
arxiv_id: "2602.04883"
categories: ["cs.LG", "cs.AI", "q-bio.BM"]
institution: "ByteDance Seed"
project: "https://par-protein.github.io/"
---

# PAR: Protein Autoregressive Modeling

**arXiv**: https://arxiv.org/abs/2602.04883

**Project**: https://par-protein.github.io/

**機関**: ByteDance Seed

## 概要

タンパク質バックボーン生成のための初の**マルチスケール自己回帰フレームワーク**「PAR」を提案。

## 手法

彫刻を作るように、粗いトポロジーから細かい構造詳細へ段階的に生成:

1. **Multi-scale downsampling**: 複数スケールでタンパク質構造を表現
2. **Autoregressive transformer**: マルチスケール情報をエンコードし条件付き埋め込みを生成
3. **Flow-based backbone decoder**: 埋め込みに条件付けてバックボーン原子を生成

## 技術的工夫

- **Exposure bias対策**: Noisy context learningとscheduled samplingで訓練と生成のミスマッチを軽減
- **Zero-shot汎化**: ファインチューニングなしで柔軟な条件付き生成とモチーフスキャフォールディングをサポート

## 実験結果

- 無条件生成ベンチマークでタンパク質分布を効果的に学習
- 高いデザイン品質のバックボーンを生成
- 有望なスケーリング挙動を示す

## 所感

ByteDanceがタンパク質構造生成に参入。マルチスケール自己回帰という言語モデル的アプローチでタンパク質を扱うのは興味深い。
