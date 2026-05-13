---
layout: paper
title: "Beyond GRPO and On-Policy Distillation: An Empirical Sparse-to-Dense Reward Principle"
date: 2026-05-14
category: cs.LG
arxiv_id: "2605.12483"
url: https://arxiv.org/abs/2605.12483
authors:
  - Yuanda Xu
  - Hejian Sang
  - Zhengze Zhou
tags: [GRPO, reinforcement-learning, reward, LLM, post-training, distillation]
---

# Beyond GRPO and On-Policy Distillation: An Empirical Sparse-to-Dense Reward Principle

## 概要

検証可能な学習データが制約となる設定で、各チェック済みサンプルの効率的な利用を最適化する研究。標準的手法はデプロイ学生モデルへの直接GRPO適用だが、**報酬密度原則**を見落としているとして批判。

- **疎な系列レベル報酬（GRPO）**: 探索が効果的な場所でのみ使う
- **密なトークンレベル教師報酬（蒸留）**: 小モデルへの圧縮に使う

この分業によりデータ効率を大幅改善するSparse-to-Dense Reward Principleを提案。

## 選定理由

- GRPO・RL後訓練という現在最重要のLLM研究トレンド
- 報酬設計の原則的理解に貢献
- 実用的なデータ効率改善手法

## キーポイント

- **課題**: GRPO直接適用は報酬密度の非効率を見逃す
- **原則**: 探索→GRPO、圧縮→蒸留の分業
- **効果**: 同じ検証済みデータで大幅な性能向上

## arXiv

https://arxiv.org/abs/2605.12483
