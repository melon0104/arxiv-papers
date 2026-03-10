---
layout: paper
title: "PostTrainBench: Can LLM Agents Automate LLM Post-Training?"
date: 2026-03-10
categories: [cs.CL, cs.LG]
arxiv_id: "2603.07652"
---

# PostTrainBench: Can LLM Agents Automate LLM Post-Training?

## 基本情報
- **arXiv ID**: 2603.07652
- **カテゴリ**: cs.CL, cs.LG
- **投稿日**: 2026-03-08

## 著者
Jinghan Zhang, Chen Huang, Thomas Scialom, David Grangier, Wenhu Chen, Siliang Tang, Yueting Zhuang

## 概要
LLMエージェントの進歩にもかかわらず、ポストトレーニング分野の研究開発自動化能力は未評価のまま。

**PostTrainBench**の提案：
- **96の実世界タスク**（SFT・RLHF設計/最適化/評価）
- **9つのコードエージェント**を評価
- 公開ソース（OpenHands/OpenManus）と商用（Claude Code with Opus 4.6、GPT-5.1）を含む
- 自動テスト環境とグラウンドトゥルース実行ログを完備

## 主要結果
- **GPT-5.1: 24.6%成功率**（商用最高）
- **Opus 4.6: 22.0%成功率**
- **OpenManus (DeepSeek V3): 18.3%成功率**
- 最高性能エージェントでも**過半数のタスクで失敗**

## エラー分析
1. 複雑なコードベースでの継続的メンテナンスに苦戦
2. 最先端・急速に進化するアルゴリズムの知識欠如
3. 長距離クロスファイル依存関係の困難さ
4. 訓練設定と評価パイプラインの複雑さ

## 発見されたギャップ
- ファイル修正は可能だが**一貫性維持**が困難
- 最新RLHFアルゴリズムへの適応に失敗
- 評価メトリクス設計での不正確さ

## 実用的意義
- LLMエージェントの現実的限界の定量化
- ポストトレーニング自動化の今後の課題特定
- 研究開発自動化の基準ベンチマーク

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.07652
