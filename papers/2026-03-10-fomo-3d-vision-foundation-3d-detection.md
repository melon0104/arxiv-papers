---
layout: paper
title: "FOMO-3D: Using Vision Foundation Models for Long-Tailed 3D Detection"
date: 2026-03-10
categories: [cs.CV, cs.AI, cs.LG, cs.RO]
arxiv_id: "2603.07834"
conference: "CoRL 2025"
---

# FOMO-3D: Using Vision Foundation Models for Long-Tailed 3D Detection

## 基本情報
- **arXiv ID**: 2603.07834
- **カテゴリ**: cs.CV, cs.AI, cs.LG, cs.RO
- **投稿日**: 2026-03-09
- **採択**: CoRL 2025
- **所属**: Waabi（Raquel Urtasun 研究グループ）

## 著者
Ivan Googchak, Sandeep Lal, Xiran Cai, Mikita Sazanovich, Raquel Urtasun

## 概要
オブジェクト検出モデルの訓練は伝統的に**大規模ラベル付きデータセット**を必要とし、効果的なデータキュレーションを要求。視覚基盤モデル (Vision Foundation Models) は膨大なデータから豊富なオープン語彙特徴を学習。しかしLiDAR点群など異種モダリティへの転移方法は未解明。

**FOMO-3D**の提案：
- **Pre-trained VFM特徴をLiDAR 3D検出器に注入**
- **Few-shot・ゼロショット学習**で稀少オブジェクト検出を大幅改善
- **Open-vocabulary検出能力**の獲得

## 技術的詳細
- VFM → LiDAR特徴へのクロスモーダル転移
- ロングテール分布での性能保証
- オープン語彙・ゼロショット設定のサポート

## 主要結果
- ベースラインを4.8 APポイント上回る
- **Eaton Centre (実世界) での6倍AP向上**
- ゼロショット設定でも強力な性能
- 稀少クラス（工事車両、緊急車両等）の検出改善

## 実用的意義
- 自動運転のロングテール安全性向上
- アノテーションコスト削減
- 稀少シナリオへの対応能力

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.07834
