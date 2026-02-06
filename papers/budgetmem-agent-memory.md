---
layout: paper
title: "BudgetMem: クエリ認識型エージェントメモリ管理"
date: 2026-02-07
arxiv_id: "2602.06025"
categories: [cs.CL, cs.AI, Agent]
---

# BudgetMem: Learning Query-Aware Budget-Tier Routing for Runtime Agent Memory

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.06025
- **著者**: Haozhen Zhang, Haodong Yue, Tao Feng, **Jiaxuan You** 他
- **コード**: https://github.com/ViktorAxelsen/BudgetMem

## 概要
LLMエージェントのランタイムメモリフレームワーク。**クエリ認識型の性能-コストトレードオフ制御**を実現。

## 技術的ポイント
- **3段階予算ティア**: Low/Mid/Highの各メモリモジュール
- **軽量ルーター**: RL訓練されたニューラルポリシーでティア間をルーティング
- **3つの戦略軸**:
  - Implementation（手法の複雑さ）
  - Reasoning（推論動作）
  - Capacity（モジュールモデルサイズ）

## 実験結果
- LoCoMo、LongMemEval、HotpotQAで検証
- 高予算設定でベースラインを上回る性能
- タイト予算下でより良い精度-コストフロンティア

## 注目ポイント
- **コード公開済み**
- エージェントのメモリ効率化という実践的課題に取り組む
- 予算制約下での最適化手法を提供
