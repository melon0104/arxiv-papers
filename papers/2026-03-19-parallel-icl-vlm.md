---
layout: paper
title: "Parallel In-Context Learning for Large Vision Language Models"
date: 2026-03-19
arxiv_id: "2603.16092"
categories: ["cs.CV", "cs.AI", "cs.LG"]
venue: "CVPR 2026 Findings"
---

# Parallel In-Context Learning for Large Vision Language Models

## 基本情報

| 項目 | 内容 |
|------|------|
| arXiv | [2603.16092](https://arxiv.org/abs/2603.16092) |
| 採択 | **CVPR 2026 (Findings)** |
| GitHub | https://github.com/yshinya6/parallel-icl |

## 概要

多モーダルIn-Context Learning（MM-ICL）の精度-効率トレードオフを解決する**Parallel-ICL**を提案。デモンストレーションを並列処理することで、フルコンテキストに近い性能を大幅に高速化。

## 問題設定

- デモンストレーション数を増やすと性能向上
- しかしTransformerの二次的計算コストで推論遅延が増大
- 精度と効率のトレードオフが課題

## 提案手法: Parallel-ICL

### コンテキストチャンク分割
- 長いデモンストレーションコンテキストを複数の短いチャンクに分割
- 各チャンクを**並列処理**

### Product-of-Experts (PoE) アンサンブル
- 各チャンクの予測をロジットレベルで統合
- 重み付きPoEアンサンブルでフルコンテキスト出力を近似

### アンサンブル理論に基づく戦略

1. **クラスタリングベースのチャンク分割** - チャンク間の多様性を最大化
2. **類似度ベースのコンテキスト編成** - クエリ関連度で予測を重み付け

## 主要な結果

- VQA、画像キャプション、分類ベンチマークで検証
- フルコンテキストMM-ICLに匹敵する性能
- **推論速度を大幅に改善**

## 技術的貢献

1. MM-ICLの並列化フレームワーク
2. アンサンブル理論に基づいた原理的なチャンク戦略
3. プラグアンドプレイで既存モデルに適用可能

## 意義

動的タスク適応を大幅に低い推論オーバーヘッドで実現。MM-ICLの実用化に向けた重要な一歩。
