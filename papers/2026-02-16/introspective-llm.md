---
layout: paper
title: "Introspective LLM: Learning Temperature Policy via Hierarchical RL"
date: 2026-02-17
arxiv_id: "2602.13035"
category: cs.CL
tags: [llm, reinforcement-learning, decoding, temperature, reasoning]
---

# Look Inward to Explore Outward: Learning Temperature Policy from LLM Internal States via Hierarchical RL

## 基本情報
- **arXiv**: [2602.13035](https://arxiv.org/abs/2602.13035)
- **著者**: Yixiao Zhou, Yang Li, Dongzhou Cheng, Hehe Fan, Yu Cheng

## 一言まとめ
LLMの隠れ状態から動的にサンプリング温度を制御することを学習する階層的強化学習フレームワーク。推論の不確実性に合わせた探索行動を実現。

## 課題
- サンプリング温度は探索-活用トレードオフを直接制御
- 既存手法は静的な値またはタスク報酬から切り離されたヒューリスティック適応に依存

## 提案手法: Introspective LLM
### 階層的RL
1. **温度選択**: 各デコードステップで隠れ状態に基づいて温度を選択
2. **トークンサンプリング**: 選択された温度分布から次トークンをサンプル

### 学習
- Coordinate Ascent方式で温度ポリシーとトークンポリシーを同時最適化
- 下流報酬から学習

## 実験結果
### 数学推論ベンチマーク
- 学習された温度ポリシーが固定・ヒューリスティックベースラインを上回る
- 推論の不確実性に整合した解釈可能な探索行動を示す

## キーポイント
- 温度をRLで学習するという新しいアプローチ
- LLMの内部状態を活用
- 推論タスクでの有効性を実証
