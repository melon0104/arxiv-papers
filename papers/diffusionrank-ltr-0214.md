---
layout: paper
title: "DiffusionRank: 拡散モデルによるLearning-to-Rank"
---

# From Noise to Order: Learning to Rank via Denoising Diffusion

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.11453
- **カテゴリ**: cs.IR, cs.AI, cs.LG
- **著者**: Bhaskar Mitra et al.
- **投稿日**: 2026-02-12

## 選定理由
✅ **有名研究機関**: Bhaskar Mitraはニューラル検索の第一人者

## 概要
情報検索のLearning-to-Rank（LTR）は従来、クエリ-文書ペアの特徴表現から関連性確率をモデル化する識別的アプローチが主流。本論文では、特徴ベクトルと関連性ラベルの同時分布をモデル化する生成的拡散ベースアプローチを提案。

## 技術的貢献
- **DiffusionRank**: TabDiffをベースに、表形式データ向け拡散モデルをLTRに拡張
- **生成的等価物**: 古典的なpointwiseおよびpairwise LTR目的関数の生成的バージョンを構築
- **仮説**: 生成的設定でデータ分布全体を説明できる解は、より頑健なランキングモデルを生成

## 実験結果
- DiffusionRankモデルは識別的対応モデルを一貫して大幅に上回る
- 深層生成モデリングのLTRへの応用可能性を実証

## 所感
拡散モデルをランキングに適用する斬新なアプローチ。生成的観点からのLTRは今後の研究領域として有望。
