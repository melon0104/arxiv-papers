---
layout: paper
title: "Context Forcing: 長コンテキスト一貫性のある動画生成"
date: 2026-02-07
arxiv_id: "2602.06028"
categories: [cs.CV, Video Generation]
---

# Context Forcing: Consistent Autoregressive Video Generation with Long Context

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.06028
- **著者**: Shuo Chen, Cong Wei, Sun Sun, Ping Nie, Kai Zhou, Ge Zhang, **Ming-Hsuan Yang**, **Wenhu Chen**
- **機関**: UC Merced, Waterloo

## 概要
長コンテキストの学生モデルを長コンテキストの教師で訓練する新フレームワーク。**student-teacher不一致問題**を解決し、20秒以上の一貫した動画生成を実現。

## 従来手法の問題
- ストリーミングチューニングは短コンテキスト（5秒）教師で長コンテキスト学生を訓練
- 教師が長期履歴にアクセスできないため、グローバルな時間依存性を指導できない

## 技術的ポイント
- **Slow-Fast Memory**: 線形成長するコンテキストを効率的に管理
- **視覚冗長性の削減**: 2分以上の極端な長さにも対応可能
- **監督不一致の排除**: 教師が完全な生成履歴を認識

## 実験結果
| 手法 | 有効コンテキスト長 |
|------|-------------------|
| LongLive | 2-10秒 |
| Infinite-RoPE | 2-10秒 |
| **Context Forcing** | **20秒以上** |

- SOTAベースラインを各種長動画評価指標で上回る

## 注目ポイント
- **Ming-Hsuan Yang（著名CV研究者）が共著**
- 長時間動画生成の新標準を確立
- 実用的なメモリ管理戦略を提供
