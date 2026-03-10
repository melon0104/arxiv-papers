---
layout: paper
title: "How Far Can Unsupervised RLVR Scale LLM Training?"
date: 2026-03-10
categories: [cs.LG, cs.AI, cs.CL]
arxiv_id: "2603.08073"
conference: "ICLR 2026"
---

# How Far Can Unsupervised RLVR Scale LLM Training?

## 基本情報
- **arXiv ID**: 2603.08073
- **カテゴリ**: cs.LG, cs.AI, cs.CL
- **投稿日**: 2026-03-09
- **採択**: ICLR 2026

## 著者
Qiying Yu, Zheng Li, Yuqiang Xie, Hanbo Xie, Xiaotian Han, Yufei Wang, Luxi He, Wei Cheng, Haifeng Chen, Yongfeng Zhang

## 概要
強化学習と検証可能報酬 (RLVR) は、監視不要の推論モデルスケーリングに大きな可能性を示す。しかし高品質RL訓練データの確保が困難で、従来手法は人間アノテーション・モデル合成・ドメイン限定ソースに依存。

本研究では**教師なしRLVR**のスケーリングを調査し、以下の発見を報告：

**主要発見**：
1. **Web規模データ**は極めて高い訓練信号ノイズ比（SNR）
2. **ゼロショットクエリ抽出**は既存手法より優れたデータ品質
3. **タスク固有訓練データなし**で困難な推論タスクを大幅改善

## 手法
- **ゼロショットクエリ抽出パイプライン**
- **自己検証報酬信号**
- **教師なしでの推論能力獲得**

## 主要結果
- Webデータのみで**AIME24で7%向上**、MATH500で14%向上
- **LiveCodeBenchで10%以上向上**（タスク固有データなし）
- ドメイン転移性能の実証

## 技術的詳細
- 高ノイズWeb環境でのRL訓練シグナル抽出
- 検証可能報酬による自己監督
- スケーラブルな教師なし訓練パイプライン

## 実用的意義
- アノテーションコスト削減
- ドメイン非依存の推論改善
- 大規模LLM訓練の民主化

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.08073
