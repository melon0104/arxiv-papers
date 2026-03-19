---
layout: default
title: "Cascade-Aware Multi-Agent Routing: Spatio-Temporal Sidecars and Geometry-Switching"
---

# Cascade-Aware Multi-Agent Routing: Spatio-Temporal Sidecars and Geometry-Switching

[arXiv:2603.17112](https://arxiv.org/abs/2603.17112) | cs.AI

## 著者
Davide Di Gioia et al.

## 一言まとめ
高度AIシステムの**カスケード障害を幾何学認識で防止**。133パラメータのサイドカーで全体勝率+36.8pp、ツリー構造で+48~68pp改善。

## 概要
高度AI推論システムの一般的アーキテクチャパターンは、特化エージェント/モジュールを委任エッジで接続したシンボリックグラフネットワーク。現行スケジューラは負荷とフィットネスを最適化するが幾何学ブラインド：ツリー状vs.サイクリック構造で障害伝播が異なることをモデル化しない。本研究はこの可観測性ギャップを特定し、システムレベルコストを定量化し、軽量緩和策を提案。

## 注目ポイント
- **幾何学ギャップ特定**: ツリー状では単一障害が指数的カスケード、サイクリック密では自己制限
- **適応的切替**: 6トポロジー統計+3幾何学認識信号で切替判断
- **劇的改善**: Genesis 3ベンチマークでnon_tree勝率64-72%→92%
- **軽量**: わずか133パラメータのサイドカー

## 技術的詳細
- 時間インデックス実行グラフ上のルートリスク推定
- ユークリッド時空間伝播ベースライン
- 時間減衰付き双曲ルートリスクモデル（オプションでバースト励起）
- 構造特徴からの学習幾何学セレクタ（9→12→1 MLP）

## 関連リンク
- [arXiv](https://arxiv.org/abs/2603.17112)
- [PDF](https://arxiv.org/pdf/2603.17112)
