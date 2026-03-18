---
layout: paper
title: "CGC: Capability-Guided Compression for LLMs"
date: 2026-03-19
arxiv_id: "2603.16440"
categories: ["cs.LG", "cs.CL"]
---

# Capability-Guided Compression: Toward Interpretability-Aware Budget Allocation for LLMs

## 基本情報

| 項目 | 内容 |
|------|------|
| arXiv | [2603.16440](https://arxiv.org/abs/2603.16440) |
| 手法 | Sparse Autoencoder (SAE) ベース |
| 検証モデル | GPT-2 Medium |

## 概要

LLM圧縮の根本的限界「**capability-blind compression問題**」を特定。SAE由来のcapability density mapsを用いて、コンポーネントごとに差分圧縮予算を割り当てる**CGC**フレームワークを提案。

## 問題設定

### Capability-Blind Compression問題
> 既存手法は全て、モデルコンポーネントが機能的に何をエンコードしているかの表現なしに圧縮予算を割り当て

### 関連する失敗モード
1. Perplexityベース評価の推論能力損失への非感度
2. Ma et al. (2026)が特徴付けた性能の急激な相転移

## 提案手法: Capability-Guided Compression (CGC)

### Capability Density
- SAE特徴活性化分布から導出
- 以下を組み合わせたスカラー尺度：
  - **Feature breadth** - 特徴の広がり
  - **Activation entropy** - 活性化エントロピー
  - **Cross-input consistency** - 入力間一貫性

### 理論的保証
- 高capability densityのコンポーネント → 低構造冗長性
- より低い圧縮率で相転移点に到達
- **コンポーネントレベルの相転移予測の初の事前圧縮メカニズム**

## 主要な発見

### 直交性の実証
- Capability densityはWanda重要度スコアと**統計的に独立**
- Spearman ρ = -0.054 (n = 384 heads)
- 既存重要度指標と**直交する新規圧縮信号**

## 技術的貢献

1. Capability-blind compression問題の特定
2. SAEベースのcapability density定式化
3. 既存指標との直交性の実証

## 意義

capability-aware圧縮研究の基盤を確立。LLM圧縮の理論的理解を深め、より原理的なアプローチへの道を開く。
