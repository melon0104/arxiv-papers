---
layout: paper
title: "MoToRec: Sparse-Regularized Multimodal Tokenization for Cold-Start Recommendation"
arxiv_id: "2602.11062"
date: 2026-02-12
categories: [cs.LG, cs.IR]
conference: "AAAI 2026 (Main Track)"
---

# MoToRec: Multimodal Tokenization for Cold-Start

## 基本情報
- **arXiv**: [2602.11062](https://arxiv.org/abs/2602.11062)
- **カテゴリ**: cs.LG, cs.IR
- **著者**: Jialin Liu et al.
- **採択**: AAAI 2026 Main Track

## 概要

マルチモーダル推薦をディスクリート意味トークン化として再定式化。コールドスタート問題に対処するための新フレームワーク。

## 技術的貢献

### Sparse-Regularized RQ-VAE
- ディスエンタングルされた表現を促進
- 解釈可能なトークンからなる組成的意味コードを生成

### 3つの相乗的コンポーネント
1. **スパース正則化RQ-VAE**: ディスエンタングルド表現
2. **適応的希少性増幅**: コールドスタートアイテムの優先学習
3. **階層的マルチソースグラフエンコーダ**: 協調シグナルとのロバストな融合

## 性能

3つの大規模データセットで検証：
- 全体シナリオ・コールドスタートシナリオ両方でSOTA超え

## 意義

ディスクリートトークン化がコールドスタート課題緩和の効果的でスケーラブルな代替手法であることを検証。
