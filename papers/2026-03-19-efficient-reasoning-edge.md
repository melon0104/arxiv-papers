---
layout: paper
title: "Efficient Reasoning on the Edge"
date: 2026-03-19
arxiv_id: "2603.16867"
categories: ["cs.LG", "cs.CL"]
organization: "Qualcomm AI Research"
---

# Efficient Reasoning on the Edge

## 基本情報

| 項目 | 内容 |
|------|------|
| arXiv | [2603.16867](https://arxiv.org/abs/2603.16867) |
| 組織 | **Qualcomm AI Research** |
| デモ | https://qualcomm-ai-research.github.io/llm-reasoning-on-edge/ |

## 概要

Chain-of-Thought推論を持つLLMのエッジデプロイメントを実現。LoRAアダプターと強化学習によるバジェット強制で、応答長を大幅削減しながら精度を維持。

## 問題設定

- CoT推論は冗長な推論トレースを生成
- 大きなコンテキスト要求、高トークン生成コスト
- 大きなKV-cacheフットプリント
- **モバイルデバイスでの推論が非実用的**

## 提案手法

### LoRAアダプター + 教師ありファインチューニング
- 軽量なアプローチで小型LLMの推論を有効化
- 既存のプリトレーニング済みモデルを活用

### 強化学習によるバジェット強制
- 応答長を**大幅削減**
- 精度損失は最小限

### 並列テストタイム・スケーリング
- メモリバウンドなデコーディングに対応
- わずかなレイテンシ増加で精度向上

### 動的アダプター切り替え
- 推論が必要な時のみアクティベート
- 不要な計算を回避

### KV-cache共有戦略
- プロンプトエンコーディング時にキャッシュ共有
- **Time-to-first-token削減**

## 主要な結果 (Qwen2.5-7B)

- 厳しいリソース制約下で効率的かつ正確な推論を実現
- **実際のモバイルデバイスでの動作デモ公開**

## 技術的貢献

1. エッジ向けLLM推論の包括的フレームワーク
2. 複数の効率化技術の統合
3. 実機デモによる実用性の実証

## 意義

LLM推論のモバイルシナリオでの実用化に向けた重要な成果。Qualcomm AI Researchによる産業的に重要な研究。
