---
layout: default
title: ProRAG - Process-Supervised RL for RAG
---

# 🎯 ProRAG: プロセス監督型強化学習でRAGを最適化

**arXiv:** [2601.21912](https://arxiv.org/abs/2601.21912) | **GitHub公開**

## 概要

従来のRL-RAGは最終結果のみで報酬を与えるため、長いホライズンで「正解にたどり着いたが推論過程は間違っている」プロセス幻覚が発生。ステップレベルの監督を導入して解決。

## 問題: プロセス幻覚

- 正しい答えに到達しても、途中の推論ステップが間違っている
- スパースな報酬では、どのステップが問題かわからない
- 冗長な検索ステップも見逃される

## 提案手法: ProRAG

### Stage 1: Supervised Policy Warmup
- 構造化された推論フォーマットでモデルを初期化

### Stage 2: MCTS-based Process Reward Model (PRM)
- MCTSで中間推論品質を定量化
- ステップごとのスコアを学習

### Stage 3: PRM-Guided Reasoning Refinement
- 細粒度のプロセス選好でポリシーを調整

### Stage 4: Process-Supervised RL
- **デュアル粒度アドバンテージ機構**
- ステップレベル報酬 + グローバル結果信号を統合
- すべてのアクションに対して精密なフィードバック

## 実験結果

- **5つのマルチホップ推論ベンチマーク**で評価
- 結果ベース・プロセス考慮型のベースラインを上回る
- 特に複雑な長ホライズンタスクで効果大

## コード

**GitHub:** https://github.com/lilinwz/ProRAG

## ポイント

| 項目 | 内容 |
|------|------|
| 問題 | 結果OKでもプロセスが間違い |
| 解決 | ステップレベルのRL監督 |
| 技術 | MCTS-PRM + デュアル粒度報酬 |
| コード | GitHub公開 ✓ |

## 関連技術

- Retrieval-Augmented Generation
- Reinforcement Learning
- Process Reward Models

[← 一覧に戻る](../index)
