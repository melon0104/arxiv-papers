---
layout: paper
title: "Agentic Critical Training (ACT) of Reinforcement Learning Agents"
date: 2026-03-10
categories: [cs.AI, cs.CL, cs.LG]
arxiv_id: "2603.08299"
---

# Agentic Critical Training (ACT) of Reinforcement Learning Agents

## 基本情報
- **arXiv ID**: 2603.08299
- **カテゴリ**: cs.AI, cs.CL, cs.LG
- **投稿日**: 2026-03-09

## 著者
Daniel Neider, Houssam Kanso, Andrei Paleyes, Ansgar Fehnker, Neil Lawrence

## 概要
RLベースのアプローチは、正確にタスクを完了する堅牢なエージェントの訓練に有効だが、テストタイム推論など通常人間の監督が必要な適応的決定を行うエージェントを生成するのに苦戦。本研究は、エージェントが環境条件を**クリティカルに分析**し、実行戦略を適応させ、複雑なタスクを確実に解決できるよう**Agentic Critical Training (ACT)** を開発。

**ACTの核心**：
1. **エージェント的クリティカル分析**: 環境状態の批判的評価
2. **適応的戦略選択**: 状況に応じた実行計画調整
3. **Test-time reasoning**: 人間監督なしでの推論時適応

## 技術的詳細
- RLと言語モデルの能力を統合
- クリティカルシンキングを訓練に組み込み
- 環境理解と適応的行動の両立

## 主要結果
- 複雑なタスクでの信頼性向上
- テストタイム適応能力の獲得
- 人間監督なしでの堅牢な意思決定

## 実用的意義
- LLMエージェントの自律性向上
- 動的環境での適応的行動
- エージェントシステムの信頼性強化

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.08299
