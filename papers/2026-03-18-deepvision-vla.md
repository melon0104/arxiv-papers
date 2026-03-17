---
layout: paper
title: "DeepVision-VLA: Enhanced Vision for VLA Models"
date: 2026-03-18
arxiv_id: "2603.15618"
categories: ["cs.CV"]
importance: "★★★"
---

# Look Before Acting: Enhancing Vision Foundation Representations for Vision-Language-Action Models

## 基本情報
- **arXiv ID**: 2603.15618
- **タイトル**: Look Before Acting: Enhancing Vision Foundation Representations for Vision-Language-Action Models
- **著者**: Yulin Luo, Hao Chen, et al.
- **投稿日**: 2026-03-16
- **分野**: cs.CV

## 概要
VLAモデルにおける視覚情報の行動生成への統合を体系的に分析。深い層で視覚トークンへの感度が低下することを発見し、この問題を解決するDeepVision-VLAを提案。

## 技術的発見
- 複数のVLAモデル・行動生成パラダイムを分析
- 行動生成時、深い層で視覚トークンへの感度が進行的に低下

## 技術的貢献: DeepVision-VLA
- **Vision-Language Mixture-of-Transformers (VL-MoT)**: ビジョン基盤モデルとVLAバックボーン間の共有アテンション
- **マルチレベル視覚特徴注入**: ビジョンエキスパートからVLAバックボーンの深い層へ
- **Action-Guided Visual Pruning (AGVP)**: 浅い層アテンションで無関係な視覚トークンを刈り込み、タスク関連トークンを保持

## 実験結果
- シミュレーションタスク: 先行SOTA比 **+9.0%**
- 実世界タスク: **+7.5%**
- 最小限の計算オーバーヘッドで重要な視覚キューを強化

## 意義
VLAモデルの視覚強化設計に新しい知見を提供。「行動前に見る」原則の重要性を実証。
