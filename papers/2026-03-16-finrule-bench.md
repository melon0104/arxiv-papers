---
layout: paper
date: 2026-03-16
title: "FinRule-Bench: Joint Reasoning over Financial Tables and Principles"
arxiv_id: "2603.11339"
categories: [cs.AI, cs.CE, cs.LG]
---

# FinRule-Bench: Joint Reasoning over Financial Tables and Principles

## 基本情報
- **arXiv ID**: 2603.11339
- **カテゴリ**: cs.AI, cs.CE, cs.LG

## 概要
財務諸表に対するルールベース推論の診断的完全性を評価するベンチマーク。実際の財務諸表と人間がキュレーションした会計原則をペアリング。

## タスク設計
1. **ルール検証**: 単一原則への準拠テスト
2. **ルール識別**: 提供されたルールセットから違反原則を選択
3. **ジョイントルール診断**: レコードレベルで複数同時違反を検出・特定

## 主な成果
- 4種の標準財務諸表（貸借対照表、キャッシュフロー、損益、株主資本変動）を網羅
- 単一ルール検証は良好だが、**ルール識別・多重違反診断で急激に性能低下**
- 因果・反事実推論プロトコルで判断・説明・反事実判断の一貫性を強制

## 注目ポイント
- 財務分析AIの安全性・信頼性評価
- ルール統制推論の体系的テストベッド
- LLMの金融応用における限界を明確化
