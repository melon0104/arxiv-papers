---
layout: paper
title: "ACDC: Adaptive Curriculum Planning with Dynamic Contrastive Control for Goal-Conditioned Reinforcement Learning in Robotic Manipulation"
date: 2026-03-03
arxiv_id: "2603.02104"
arxiv_url: "https://arxiv.org/abs/2603.02104"
pdf_url: "https://arxiv.org/pdf/2603.02104"
authors: ["Xuerui Wang", "Guangyu Ren", "Tianhong Dai", "Bintao Hu", "Shuangyao Huang", "Wenzhang Zhang", "Hengyan Liu"]
categories: ["cs.RO", "cs.AI", "cs.LG"]
venue: "ICAPS 2026"
code_url: "https://github.com/Xuerui-Wang-oss/Adaptive-Curriculum-Learning-and-Dynamic-Contrastive-Control"
---

## 一言まとめ

**ICAPS 2026**: ロボットマニピュレーション向け目標条件付きRLで、人間の学習行動に着想を得た**適応的カリキュラム計画 + 動的コントラスト制御 (ACDC)**を提案。

## 概要

目標条件付き強化学習はロボットマニピュレーションで大きな可能性を示しているが、既存アプローチは収集済み経験の優先順位付けに依存し、多様なタスクで準最適な性能に留まる。

### 提案手法: ACDC

人間の学習行動に着想を得た、より包括的な学習パラダイム。

1. **Adaptive Curriculum (AC) Planning**: 多次元の適応的カリキュラム計画
2. **Dynamic Contrastive (DC) Control**: 動的コントラスト制御

### 技術的特徴

- エージェントを適切に設計された学習パスに沿ってガイド
- 経験の単純な優先順位付けを超えた、構造化された学習プロセス

### 実験結果

- 多様なロボットマニピュレーションタスクで検証
- 既存手法を上回る性能

## 所感

カリキュラム学習のロボティクス応用として興味深い。人間の学習プロセスを参考にした設計は直感的で説明しやすい。GitHub公開済みで再現・拡張が可能。
