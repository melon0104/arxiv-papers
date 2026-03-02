---
layout: paper
title: "CUDA Agent: Agentic RL for High-Performance CUDA Kernel Generation"
date: 2026-03-02
arxiv_id: "2602.24286"
categories: [cs.LG, cs.AI]
---

# CUDA Agent: Large-Scale Agentic RL for High-Performance CUDA Kernel Generation

## 基本情報
- **arXiv**: [2602.24286](https://arxiv.org/abs/2602.24286)
- **カテゴリ**: cs.LG, cs.AI

## 概要
GPUカーネル最適化はディープラーニングの基盤だが、深いハードウェア専門知識が必要。LLMは一般的プログラミングでは強力だが、CUDAカーネル生成ではtorch.compileなどのコンパイラベースシステムに及ばない。本研究では大規模エージェント強化学習システム**CUDA Agent**を提案。

## 主要貢献
1. **スケーラブルなデータ合成パイプライン**
2. **スキル拡張CUDA開発環境**: 自動検証・プロファイリングで信頼性の高い報酬信号
3. **安定した訓練を可能にする強化学習アルゴリズム技術**

## 実験結果
- **KernelBench Level-1**: torch.compileより**100%高速**
- **KernelBench Level-2**: torch.compileより**100%高速**
- **KernelBench Level-3**: torch.compileより**92%高速**
- **Claude Opus 4.5やGemini 3 Proを約40%上回る**（最難Level-3で）

## 注目ポイント
🚀 **SOTA達成**: 最新プロプライエタリモデルを大幅に上回る
🎯 GPUカーネル最適化という実用的な難題に取り組む
🔬 強化学習でコード生成能力を本質的に向上
