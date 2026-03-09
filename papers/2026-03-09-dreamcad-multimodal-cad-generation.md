---
layout: paper
title: "DreamCAD: Scaling Multi-modal CAD Generation using Differentiable Parametric Surfaces"
date: 2026-03-09
categories: [cs.CV, cs.AI]
arxiv_id: "2603.05607"
---

# DreamCAD: Scaling Multi-modal CAD Generation using Differentiable Parametric Surfaces

## 基本情報
- **arXiv ID**: 2603.05607
- **カテゴリ**: cs.CV, cs.AI
- **投稿日**: 2026-03-09
- **データセット公開予定**: CADCap-1M

## 著者
Mohammad Sadil Khan, Muhammad Usama, Rolandos Alexandros Potamias, Didier Stricker, Muhammad Zeshan Afzal, Jiankang Deng, Ismail Elezi

## 概要
CAD (Computer-Aided Design) は構造化された編集可能な幾何学表現に依存するが、既存の生成手法は明示的な設計履歴やBRep（境界表現）ラベルを持つ小規模なアノテーションデータセットに制約される。一方、数百万のアノテーションなし3Dメッシュは未活用のまま。

**DreamCAD**を提案：ポイントレベルの監督から直接編集可能なBRepを生成するマルチモダル生成フレームワーク（CAD固有のアノテーション不要）。

## 技術的詳細
各BRepをパラメトリックパッチ（例：Bézier曲面）のセットとして表現し、**微分可能テッセレーション手法**でメッシュを生成。これにより3Dデータセットでの大規模学習が可能になり、接続された編集可能な表面を再構成。

**CADCap-1M**を導入：
- **GPT-5を使用して生成**された100万件以上の説明
- text-to-CAD研究を推進する史上最大のCADキャプションデータセット

## 主要結果
ABCおよびObjaverseベンチマークでテキスト、画像、ポイントモダリティにわたり評価：
- 幾何学的忠実度を向上しつつSOTA性能を達成
- ユーザー選好で**75%超**を獲得

## 実用的意義
- 機械設計の自動化
- 3Dプリンティング向けモデル生成
- ゲーム・映画のアセット制作
- テキストからの直接CADモデル生成
- シミュレーション対応モデルの即時生成

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.05607
- コード・データセット: 公開予定
