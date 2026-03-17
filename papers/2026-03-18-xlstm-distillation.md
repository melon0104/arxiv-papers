---
layout: paper
title: "Effective Distillation to Hybrid xLSTM Architectures"
date: 2026-03-18
arxiv_id: "2603.15590"
categories: ["cs.LG"]
importance: "★★☆"
---

# Effective Distillation to Hybrid xLSTM Architectures

## 基本情報
- **arXiv ID**: 2603.15590
- **タイトル**: Effective Distillation to Hybrid xLSTM Architectures
- **著者**: Lukas Hauzenberger et al.
- **投稿日**: 2026-03-16
- **分野**: cs.LG

## 概要
二次複雑性のアテンションベースLLMを準二次的な線形化アーキテクチャ（xLSTM）に蒸留するパイプラインを提案。許容誤差補正済みWin-and-Tie率での「ロスレス蒸留」を目標。

## 技術的貢献
- **xLSTMベース蒸留**: 線形化アーキテクチャへの効果的な蒸留パイプライン
- **マージングステージ**: 個別に線形化されたエキスパートを単一モデルに統合
- **多ファミリー対応**: Llama、Qwen、Olmoのベースモデルと指示調整モデルの両方を蒸留

## 実験結果
- 多くの設定でxLSTMベースの生徒モデルが教師の性能の大部分を回復
- 一部の下流タスクでは教師を上回る性能
- エネルギー効率とコスト効率の向上を実現

## 意義
Transformerベース LLM の効率的な代替としてのxLSTMの可能性を実証。環境負荷の低減に貢献。
