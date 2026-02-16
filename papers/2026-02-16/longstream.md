---
layout: paper
title: "LongStream: Long-Sequence Streaming Autoregressive Visual Geometry"
date: 2026-02-17
arxiv_id: "2602.13172"
category: cs.CV
tags: [3d-reconstruction, autoregressive, streaming, slam]
---

# LongStream: Long-Sequence Streaming Autoregressive Visual Geometry

## 基本情報
- **arXiv**: [2602.13172](https://arxiv.org/abs/2602.13172)
- **プロジェクトページ**: [3dagentworld.github.io/longstream](https://3dagentworld.github.io/longstream/)
- **著者**: Chong Cheng, Xianda Chen, Tao Xie et al.

## 一言まとめ
数千フレームにわたるメトリックスケールの3D再構成を実現するストリーミング視覚幾何モデル。既存手法の長系列での失敗を解決。

## 課題
- 既存の自己回帰モデルは長系列で失敗
- 最初のフレームへのアンカリングが注意減衰、スケールドリフト、外挿エラーを引き起こす

## 提案手法: LongStream
### ゲージ分離型ストリーミングモデル
最初のフレームアンカーを廃止し、キーフレーム相対ポーズを予測

### 3つの主要技術
1. **キーフレーム相対ポーズ予測**
   - 長距離外挿を一定難度のローカルタスクに再定式化
   
2. **直交スケール学習**
   - 幾何とスケール推定を完全分離
   - ドリフトを抑制

3. **キャッシュ一貫学習 + 周期的キャッシュリフレッシュ**
   - Attention-sink依存と長期KVキャッシュ汚染を解決
   - 学習と推論のギャップを削減

## 実験結果
- **キロメートルスケールの系列で安定したメトリックスケール再構成**
- **18 FPS**でリアルタイム処理
- SOTA性能を達成

## キーポイント
- 長系列3D再構成の根本的な課題を解決
- 実用的な速度（18 FPS）
- キロメートルスケールへのスケーラビリティ
