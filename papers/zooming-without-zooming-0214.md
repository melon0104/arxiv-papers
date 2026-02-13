---
layout: paper
title: "Zooming without Zooming: 領域-画像蒸留によるきめ細かい知覚"
---

# Zooming without Zooming: Region-to-Image Distillation for Fine-Grained Multimodal Perception

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.11858
- **カテゴリ**: cs.CV, cs.AI, cs.CL, cs.LG
- **著者**: Lai Wei, Liangbo He et al.
- **投稿日**: 2026-02-12
- **GitHub**: https://github.com/inclusionAI/Zooming-without-Zooming

## 選定理由
✅ **コード公開**: GitHubでコード公開
✅ **新ベンチマーク**: ZoomBench（845 VQAデータ、6次元評価）

## 概要
MLLMsは広範な視覚理解に優れるが、きめ細かい知覚では依然として苦労。決定的な証拠が小さく、グローバルコンテキストに埋もれやすい。最近の「Thinking-with-Images」手法は推論時に関心領域をズームイン/アウトするが、ツール呼び出しと視覚再エンコードの繰り返しにより高レイテンシ。

## 技術的貢献
- **Region-to-Image Distillation**: ズームを推論時ツールから訓練時プリミティブに変換
- **マイクロクロップ領域**: 強力な教師モデルが高品質VQAデータを生成
- **領域グラウンド監督**: 生成されたデータをフル画像に蒸留
- **ZoomBench**: 6つのきめ細かい知覚次元にわたる845 VQAデータ、デュアルビュープロトコル

## 実験結果
- 複数のきめ細かい知覚ベンチマークで最先端性能
- 視覚推論やGUIエージェントなど一般的なマルチモーダル認知も改善
- ツール使用なしで「シングルグランス」きめ細かい知覚を実現

## 所感
エージェント的ズームの利点を単一フォワードパスに内部化する効率的なアプローチ。推論時コスト削減と精度向上の両立が魅力。
