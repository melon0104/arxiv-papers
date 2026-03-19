---
layout: default
title: "DesertFormer: Transformer-Based Semantic Segmentation for Off-Road Desert Terrain"
---

# DesertFormer: Transformer-Based Semantic Segmentation for Off-Road Desert Terrain Classification in Autonomous Navigation Systems

[arXiv:2603.17056](https://arxiv.org/abs/2603.17056) | cs.CV

## 著者
Yasaswini Chebolu et al.

## 一言まとめ
オフロード砂漠地形の**セマンティックセグメンテーション**。SegFormer B2ベースで**mIoU 64.4%**、DeepLabV3 MobileNetV2比**+24.2%**改善。GitHub公開。

## 概要
信頼性の高い地形認識は非構造化オフロード環境での自律ナビゲーションの基本要件。砂漠景観は地形カテゴリ間の低色彩コントラスト、極端な照明変動、疎な植生により独自の課題を提示。DesertFormerはMiT-B2バックボーンを持つSegFormer B2ベースのセマンティックセグメンテーションパイプライン。10の生態学的意味カテゴリに分類。

## 注目ポイント
- **大幅改善**: ベースライン比+24.2% mIoU (41.0% → 64.4%)
- **10カテゴリ分類**: Trees, Lush Bushes, Dry Grass, Dry Bushes, Ground Clutter, Flowers, Logs, Rocks, Landscape, Sky
- **失敗分析**: Ground Clutter→Landscape、Dry Grass→Landscapeの混同パターンを特定
- **コード公開**: GitHub + インタラクティブ推論ダッシュボード

## 技術的詳細
- 4,176枚の注釈付きオフロード画像（512x512解像度）
- 階層的Mix Transformer (MiT-B2)バックボーン
- クラス重み付き訓練 + レアカテゴリ向けcopy-paste augmentation提案

## 関連リンク
- [arXiv](https://arxiv.org/abs/2603.17056)
- [PDF](https://arxiv.org/pdf/2603.17056)
- [GitHub](https://github.com/Yasaswini-ch/Vision-based-Desert-Terrain-Segmentation-using-SegFormer)
