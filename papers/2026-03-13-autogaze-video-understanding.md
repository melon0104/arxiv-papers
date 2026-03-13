---
layout: paper
title: "AutoGaze: Efficient Video Understanding via Autoregressive Gazing"
date: 2026-03-13
arxiv_id: "2603.12254"
categories: [cs.CV]
---

# AutoGaze: Attend Before Attention

## 基本情報
- **arXiv ID**: 2603.12254
- **カテゴリ**: cs.CV（コンピュータビジョン）
- **投稿日**: 2026年3月12日
- **注目ポイント**: 🏆 **CVPR 2026採択**, 🏢 **NVIDIA/Berkeley** (Jan Kautz, Song Han, Trevor Darrell)

## 概要
長尺・高解像度動画における時空間冗長性を削減する軽量モジュール「AutoGaze」を提案。ViTやMLLMの処理前に冗長パッチを除去。

## 主要な貢献
1. **自己回帰パッチ選択**: 次トークン予測と強化学習で訓練
2. **マルチスケールパッチ**: ユーザー指定の誤差閾値内で動画再構成
3. **新ベンチマーク HLVid**: 初の高解像度長尺動画QA（5分4K動画）

## 驚異的な性能
| 指標 | 結果 |
|------|------|
| 視覚トークン削減 | 4x-100x |
| ViT/MLLM高速化 | 最大19x |
| VideoMME | 67.0% |
| 対応規模 | 1Kフレーム・4K解像度 |

## HLVidベンチマーク
- AutoGazeでスケールしたMLLM: ベースライン比+10.1%
- 前SOTAモデル比: +4.5%

## リンク
- [arXiv](https://arxiv.org/abs/2603.12254)
- [プロジェクトページ](https://autogaze.github.io/)
