---
layout: paper
title: "GlyphPrinter: Glyph-Accurate Visual Text Rendering (CVPR 2026)"
date: 2026-03-18
arxiv_id: "2603.15616"
categories: ["cs.CV"]
importance: "★★★"
---

# GlyphPrinter: Region-Grouped Direct Preference Optimization for Glyph-Accurate Visual Text Rendering

## 基本情報
- **arXiv ID**: 2603.15616
- **タイトル**: GlyphPrinter: Region-Grouped Direct Preference Optimization for Glyph-Accurate Visual Text Rendering
- **著者**: Henghui Ding et al.
- **投稿日**: 2026-03-16
- **分野**: cs.CV
- **採択**: **CVPR 2026**
- **プロジェクトページ**: https://henghuiding.com/GlyphPrinter/

## 概要
視覚的テキストレンダリングにおける正確なグリフ生成の課題を解決。高品質シーンテキスト画像での訓練は限られたグリフバリエーションと過度のスタイル化で精度を損なう問題を、Direct Preference Optimization (DPO)で解決。

## 技術的貢献
- **Region-Grouped DPO (R-GDPO)**: 標準DPOの「全体嗜好」ではなく、領域レベルのグリフ嗜好アノテーションで最適化
- **GlyphCorrectorデータセット**: 領域レベルグリフ嗜好アノテーション付き
- **サンプル間・内嗜好**: アノテートされた領域に対する嗜好を最適化
- **Regional Reward Guidance**: 制御可能なグリフ精度で最適分布からサンプリングする推論戦略

## 実験結果
- グリフ精度で既存手法を上回る
- スタイル化と精度の好バランスを維持

## 意義
視覚的テキスト生成における「領域」の重要性を示し、細粒度制御を可能にする新パラダイムを提示。
