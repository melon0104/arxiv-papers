---
layout: paper
title: "SafeGen-LLM: Safety Generalization in Robotic Task Planning"
date: 2026-03-02
arxiv_id: "2602.24235"
categories: [cs.RO, cs.AI]
---

# SafeGen-LLM: Enhancing Safety Generalization in Task Planning for Robotic Systems

## 基本情報
- **arXiv**: [2602.24235](https://arxiv.org/abs/2602.24235)
- **カテゴリ**: cs.RO, cs.AI

## 概要
安全性クリティカルなロボットタスク計画は依然として困難。古典的プランナーはスケーラビリティに劣り、強化学習は汎化が弱く、ベースLLMは安全性を保証できない。本研究では安全性汎化可能なLLM **SafeGen-LLM**を提案。

## 主要貢献
1. **マルチドメインPDDL3ベンチマーク**: 明示的な安全制約付き
2. **2段階事後学習フレームワーク**:
   - **SFT**: 制約準拠計画データセットで計画構文・意味論を学習
   - **GRPO**: 形式検証からの報酬マシンでガイド、カリキュラム学習で複雑タスク対応
3. **Info-DPO**: 各中間ステップの情報利得を評価、より情報的な推論へ誘導

## 技術的特徴
- PDDL3（Planning Domain Definition Language 3）の安全制約を活用
- フロンティアプロプライエタリモデルを上回る
- 自然言語入力にも対応

## 実験結果
- 複数ドメインのタスクで強い安全性汎化
- 新規安全特性への汎化能力

## 注目ポイント
🤖 **ロボット安全計画**: 形式検証とLLMの融合
✅ 新規安全制約への汎化 - 未知の安全要件にも対応
🔬 PDDL3+自然言語の両入力フォーマット対応
