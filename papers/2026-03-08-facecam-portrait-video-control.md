---
layout: paper
title: "FaceCam: Portrait Video Camera Control via Scale-Aware Conditioning"
date: 2026-03-08
categories: [cs.CV]
---

# FaceCam: Portrait Video Camera Control via Scale-Aware Conditioning

- **arXiv**: [2603.05506](https://arxiv.org/abs/2603.05506)
- **会議**: **CVPR 2026 採択**
- **著者**: Weijie Lyu et al.
- **プロジェクト**: https://weijielyu.github.io/FaceCam

## 概要

単眼ポートレート動画入力に対してカスタマイズ可能なカメラ軌道で動画を生成するシステム。スケール曖昧性や3D再構築エラーによる幾何学的歪みを解決。

## 主な貢献

1. **顔特化スケール認識表現**: 3Dプライアに依存しない決定論的カメラ変換条件付け
2. **合成カメラモーション**: 静止訓練カメラから動的・連続カメラ軌道へ一般化
3. **マルチショットスティッチング**: マルチビュースタジオ撮影とワイルド単眼動画の両方で訓練

## 実験結果

- Ava-256データセットと多様なワイルド動画で評価
- **カメラ制御性、視覚品質、アイデンティティ・モーション保存で優れた性能**

## 注目ポイント

- **CVPR 2026採択**
- ポートレート動画のカメラ制御という実用的課題
- スケール認識型の新しいアプローチ
