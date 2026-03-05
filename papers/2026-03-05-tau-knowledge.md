---
layout: paper
title: "τ-Knowledge: Evaluating Conversational Agents over Unstructured Knowledge"
date: 2026-03-05
categories: [cs.AI, cs.CL, cs.IR]
---

# τ-Knowledge: Evaluating Conversational Agents over Unstructured Knowledge

**arXiv**: [2603.04370](https://arxiv.org/abs/2603.04370)

## 著者
Quan Shi, Alexandra Zytek, Pedram Razavi, Karthik Narasimhan (Princeton), Victor Barres

## 一言まとめ
非構造化知識上でのエージェント評価ベンチマーク。τ-Bankingドメインで700文書ナビゲーション＋ツール実行を評価、**フロンティアモデルでも25.5%**の厳しい結果。

## 概要
会話エージェントは知識集約的設定で展開されるが、既存ベンチマークは検索とツール使用を独立評価。非構造化データ上での長期インタラクションでの現実的・完全エージェント評価にギャップ。

### 主要な技術貢献
1. **τ-Knowledge**: τ-Benchの拡張、外部自然言語知識とツール出力の協調が必要
2. **τ-Banking domain**: 現実的フィンテック顧客サポートワークフロー、約700相互接続文書
3. **Policy-compliant state changes**: 検証可能で方針準拠の状態変更生成が目標

### 実験結果
- **フロンティアモデル（高推論予算）**:
  - pass^1: 約25.5%
  - 繰り返し試行で信頼性が急激に低下
- 密に相互リンクされた知識ベースからの正確な文書検索に苦戦
- 複雑な内部方針に対する正確な推論が困難

## キーワード
Conversational Agents, Knowledge Retrieval, Benchmark, Tool Use, Princeton

## 選定理由
- Princeton著名研究者
- 現実的なエージェント評価
- 産業応用に直結
