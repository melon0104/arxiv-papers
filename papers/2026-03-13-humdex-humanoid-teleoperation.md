---
layout: paper
title: "HumDex: Humanoid Dexterous Manipulation Made Easy"
date: 2026-03-13
arxiv_id: "2603.12260"
categories: [cs.RO]
---

# HumDex: Humanoid Teleoperation System

## 基本情報
- **arXiv ID**: 2603.12260
- **カテゴリ**: cs.RO（ロボティクス）
- **投稿日**: 2026年3月12日
- **注目ポイント**: 📂 **GitHub完全公開**

## 概要
ヒューマノイド全身器用操作のためのポータブルテレオペレーションシステム「HumDex」を提案。既存システムの可搬性・オクルージョン・精度の課題を解決。

## 技術的特徴
1. **IMUベースモーショントラッキング**: 可搬性と精度のトレードオフを解消
2. **学習ベースリターゲティング**: スムーズで自然なハンドモーションを生成、手動パラメータ調整不要

## 2段階模倣学習フレームワーク
1. **事前学習**: 多様な人間動作データで汎化可能な事前分布を学習
2. **ファインチューニング**: ロボットデータでエンボディメントギャップを橋渡し

## 汎化性能
最小限のデータ取得コストで新しい構成、物体、背景への汎化を大幅改善。

## 完全再現可能
システム全体がオープンソースで公開。

## リンク
- [arXiv](https://arxiv.org/abs/2603.12260)
- [GitHub](https://github.com/physical-superintelligence-lab/HumDex)
