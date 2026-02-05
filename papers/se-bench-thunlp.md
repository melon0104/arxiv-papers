---
layout: paper
title: "SE-Bench: Benchmarking Self-Evolution with Knowledge Internalization"
date: 2026-02-06
arxiv_id: "2602.04811"
categories: ["cs.CL", "cs.AI", "cs.LG"]
institution: "THUNLP"
github: "https://github.com/thunlp/SE-Bench"
---

# SE-Bench: Self-Evolution Benchmark

**arXiv**: https://arxiv.org/abs/2602.04811

**GitHub**: https://github.com/thunlp/SE-Bench

**機関**: THUNLP（清華大学NLP研究室）

## 概要

エージェントの自己進化能力（新しい知識を内化して将来の問題解決に活用）を厳密に測定するための診断環境「SE-Bench」を提案。

## 課題

従来の評価には2つの障害:
1. **事前知識の混在**: 「新しい」知識が事前学習データに含まれている可能性
2. **推論複雑さの混在**: 失敗が知識想起能力か問題難易度かを区別できない

## 提案: SE-Bench

- NumPyライブラリとAPIドキュメントを**偽装・難読化**
- エージェントはこのパッケージを内化し、ドキュメントなしで簡単なコーディングタスクを解く
- 新しいAPIドキュメントがあれば簡単だが、なければ不可能な設定

## 主な発見

1. **Open-Book Paradox**: 参照ドキュメントで訓練すると保持を**阻害**→「Closed-Book Training」で強制圧縮が必要
2. **RL Gap**: 標準RLはPPOクリッピングと負の勾配により新知識を完全に内化できない
3. **Self-Playの可能性**: ノイズのある自己生成タスクからSFTで学習可能（RLでは不可）

## 所感

自己進化能力の厳密な測定は今後のエージェント開発に不可欠。SE-Benchは知識内化の根本的な課題を明らかにし、重要な研究基盤を提供する。
