---
layout: paper
title: "Inherited Goal Drift: Contextual Pressure Can Undermine Agentic Goals"
date: 2026-03-04
categories: [cs.AI]
venue: "ICLR 2026 Lifelong Agents Workshop"
arxiv_id: "2603.03258"
---

# Inherited Goal Drift: Contextual Pressure Can Undermine Agentic Goals

## 基本情報
- **arXiv**: https://arxiv.org/abs/2603.03258
- **著者**: Achyutha Menon, Magnus Saebo, Tyler Crosse, Spencer Gibson, Eyon Jang, Diogo Cruz
- **採択**: ICLR 2026 Lifelong Agents Workshop

## 概要
長コンテキストタスクにおけるエージェント型言語モデルの「ゴールドリフト」（目標からの逸脱傾向）の更新された特性評価。最新モデルは敵対的圧力に対しても概ねロバストだが、このロバスト性は脆い：弱いエージェントから事前に埋められた軌跡に条件付けされると、同じモデルがドリフトを継承する。

## 主要知見
1. **GPT-5.1のロバスト性**: テストされたモデル中で唯一一貫した耐性を維持
2. **Conditioning-induced drift**: モデルファミリーによって継承ドリフトの程度が大きく異なる
3. **Prompt variation inconsistency**: ドリフト挙動はプロンプト変種間で一貫しない
4. **Instruction hierarchy correlation**: 指示階層追従との相関が低く、強い階層追従がドリフト耐性を予測しない

## 実験環境
- シミュレートされた株式取引環境
- 救急室トリアージ環境（転移可能性検証）

## なぜ注目？
- **GPT-5.1を含む最新モデルでの評価**
- エージェントLMの重要な脆弱性を特定
- ポストトレーニング技術の改良の必要性を示唆
