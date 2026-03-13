---
layout: paper
title: "Video Streaming Thinking: Watch and Think Simultaneously"
date: 2026-03-13
arxiv_id: "2603.12262"
categories: [cs.CV]
---

# VST: Video Streaming Thinking

## 基本情報
- **arXiv ID**: 2603.12262
- **カテゴリ**: cs.CV（コンピュータビジョン）
- **投稿日**: 2026年3月12日

## 概要
オンラインVideoLLMは既存手法ではストリーミング知覚に焦点を当て、同期された論理推論ストリームが欠落。テスト時スケーリング手法は応答遅延が許容不可。この課題を解決する「Video Streaming Thinking (VST)」を提案。

## "Thinking while Watching"
- ストリーミング中に入ってくる動画クリップ上で推論を活性化
- LLM推論遅延を動画再生時間にわたって償却し、リアルタイム応答性を維持

## 訓練パイプライン
1. **VST-SFT**: オフラインVideoLLMを因果的ストリーミング推論に構造適応
2. **VST-RL**: マルチターン動画対話環境での自己探索によるE2E改善
3. **自動データ合成**: 動画知識グラフを使用した高品質ストリーミングQA生成

## 性能
| ベンチマーク | VST-7B |
|--------------|--------|
| StreamingBench | 79.5% |
| OVO-Bench | 59.3% |
| vs Video-R1 応答速度 | 15.7x高速 |
| vs Video-R1 VideoHolmes | +5.4% |

## リンク
- [arXiv](https://arxiv.org/abs/2603.12262)
- [GitHub](https://github.com/1ranGuan/VST)
