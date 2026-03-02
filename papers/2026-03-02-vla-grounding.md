---
layout: paper
title: "Robust Skills, Brittle Grounding: Diagnosing VLA Generalization"
date: 2026-03-02
arxiv_id: "2602.24143"
categories: [cs.RO]
---

# Robust Skills, Brittle Grounding: Diagnosing Restricted Generalization in Vision-Language Action Policies

## 基本情報
- **arXiv**: [2602.24143](https://arxiv.org/abs/2602.24143)
- **カテゴリ**: cs.RO

## 概要
Vision-Language Action（VLA）ポリシーは少数のデモンストレーションで高い操作ベンチマーク性能を報告するが、これがロバストな言語-オブジェクトグラウンディングか、訓練分布を超えない物体-位置相関への依存かは不明確。本研究では制御されたマルチオブジェクトピッキング研究を実施。

## 主要貢献
1. **段階的ストレステスト**: オブジェクト配置の変動を完全ワークスペースランダム化まで漸増
2. **ホールドアウト評価**: 慣れたペアリングを壊す物体-位置組み合わせ
3. **分解メトリクス**: プリミティブ実行と指示条件付き成功を分離測定

## 評価対象
- **SmolVLA**
- **π₀.₅**
- その他の代表的VLAポリシー

## 実験結果
- **操作プリミティブ実行**は指示条件付きタスク成功より安定
- 難しい設定で操作スキル獲得と指示追従が**分離**している
- スケーリングだけでは指示グラウンデッド汎化を達成しない

## 注目ポイント
🔍 **診断的評価**: VLAの汎化限界を明確化
⚠️ 操作スキルと言語グラウンディングの分離を発見
📊 ベンチマーク設計への具体的提言
