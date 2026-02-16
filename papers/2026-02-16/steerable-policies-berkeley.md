---
layout: paper
title: "Steerable Policies: Vision-Language-Action Policies for Embodied Reasoning"
date: 2026-02-17
arxiv_id: "2602.13193"
category: cs.RO
tags: [robotics, vla, vlm, manipulation, berkeley]
---

# Steerable Vision-Language-Action Policies for Embodied Reasoning and Hierarchical Control

## 基本情報
- **arXiv**: [2602.13193](https://arxiv.org/abs/2602.13193)
- **プロジェクトページ**: [steerable-policies.github.io](https://steerable-policies.github.io)
- **著者**: William Chen, Jagdeep Singh Bhatia, Catherine Glossop, Nikhil Mathihalli, Ria Doshi, Andy Tang, Danny Driess, Karl Pertsch, **Sergey Levine**
- **機関**: UC Berkeley, Google DeepMind

## 一言まとめ
様々な抽象度レベルの合成コマンド（サブタスク、動作、ピクセル座標）で学習したVLAで、VLMの事前知識を引き出しタスク汎化を向上。

## 課題
- VLMの推論とVLAの低レベル動作のインターフェースは通常自然言語タスク指示
- VLM推論が低レベル動作をどれだけ誘導できるかが制限される

## 提案手法: Steerable Policies
### 様々な抽象度レベルのコマンドで学習
- サブタスク
- 動作
- グラウンドされたピクセル座標

### 低レベル制御可能性の向上
- VLMの事前学習済み知識を引き出す
- タスク汎化の改善

### 2つの制御方法
1. **学習された高レベル身体推論器**
2. **既製VLM + In-Context Learningによるコマンド抽象化推論**

## 実験結果
### 広範な実世界マニピュレーション実験
- 既存のEmbodied Reasoning VLAを上回る
- VLMベース階層ベースラインを上回る
- 挑戦的な汎化・長期タスクで有効

## キーポイント
- Sergey Levine (Berkeley)グループの最新研究
- VLMの知識をロボット制御に効果的に接続
- 実世界での広範な検証
