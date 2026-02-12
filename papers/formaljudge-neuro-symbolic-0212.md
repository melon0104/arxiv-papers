---
layout: paper
title: "FormalJudge: A Neuro-Symbolic Paradigm for Agentic Oversight"
arxiv_id: "2602.11136"
date: 2026-02-12
categories: [cs.AI]
---

# FormalJudge: Formal Verification for Agent Safety

## 基本情報
- **arXiv**: [2602.11136](https://arxiv.org/abs/2602.11136)
- **カテゴリ**: cs.AI
- **著者**: Jiayi Zhou et al.

## 概要

LLM-as-a-Judge の根本的ジレンマ（確率的システムが確率的システムを監督する信頼性）に対し、形式検証によるエスケープを提案。

## 技術的貢献

### 双方向Formal-of-Thoughtアーキテクチャ

1. **トップダウン**: LLMが高レベル人間意図を原子的・検証可能な制約に分解（仕様コンパイラ）
2. **ボトムアップ**: Dafny仕様とZ3 SMTソルバーでコンプライアンスを証明

確率的スコアではなく**数学的保証**を生成。

## ベンチマーク評価

3ベンチマークで検証：
- 行動安全性
- マルチドメイン制約遵守
- エージェント欺瞞検出

## 主要結果

| 指標 | 結果 |
|------|------|
| LLM-as-a-Judge比 | 平均**+16.6%**改善 |
| 弱→強汎化 | 7Bジャッジが72Bエージェントの欺瞞を**90%超精度**で検出 |

反復的改良による準線形の安全性向上を実現。
