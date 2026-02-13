---
layout: paper
title: "MTFM: Meituan基盤モデルによる大規模推薦システム"
---

# MTFM: A Scalable and Alignment-free Foundation Model for Industrial Recommendation in Meituan

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.11235
- **カテゴリ**: cs.IR
- **著者**: Xin Song, Zhilin Guan, Ruidong Han et al. (Meituan)
- **投稿日**: 2026-02-11

## 選定理由
✅ **実運用**: Meituanで本番運用中、オンライン実験で性能向上を実証

## 概要
産業用推薦システムは複数シナリオにまたがるが、既存のCDR/MSR手法はリソース制約と入力アライメント要件により拡張性に限界がある。本論文ではMTFM（Meituan Foundation Model for Recommendation）を提案。

## 技術的貢献
- **アライメント不要設計**: 入力を事前整列せず、異種トークンに変換してマルチシナリオ知識を捕捉
- **ユーザーレベルサンプル集約**: マルチシナリオのユーザーレベル集約により訓練スループット大幅向上
- **Grouped-Query Attention**: メモリ使用量と計算複雑性を削減
- **Hybrid Target Attention**: カスタム設計のアテンション機構
- **システムレベル最適化**: カーネル融合、CPU-GPUブロッキング排除で訓練・推論高速化

## 実験結果
- オフライン・オンライン両方で有効性を実証
- モデル容量とマルチシナリオ訓練データのスケーリングで大幅な性能向上

## 所感
Meituanの大規模推薦システムにおける基盤モデルの実践的アプローチ。アライメント不要設計は異種データ統合の現実的解決策として注目。
