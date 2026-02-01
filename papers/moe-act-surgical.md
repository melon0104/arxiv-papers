---
layout: default
title: MoE-ACT - Surgical Imitation Learning
---

# MoE-ACT: Improving Surgical Imitation Learning Policies through Supervised Mixture-of-Experts

**arXiv:** [2601.21971](https://arxiv.org/abs/2601.21971) | **カテゴリ:** cs.RO, cs.AI, cs.LG

## 概要

手術ロボットのためのMixture-of-Experts型模倣学習アーキテクチャ。フェーズ構造化された手術操作タスク向けに設計。**150件未満のデモンストレーション**から、ステレオ内視鏡画像のみで複雑な長時間操作を学習。

## 主要な貢献

1. **Supervised MoE**: 任意の自律ポリシーに追加可能
2. **少数デモ学習**: ACT（Action Chunking Transformer）ベースの軽量ポリシー
3. **腸管把持・牽引タスク**: 外科医の視覚的手がかりを解釈し、変形組織を把持・牽引

## 結果

- 汎用VLA（Vision-Language-Action）モデルは標準条件でもタスク習得に完全失敗
- MoE-ACTは分布内で高い成功率、分布外（新グラスプ位置、低照度、部分遮蔽）でも頑健
- **ex vivo豚組織へのゼロショット転移**成功
- **in vivo豚手術での予備結果**を提示

## 選定理由

✅ 手術ロボット×模倣学習の最前線 | ✅ in vivo実験

[← 戻る](/)
