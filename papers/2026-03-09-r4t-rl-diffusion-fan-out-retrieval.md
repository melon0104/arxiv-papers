---
layout: paper
title: "R4T: Efficient, Property-Aligned Fan-Out Retrieval via RL-Compiled Diffusion"
date: 2026-03-09
categories: [cs.IR, cs.LG]
arxiv_id: "2603.06397"
---

# R4T: Efficient, Property-Aligned Fan-Out Retrieval via RL-Compiled Diffusion

## 基本情報
- **arXiv ID**: 2603.06397
- **カテゴリ**: cs.IR, cs.LG
- **投稿日**: 2026-03-09
- **所属**: Google（著者にGoogleの研究者含む）

## 著者
Pengcheng Jiang, Judith Yue Li, Moonkyung Ryu, R. Lily Hu, Kun Su, Zhong Yi Wan, Liam Hebert, Hao Peng, Jiawei Han, Dima Kuzmin, Craig Boutilier

## 概要
現代の検索問題の多くは**セット値問題**：広い意図に対し、**高次特性**（多様性、カバレッジ、相補性、一貫性）を最適化する結果コレクションを返す必要がある。セット値目標は通常非分解可能で、top-1検索のみを優先する既存の教師あり（query, content）データセットでは捕捉できない。

**R4T (Retrieve-for-Train)** を提案：RLを**目標変換器**として一度だけ使用する3段階プロセス
1. 複合セットレベル報酬でfan-out LLMを訓練
2. 目標整合訓練ペアを合成
3. 軽量拡散検索器を訓練してセット値出力の条件付き分布をモデル化

## 技術的詳細
- Fan-outをembedding空間で効率的な単一パスで実現
- 大規模ファッション・音楽ベンチマーク（キュレートされたアイテムセット）で評価
- RLで学習したセットレベル報酬を拡散モデルに蒸留

## 主要結果
- 強力なベースラインに対し検索品質を向上
- クエリ時のfan-outレイテンシを**桁違いに削減**
- セットレベルの特性（多様性、カバレッジ等）を維持

## 実用的意義
- ファッション推薦での「コーディネート提案」
- 音楽プレイリスト生成
- 相補的アイテムセットの効率的検索
- Eコマース・コンテンツプラットフォームでのセット推薦

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.06397
