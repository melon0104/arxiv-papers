---
layout: paper
title: "GuidedVLA: Specifying Task-Relevant Factors via Plug-and-Play Action Attention Steering"
date: 2026-05-14
category: cs.RO
arxiv_id: "2605.12369"
url: https://arxiv.org/abs/2605.12369
authors:
  - Xiaosong Jia
  - Bowen Yang
  - Zuhao Ge
tags: [VLA, robot-learning, attention-steering, generalization, plug-and-play]
---

# GuidedVLA: Specifying Task-Relevant Factors via Plug-and-Play Action Attention Steering

## 概要

VLA（Vision-Language-Action）モデルがエンドツーエンドの教師あり学習のみでアクションデコードを学習する際、タスク関連特徴の明示的ガイダンスがなければ、視覚的ショートカットや環境ノイズなどの偽りの相関に過学習し汎化が制限される問題を解決。

GuidedVLAは、プラグアンドプレイ型のAction Attention Steeringフレームワークで、タスク関連要因を明示的に指定し、VLMの強力な視覚言語事前知識を効果的に活用する。

## 選定理由

- VLA（ロボット学習）の実用的課題への取り組み
- プラグアンドプレイという実装容易性
- 汎化問題への直接的なアプローチ

## キーポイント

- **課題**: 明示的ガイダンスなしだと視覚ショートカットに過学習
- **手法**: Action Attention Steeringでタスク関連要因を明示的指定
- **効果**: VLMの事前知識を活用した汎化能力向上

## arXiv

https://arxiv.org/abs/2605.12369
