---
layout: paper
title: "PRIMO R1: Process Reasoning for Robotic Manipulation"
date: 2026-03-18
arxiv_id: "2603.15600"
categories: ["cs.RO", "cs.AI", "cs.CL", "cs.CV"]
importance: "★★★"
---

# PRIMO R1: From Passive Observer to Active Critic

## 基本情報
- **arXiv ID**: 2603.15600
- **タイトル**: From Passive Observer to Active Critic: Reinforcement Learning Elicits Process Reasoning for Robotic Manipulation
- **著者**: Yibin Liu et al.
- **投稿日**: 2026-03-16
- **分野**: cs.RO, cs.AI, cs.CL, cs.CV

## 概要
長期ロボットマニピュレーションにおける正確なプロセス監視の課題を解決。SFTで訓練されたビデオMLLMが「受動的観察者」にとどまる問題を、強化学習で「能動的批評者」に変換するPRIMO R1を提案。

## 技術的貢献
- **結果ベース強化学習**: 進捗推定のための明示的なChain-of-Thought生成を誘発
- **構造化時間入力**: 初期状態と現在状態の画像間にビデオシーケンスを明示的にアンカー
- **PRIMO Dataset & Benchmark**: 多様な環境での評価リソース

## 実験結果
- **推論ベースライン比**: 平均絶対誤差 **50%削減**
- **72Bスケール汎用MLLM比**: 相対精度で大幅改善
- **RoboFailベンチマーク**: 67.0%精度でSOTA達成
- **OpenAI o1比**: +6.0%の改善
- ゼロショットでの失敗検出に強い汎化性能

## 意義
7Bモデルで72Bスケールモデルを凌駕する効率性を実証。ロボットプロセス監視における能動的推論の重要性を示す。
