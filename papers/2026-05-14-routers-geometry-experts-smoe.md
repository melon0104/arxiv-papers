---
layout: paper
title: "Routers Learn the Geometry of Their Experts: Geometric Coupling in Sparse Mixture-of-Experts"
date: 2026-05-14
category: cs.LG
arxiv_id: "2605.12476"
url: https://arxiv.org/abs/2605.12476
authors:
  - Sagi Ahrac
  - Noya Hochwald
  - Mor Geva
tags: [mixture-of-experts, routing, geometry, LLM, mechanistic-interpretability]
---

# Routers Learn the Geometry of Their Experts: Geometric Coupling in Sparse Mixture-of-Experts

## 概要

SMoE（Sparse Mixture-of-Experts）モデルのスケール効率的な訓練における課題—ルーティング崩壊と補助負荷バランス損失による専門化低下—をメカニスティックに解明。

あるトークンに対して、選択されたエキスパートのルーター重みとエキスパート重みは、スカラー係数の違いのみで**同一入力方向の勾配**を受け取るという**幾何的結合**を発見。つまりマッチしたルーター-エキスパートペアは自然に整合した表現を発達させる。

## 選定理由

- MoEアーキテクチャの理論的理解という重要論文
- ルーティング崩壊問題への新しい視点
- 効率的なLLMスケーリングへの直接的貢献

## キーポイント

- **発見**: ルーターとエキスパートは幾何的に結合した勾配を受け取る
- **意味**: マッチしたペアは自然に整合した表現空間を形成する
- **応用**: ルーティング崩壊の原因理解→改善手法の設計

## arXiv

https://arxiv.org/abs/2605.12476
