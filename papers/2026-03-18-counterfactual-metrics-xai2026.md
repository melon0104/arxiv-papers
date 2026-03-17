---
layout: paper
title: "Counterfactual Explanation Metrics vs User Perception (XAI 2026)"
date: 2026-03-18
arxiv_id: "2603.15607"
categories: ["cs.AI", "cs.HC"]
importance: "★★☆"
---

# Do Metrics for Counterfactual Explanations Align with User Perception?

## 基本情報
- **arXiv ID**: 2603.15607
- **タイトル**: Do Metrics for Counterfactual Explanations Align with User Perception?
- **著者**: Felix Liedeker et al.
- **投稿日**: 2026-03-16
- **分野**: cs.AI, cs.HC
- **採択**: **4th World Conference on eXplainable Artificial Intelligence (XAI 2026)**

## 概要
反事実説明の評価に使用されるアルゴリズム評価指標が人間の判断と整合しているかを実証研究で検証。3つのデータセットで指標と人間評価を直接比較。

## 実験設定
- 参加者が複数の知覚品質次元で反事実説明を評価
- 標準的な反事実メトリクスの包括的セットと比較
- 個別関係とメトリクス組み合わせの予測力を分析

## 主要発見
- **弱い相関**: アルゴリズム指標と人間評価の相関は一般に弱い
- **データセット依存**: 相関はデータセットに強く依存
- **メトリクス数増加は無効**: 予測モデルで使用するメトリクス数を増やしても信頼性のある改善につながらない
- **構造的限界**: 現在のメトリクスが人間にとって重要な基準を捉えられていない

## 意義
広く使われている反事実評価指標がユーザーの説明品質認識の重要な側面を反映できていないことを実証。より人間中心のXAI評価アプローチの必要性を強調。
