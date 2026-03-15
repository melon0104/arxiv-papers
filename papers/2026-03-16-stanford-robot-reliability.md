---
layout: paper
date: 2026-03-16
title: "Deployment-Time Reliability of Learned Robot Policies"
arxiv_id: "2603.11400"
categories: [cs.RO, cs.AI, cs.LG]
---

# Deployment-Time Reliability of Learned Robot Policies

## 基本情報
- **arXiv ID**: 2603.11400
- **カテゴリ**: cs.RO, cs.AI, cs.LG
- **出典**: Stanford University PhD Dissertation, 2026 🎓

## 概要
学習ベースロボットポリシーの展開時信頼性を向上させるための博士論文。分布シフト、エラー累積、複雑なタスク依存関係が実世界展開を妨げる問題に対処。

## 3つの展開時メカニズム
1. **ランタイム監視**: 閉ループポリシー行動の不整合やタスク進捗の逸脱を検出（失敗データ・タスク固有監視不要）
2. **データ中心の解釈可能性**: 影響関数を用いて展開時の成功・失敗を訓練デモに遡及
3. **長期タスク実行**: ポリシー協調を行動列の成功確率推定・最大化として定式化

## 注目ポイント
- 展開の核心課題に焦点を当てた実践的基盤
- フィージビリティ考慮型タスク計画への拡張
- 言語指定オープンエンドタスクにも対応
- 信頼性・スケーラブルなロボット自律の基礎
