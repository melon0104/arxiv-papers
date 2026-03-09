---
layout: paper
title: "MAPO: Mixed Advantage Policy Optimization for Long-Horizon Multi-Turn Dialogue"
date: 2026-03-09
categories: [cs.CL]
arxiv_id: "2603.06194"
---

# MAPO: Mixed Advantage Policy Optimization for Long-Horizon Multi-Turn Dialogue

## 基本情報
- **arXiv ID**: 2603.06194
- **カテゴリ**: cs.CL (Computation and Language)
- **投稿日**: 2026-03-09

## 著者
（著者情報は本文参照）

## 概要
感情サポートなど**主観的マルチターン対話タスク**は、ユーザー状態の変化に適応し長期的なインタラクション品質を最適化する会話ポリシーを必要とする。しかし、このような設定でのRLは**信頼性のあるプロセス監督の欠如**により困難。

outcome-onlyトレーニングはターン間のクレジット割り当てを単一の軌跡レベル報酬に圧縮し、ナイーブなターンレベルグループサンプリングはインタラクティブ環境で法外なrolloutコストを招く。

## 技術的詳細
**MAPO**を提案：ジャッジモデルからの密なプロセスフィードバックを活用し、モンテカルロリターンで長期効果を伝播する批評家フリーの効率的RLアルゴリズム。

**Mixed Advantage Estimator**を導入：
- ターンレベル正規化とバッチレベル正規化を組み合わせ
- きめ細かくスケーラブルなクレジット割り当てを実現
- 最適化を安定化

## 主要結果
複数の主観的対話ベンチマーク（EMPA、EmoBench、EQ-Bench）、7B〜32Bのモデルスケールで評価：
- outcome-only GRPOと単一レベル正規化ベースラインに対し、学習安定性と最終性能を一貫して向上
- EMPAで**最大+9ポイント**の改善率、対話スコア7Bベースモデルから**+43.2**
- EMPA形式環境のみで学習しても未見の感情知能ベンチマークに汎化：EmoBench**+4ポイント**、EQ-Bench**+3.5ポイント**

## 実用的意義
- 感情サポートチャットボットの品質向上
- カウンセリング・メンタルヘルス支援AI
- 長期的関係構築を要する対話システム
- 主観的評価を要するオープンエンドマルチターン対話

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.06194
