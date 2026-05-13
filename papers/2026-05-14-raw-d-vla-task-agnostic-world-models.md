---
layout: paper
title: "Reinforcing VLAs in Task-Agnostic World Models (RAW-D)"
date: 2026-05-14
category: cs.AI
arxiv_id: "2605.12334"
url: https://arxiv.org/abs/2605.12334
authors:
  - Yucen Wang
  - Rui Yu
  - Fengming Zhang
tags: [VLA, world-model, reinforcement-learning, robot-learning, zero-shot]
---

# Reinforcing VLAs in Task-Agnostic World Models (RAW-D)

## 概要

学習済みワールドモデルでのRLによるVLA後訓練という効果的戦略を発展させた研究。現行手法は想像軌跡でサンプル複雑度を下げるが、ワールドモデルと報酬モデルの両方のファインチューニングにタスク固有データへの強い依存があり、未見タスクへのスケーラビリティが根本的に制限される。

**RAW-D**は世界モデルと報酬モデルが転移可能な物理的事前知識を捉え、ゼロショット推論を可能にすることを提案。タスク非依存のワールドモデルでVLAを強化する。

## 選定理由

- VLA（視覚-言語-行動）モデルのロボット学習
- ゼロショット転移という実用性の高い課題
- 世界モデル×強化学習の先端研究

## キーポイント

- **課題**: タスク固有ファインチューニングが未見タスクへのスケールを妨げる
- **解決**: 転移可能な物理的事前知識をワールドモデルに組み込む
- **目標**: ゼロショットで新タスクに対応できるロバストなVLA

## arXiv

https://arxiv.org/abs/2605.12334
