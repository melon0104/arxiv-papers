---
layout: paper
title: "AgentDisCo: Towards Disentanglement and Collaboration in Open-ended Deep Research Agents"
date: 2026-05-14
category: cs.IR
arxiv_id: "2605.11732"
url: https://arxiv.org/abs/2605.11732
authors:
  - Jiarui Jin
  - Zexuan Yan
  - Shijian Wang
tags: [deep-research, agent, information-retrieval, exploration-exploitation, adversarial]
---

# AgentDisCo: Towards Disentanglement and Collaboration in Open-ended Deep Research Agents

## 概要

Deep Researchエージェントを**情報探索（Exploration）と活用（Exploitation）の敵対的最適化問題**として定式化する新しいアーキテクチャ。既存手法がこの2プロセスを単一モジュールに混在させる問題を解消するため、AgentDisCoは役割を分離する：

- **Critic Agent**: 生成されたアウトラインを評価し、検索クエリを改良
- **Generator Agent**: 更新された結果を取得し、アウトラインを修正
- 反復的精緻化後、Report Writerが包括的な研究レポートを合成

## 選定理由

- Deep Research / エージェント型情報検索という注目トレンド
- 探索-活用のトレードオフを明示的に扱う理論的に興味深い手法
- cs.IR（情報検索）の中核トピック

## キーポイント

- **課題**: Deep Researchエージェントで探索と活用が混在し最適化が困難
- **手法**: Critic/Generator二エージェント構造による役割分離
- **メリット**: 反復精緻化により情報の網羅性と品質を向上

## arXiv

https://arxiv.org/abs/2605.11732
