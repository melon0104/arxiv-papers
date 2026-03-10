---
layout: paper
title: "MetaWorld-X: Hierarchical World Modeling via VLM-Orchestrated Experts for Humanoid Loco-Manipulation"
date: 2026-03-10
categories: [cs.RO, cs.AI, cs.CV]
arxiv_id: "2603.07816"
---

# MetaWorld-X: Hierarchical World Modeling via VLM-Orchestrated Experts for Humanoid Loco-Manipulation

## 基本情報
- **arXiv ID**: 2603.07816
- **カテゴリ**: cs.RO, cs.AI, cs.CV
- **投稿日**: 2026-03-09

## 著者
Jialong Li, Tianyu Huang, Shengzhe Liu, Yingdong Hu, Jiangmiao Pang, Yang Gao

## 概要
ヒューマノイドロボットが複雑な環境で多様なタスクを実行するには、マルチモーダルな世界知覚と物理的な行動能力の**同時習得**が必要。これらの目標を単一の学習システムで統合するのは、知覚ベースと物理ベースのアプローチ間の根本的不一致により困難。

**MetaWorld-X**の提案：
- **VLM-オーケストレーション型エキスパート**による階層的ワールドモデリング
- 2レベルのシステム：
  1. **High-level VLM**: 状況分析とエキスパート選択（知覚レイヤー）
  2. **Low-level World Model Experts**: 物理ダイナミクスモデリング（物理レイヤー）

## 技術的詳細
- Vision-Language Modelによる高レベル推論
- ワールドモデルエキスパートの混合
- 移動（loco）と操作（manipulation）の統合

## 主要結果
- 複雑なloco-manipulationタスクで高い成功率
- ゼロショット転移能力の実証
- 効率的なエキスパート選択と切り替え

## 実用的意義
- 汎用ヒューマノイドロボット制御
- 複雑環境での自律行動
- シミュレーションから実機への転移

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.07816
