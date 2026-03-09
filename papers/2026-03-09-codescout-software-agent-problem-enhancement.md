---
layout: paper
title: "CodeScout: Contextual Problem Statement Enhancement for Software Agents"
date: 2026-03-09
categories: [cs.CL, cs.SE]
arxiv_id: "2603.05744"
---

# CodeScout: Contextual Problem Statement Enhancement for Software Agents

## 基本情報
- **arXiv ID**: 2603.05744
- **カテゴリ**: cs.CL, cs.SE
- **投稿日**: 2026-03-09

## 著者
Manan Suri, Xiangci Li, Mehdi Shojaie, Songyang Han, Chao-Chun Hsu, Shweta Garg, Aniket Anand Deshmukh, Varun Kumar

## 概要
現在のAI駆動コード支援ツールは、タスクコンテキストと要件仕様が不十分な**不明確な問題文**に苦戦することが多い。ソフトウェアエンジニアリングエージェントの最近の分析では、このような不十分な仕様のリクエストでの失敗は、**過剰探索や同じ修正の反復適用**を伴う長い軌跡と高い相関があることが判明。

**CodeScout**を提案：軽量な事前探索によりユーザーリクエストを包括的で実行可能な問題文に体系的に変換するコンテキスト的クエリ改善アプローチ。

## 技術的詳細
主要イノベーション：
- タスク実行前の**構造化分析**が既存のエージェント的能力を補強
- 基盤となるスキャフォールドの変更不要
- ターゲットコードベースの事前探索を実行
- 再現ステップ、期待動作、ターゲット探索ヒントを含む強化問題文を合成

## 主要結果
SWEBench-Verifiedで評価：
- 解決率を**20%向上**（最大27件の追加issue解決）
- デフォルトベースライン手法に対し一貫した改善

## 実用的意義
- 開発者の曖昧なバグレポートからの自動問題明確化
- ソフトウェアエージェントの効率性向上
- 非収束エージェント軌跡の削減
- コードレビュー・修正プロセスの高速化

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.05744
