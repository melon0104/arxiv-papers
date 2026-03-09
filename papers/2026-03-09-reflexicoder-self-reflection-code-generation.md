---
layout: paper
title: "ReflexiCoder: Teaching Large Language Models to Self-Reflect on Generated Code and Self-Correct It via Reinforcement Learning"
date: 2026-03-09
categories: [cs.CL, cs.LG, cs.SE]
arxiv_id: "2603.05863"
---

# ReflexiCoder: Teaching Large Language Models to Self-Reflect on Generated Code and Self-Correct It via Reinforcement Learning

## 基本情報
- **arXiv ID**: 2603.05863
- **カテゴリ**: cs.CL, cs.LG, cs.SE
- **投稿日**: 2026-03-09
- **コード**: https://github.com/juyongjiang/ReflexiCoder

## 著者
Juyong Jiang, Jiasi Shen, Sunghun Kim, Kang Min Yoo, Jeonghoon Kim, Sungju Kim

## 概要
LLMはコード生成に革命をもたらしたが、標準的な「System 1」アプローチ（単一フォワードパスでソリューション生成）は複雑なアルゴリズムタスクで性能上限に達することが多い。既存の反復的改善戦略は外部オラクル、実行フィードバック、または計算コストの高いプロンプト-応答サイクルに依存。

**ReflexiCoder**を提案：初期生成→バグ・最適化認識リフレクション→自己修正の構造化推論軌跡をモデルの重みに直接内部化する新しいRLフレームワーク。

主要特徴：
- 外部依存の改善から**完全自律的な自己反省・自己修正**能力への推論時パラダイムシフト
- RL-zeroトレーニングパラダイムと粒度の細かい報酬関数で反省-修正軌跡全体を最適化
- ground-truthフィードバックや実行エンジンへの依存なしにデバッグ方法を学習

## 主要結果
7つのベンチマークで評価、**ReflexiCoder-8B**が1.5B-14B範囲のオープンソースモデルで新SOTA達成：
- HumanEval: 94.51% (Plus: 87.20%)
- MBPP: 81.80% (Plus: 78.57%)
- BigCodeBench: 35.00%
- LiveCodeBench: 52.21%
- CodeForces: 37.34%
- **GPT-5.1に匹敵または上回る**（単一試行設定）

## 効率性
- 規律正しく高速な推論・反省パターンにより、ベースモデルより**約40%トークン効率向上**

## 実用的意義
- コード生成の自動品質向上
- 開発者支援ツールの高度化
- オープンソースモデルでのプロプライエタリモデル級性能実現

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.05863
- GitHub: https://github.com/juyongjiang/ReflexiCoder
