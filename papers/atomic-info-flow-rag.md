# Atomic Information Flow: A Network Flow Model for Tool Attributions in RAG Systems

- **arXiv**: [2602.04912](https://arxiv.org/abs/2602.04912)
- **カテゴリ**: cs.IR, cs.CL, cs.LG
- **投稿日**: 2026-02-04

## 概要

ツールベースRAGシステムにおいて、最終応答を特定のツールコンポーネントにトレースバックするグラフベースのネットワークフローモデル「Atomic Information Flow (AIF)」を提案。

## 主要な貢献

- **アトム分解**: ツール出力とLLM呼び出しを不可分な情報単位（アトム）に分解
- **フロー理論応用**: max-flow min-cut定理を活用したコンテキスト圧縮
- **軽量モデル学習**: Gemma3-4BをAIFシグナルでポストトレーニング

## 実験結果

- ベースGemma3-4B: HotpotQAで54.7%（BM25と同等）
- AIFポストトレーニング後: **82.71%** (+28.01ポイント)
- コンテキスト圧縮: **87.52%**
- Gemma3-27B（7倍大きいモデル）とほぼ同等の性能

## リンク

- [PDF](https://arxiv.org/pdf/2602.04912)
