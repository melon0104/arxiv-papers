---
layout: paper
title: "Controllable Reasoning Models Are Private Thinkers"
date: 2026-03-02
arxiv_id: "2602.24210"
categories: [cs.CL, cs.AI]
github: "https://github.com/UKPLab/arxiv2026-controllable-reasoning-models"
---

# Controllable Reasoning Models Are Private Thinkers

## 基本情報
- **arXiv**: [2602.24210](https://arxiv.org/abs/2602.24210)
- **カテゴリ**: cs.CL, cs.AI
- **コード**: [GitHub](https://github.com/UKPLab/arxiv2026-controllable-reasoning-models)

## 概要
推論モデルを搭載したAIエージェントはセンシティブなユーザーデータにアクセスする必要があるが、推論トレースは制御が難しく、外部へのプライバシー情報漏洩リスクがある。本研究では、最終回答だけでなく推論トレース内でも指示に従うようモデルを訓練する手法を提案。

## 主要貢献
1. **推論トレースの指示追従**: 異なる制約下で推論トレースと回答生成を分離
2. **新しいデータセット**: 推論トレースへの明示的制約を含む指示追従データセット
3. **分離LoRAアダプタ**: 推論と回答生成を別々のLoRAアダプタで実行

## 実験結果
- **1.7B〜14B**パラメータの6モデルで評価
- 指示追従: **最大+20.9ポイント**改善
- プライバシーベンチマーク: **最大+51.9%ポイント**改善

## 注目ポイント
🔒 **プライバシー保護**: 推論エージェントの情報漏洩リスク軽減
🧠 推論トレースレベルでの制御可能性を実現
⚖️ タスク有用性とのトレードオフを分析
