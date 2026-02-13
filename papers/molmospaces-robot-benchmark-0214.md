---
layout: paper
title: "MolmoSpaces: ロボットナビゲーション・操作のための大規模オープンエコシステム"
---

# MolmoSpaces: A Large-Scale Open Ecosystem for Robot Navigation and Manipulation

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.11337
- **カテゴリ**: cs.RO, cs.AI, cs.CV
- **著者**: Yejin Kim, Wilbert Pumacay, Dieter Fox, Ranjay Krishna et al.
- **投稿日**: 2026-02-11

## 選定理由
✅ **有名研究機関**: Dieter Fox (NVIDIA/UW)、Ranjay Krishna (Stanford→UW)
✅ **大規模オープンソース**: 23万環境、13万オブジェクト

## 概要
実環境のロボット展開には、シーンレイアウト、オブジェクト形状、タスク仕様の無数のバリエーションへの頑健性が必要。物理評価だけでは対応できないスケールと多様性を測定するインフラが必要。

## 技術的貢献
- **MolmoSpaces**: ロボットポリシーの大規模ベンチマーキングを支援する完全オープンエコシステム
- **規模**: 23万以上の多様な屋内環境、13万のリッチアノテーション付きオブジェクト
- **マニピュラブルオブジェクト**: 4.8万の操作可能オブジェクト、4,200万の安定把持
- **シミュレータ非依存**: MuJoCo、Isaac、ManiSkillをサポート

## MolmoSpaces-Bench
- 8タスクのベンチマークスイート
- 静的・モバイル操作、ナビゲーション、マルチルーム長期タスク
- Sim-to-real相関: R = 0.96, ρ = 0.98

## 実験結果
- 新しい強力なゼロショットポリシーが以前のバージョンを上回る
- プロンプト表現、初期関節位置、カメラオクルージョンへの感度を特定

## 所感
ロボット学習研究のスケーラブルなデータ生成、ポリシー訓練、ベンチマーク作成の基盤。高いsim-to-real相関が特に重要。
