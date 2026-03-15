---
layout: paper
date: 2026-03-16
title: "Shape-of-You: Fused Gromov-Wasserstein for Semantic Correspondence"
arxiv_id: "2603.11618"
categories: [cs.CV, cs.LG]
conference: "CVPR 2026"
---

# Shape-of-You: Fused Gromov-Wasserstein for Semantic Correspondence

## 基本情報
- **arXiv ID**: 2603.11618
- **カテゴリ**: cs.CV, cs.LG
- **採択会議**: CVPR 2026 🏆
- **コード**: Shape-of-You

## 概要
明示的な対応アノテーションなしでのセマンティック対応学習。従来の最近傍疑似ラベルの限界（局所的、幾何的曖昧さに弱い）を解決。

## 主な成果
- **Fused Gromov-Wasserstein (FGW)問題**として疑似ラベル生成を再定式化
- 特徴間類似性と構造内一貫性を同時最適化
- **SPair-71k, AP-10k**でSOTA達成
- 3D基盤モデルで幾何空間の構造を定義

## 技術的特徴
- アンカーベース線形化でFGWの計算コストを近似
- ソフトターゲットロスでノイズに対するロバスト性を確保
- 明示的な幾何アノテーション不要

## 注目ポイント
- 2D基盤モデル + 3D基盤モデルの融合
- 対称性・反復特徴による曖昧さを解決
- セマンティック対応の新たなベンチマーク
