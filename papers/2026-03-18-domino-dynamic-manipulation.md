---
layout: paper
title: "DOMINO: Generalizable Dynamic Manipulation Dataset & PUMA VLA"
date: 2026-03-18
arxiv_id: "2603.15620"
categories: ["cs.CV", "cs.RO"]
importance: "★★★"
---

# DOMINO: Towards Generalizable Robotic Manipulation in Dynamic Environments

## 基本情報
- **arXiv ID**: 2603.15620
- **タイトル**: Towards Generalizable Robotic Manipulation in Dynamic Environments
- **著者**: Heng Fang et al.
- **投稿日**: 2026-03-16
- **分野**: cs.CV, cs.RO
- **コード**: https://github.com/H-EmbodVis/DOMINO

## 概要
VLAモデルが静的マニピュレーションには優れるが動的環境で苦戦する問題を解決。動的マニピュレーション用の大規模データセットDOMINOと、動的認識VLAアーキテクチャPUMAを提案。

## データセット: DOMINO
- **35タスク**: 階層的複雑性
- **110K+専門家軌跡**
- **多次元評価スイート**

## 技術的貢献: PUMA
- **シーン中心履歴オプティカルフロー**: 背景シーンの動きを統合
- **世界クエリ**: 物体中心の将来状態を暗黙的に予測
- **履歴認識知覚+短期予測**: 過去の認識と短期ホライズン予測を結合

## 実験結果
- ベースラインより成功率**+6.3%絶対改善**でSOTA達成
- 動的データでの訓練が頑健な時空間表現を育成
- 静的タスクにも転移可能

## 意義
動的環境でのVLA性能ギャップを埋める最初の大規模ベンチマーク。データとコードを公開。
