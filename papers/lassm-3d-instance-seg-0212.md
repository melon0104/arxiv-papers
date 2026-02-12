---
layout: paper
title: "LaSSM: Efficient Semantic-Spatial Query Decoding for 3D Instance Segmentation"
arxiv_id: "2602.11007"
date: 2026-02-12
categories: [cs.CV]
conference: "IEEE-TCSVT"
github: "https://github.com/RayYoh/LaSSM"
---

# LaSSM: State Space Model for 3D Instance Segmentation

## 基本情報
- **arXiv**: [2602.11007](https://arxiv.org/abs/2602.11007)
- **カテゴリ**: cs.CV
- **著者**: Lei Yao et al.
- **採択**: IEEE-TCSVT
- **コード**: [GitHub](https://github.com/RayYoh/LaSSM)

## 概要

シンプルさと効率性を重視したクエリベース3Dシーンインスタンスセグメンテーション。計算集約的なアテンション機構を回避。

## 技術的貢献

### 階層的Semantic-Spatial Query Initializer
- スーパーポイントからセマンティック手がかりと空間分布を考慮してクエリセットを導出
- 包括的なシーンカバレッジと高速収束を実現

### Coordinate-Guided SSM Decoder
- **Local Aggregation Scheme**: 幾何的に一貫性のある領域に焦点
- **Spatial Dual-Path SSM Block**: 座標情報を統合してクエリセット内の依存関係を捕捉

## ScanNet++ V2リーダーボード

| 順位 | mAP改善 | FLOPs |
|------|--------|-------|
| **1位** | +2.5% | **1/3** |

## 他ベンチマーク

ScanNet, ScanNet200, S3DIS, ScanNet++ V1でも低計算コストで競争力のある性能を達成。
