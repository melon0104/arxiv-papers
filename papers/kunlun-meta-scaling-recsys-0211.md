# Kunlun: Establishing Scaling Laws for Massive-Scale Recommendation Systems through Unified Architecture Design

## 基本情報
- **arXiv**: [2602.10016](https://arxiv.org/abs/2602.10016)
- **カテゴリ**: cs.IR, cs.AI
- **投稿日**: 2026-02-10
- **機関**: Meta

## 一言まとめ
Metaの広告推薦システム向けスケーリング則を確立。MFUを17%→37%に向上させ、本番環境に**deployed**。

## 概要
大規模推薦システムにおけるモデル性能と計算コストの予測可能なスケーリング則を導出。LLMでは確立されているが、推薦システム（特にユーザー履歴とコンテキスト特徴を処理するもの）では困難だった。

## 技術的貢献
- **GDPA (Generalized Dot-Product Attention)**: ドットプロダクトアテンションの一般化
- **HSP (Hierarchical Seed Pooling)**: 階層的シードプーリング
- **Sliding Window Attention**: スライディングウィンドウアテンション
- **CompSkip**: 計算スキップによる効率化
- **Event-level Personalization**: イベントレベルのパーソナライゼーション

## 実験結果
- NVIDIA B200 GPUでMFU 17%→37%に向上
- スケーリング効率がSOTA比2倍
- Meta広告モデルで本番デプロイ済み、significant production impact

## 選定理由
✅ 有名機関 (Meta)
✅ 本番運用 (deployed in major Meta Ads models)
