---
layout: paper
title: "ChatShopBuddy: Towards Reliable Conversational Shopping Agents via Reinforcement Learning"
date: 2026-03-09
categories: [cs.IR]
arxiv_id: "2603.06065"
---

# ChatShopBuddy: Towards Reliable Conversational Shopping Agents via Reinforcement Learning

## 基本情報
- **arXiv ID**: 2603.06065
- **カテゴリ**: cs.IR (Information Retrieval)
- **投稿日**: 2026-03-09

## 著者
Yiruo Cheng, Kelong Mao, Tianhao Li, Jiejun Tan, Ji-Rong Wen, Zhicheng Dou

## 概要
会話型ショッピングエージェントはLLMベースエージェントの重要な消費者向けアプリケーションだが、ポストトレーニングRLの効果的な適用方法は未解明だった。本研究では、実世界シナリオにおけるRLベース最適化を調査し、**複数の相互依存する目標**（製品正確性、説得力、最終応答品質、ツール効率）を同時に満たす必要性を指摘。

主要貢献：
- **SmartShopBench**: 多様なショッピング意図をカバーし、階層的評価で複雑な品質要件を分解するベンチマーク
- **Hierarchical Reward Modeling (HRM)**: 混合報酬タイプを条件付きゲーティングで論理的依存関係を反映して構造化
- **Dynamic Contrastive Policy Optimization (DCPO)**: 動的軌跡選択により応答品質と運用効率をバランス

## 技術的詳細
- 報酬モデリングの階層化により、客観的メトリクス（製品正確性）、主観的品質（説得力）、結果報酬、プロセス報酬を統合
- DCPOは報酬と推論長に基づく動的軌跡選択で効率的な学習を実現
- 大規模モデルに依存しない汎用的な推論で多様な複雑度のクエリに対応

## 主要結果
- 汎用推論に依存する大規模モデルを一貫して上回る
- より高いピークではなく**優れた安定性**を達成
- 実世界の会話型エージェントへのRL適用のガイダンスを提供

## 実用的意義
- 対話型Eコマースシステムの信頼性向上
- マルチターン会話における品質と効率のトレードオフ最適化
- 産業応用可能な会話型エージェント設計指針

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.06065
