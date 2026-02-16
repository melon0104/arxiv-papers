---
layout: paper
title: "SciAgentGym: Benchmarking Multi-Step Scientific Tool-use in LLM Agents"
date: 2026-02-17
arxiv_id: "2602.12984"
category: cs.CL
tags: [llm, agents, tool-use, benchmark, scientific-reasoning]
---

# SciAgentGym: Benchmarking Multi-Step Scientific Tool-use in LLM Agents

## 基本情報
- **arXiv**: [2602.12984](https://arxiv.org/abs/2602.12984)
- **著者**: Yujiong Shen, Yajie Yang, Zhiheng Xi et al.
- **機関**: Fudan University等

## 一言まとめ
科学推論における複雑なツール使用能力を評価するベンチマーク環境。4つの自然科学分野で1,780のドメイン特化ツールを提供。

## 課題
- 既存ベンチマークはエージェントの科学ワークフロー統合能力を評価せず
- 複雑なマルチステップツール使用の評価が不足

## 提案
### SciAgentGym
- **1,780のドメイン特化ツール**（4自然科学分野）
- 堅牢な実行インフラ

### SciAgentBench
- 基本操作から長期ワークフローまでの階層的評価スイート

### SciForge
- ツール行動空間を依存グラフとしてモデル化
- 論理認識型学習軌跡を生成

## 実験結果
- **GPT-5でも**: インタラクション長が伸びると成功率が60.6%→30.9%に低下
- **SciAgent-8B**: Qwen3-VL-235B-Instructを上回る性能
- 科学ツール使用能力の正の転移を確認

## キーポイント
- 科学推論×ツール使用の重要なボトルネックを特定
- マルチステップワークフロー実行が主な失敗要因
- 次世代自律科学エージェントへの道筋
