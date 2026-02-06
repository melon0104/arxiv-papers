---
layout: paper
title: "XHugWBC: クロスエンボディメントヒューマノイド制御"
date: 2026-02-07
arxiv_id: "2602.05791"
categories: [cs.RO, Humanoid]
---

# XHugWBC: Scalable and General Whole-Body Control for Cross-Humanoid Locomotion

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.05791
- **著者**: Yufei Xue, YunFeng Lin, Wentao Dong, Yang Tang, **Jingbo Wang**, **Jiangmiao Pang**, Ming Zhou, Minghuan Liu, Weinan Zhang

## 概要
**単一ポリシーで多様なヒューマノイドロボット設計に汎化**する全身制御フレームワーク。1回の訓練で複数ロボットに適用可能。

## 技術的ポイント
- **物理整合的な形態ランダム化**: 多様な形態・動力学特性を学習
- **意味的に整列した観測・行動空間**: 異種ロボット間で統一
- **効果的なポリシーアーキテクチャ**: 形態・動力学特性をモデル化

## ゼロショット転移
訓練時に見ていないロボットへの即座の適用が可能:
- 新しい物体とのインタラクション等の新行動も組み込み可能

## 実験結果
- **12台のシミュレーションヒューマノイド**で検証
- **7台の実世界ロボット**で実証
- 強力な汎化性とロバスト性を確認

## 注目ポイント
- ヒューマノイド制御のスケーラブルなアプローチ
- ロボット固有の訓練が不要
- 実世界デプロイメントで有効性を実証
