---
layout: paper
title: "Mechanistic Origin of Moral Indifference in Language Models"
date: 2026-03-18
arxiv_id: "2603.15615"
categories: ["cs.CL", "cs.AI"]
importance: "★★★"
---

# Mechanistic Origin of Moral Indifference in Language Models

## 基本情報
- **arXiv ID**: 2603.15615
- **タイトル**: Mechanistic Origin of Moral Indifference in Language Models
- **著者**: Lingyu Li et al.
- **投稿日**: 2026-03-16
- **分野**: cs.CL, cs.AI

## 概要
LLMの表面的なコンプライアンスと内部の非整合表現との乖離を解明。プロトタイプ理論とSocial-Chemistry-101データセットを用いた251Kモラルベクトルを構築し、LLMの「道徳的無関心」状態を検証・改善。

## 技術的貢献
- **23モデル分析**: 現在のLLMは対立するモラルカテゴリの区別や、カテゴリ内の細粒度典型性グラデーションを表現できていない
- **スケーリング無効**: モデルサイズ拡大、アーキテクチャ変更、明示的アラインメントのいずれも道徳的無関心を改善しない
- **Sparse Autoencoders**: Qwen3-8Bでモノセマンティックなモラル特徴を分離
- **位相関係再構築**: グラウンドトゥルースのモラルベクトルに合わせて特徴の位相関係を整列

## 実験結果
- **Flamesベンチマーク**: 独立した敵対的ベンチマークで75%のペアワイズ勝率達成
- 表現レベルの整列が自然に道徳推論と粒度を改善

## 意義
現在のアラインメント手法の「事後修正」的性質を哲学的観点から批判し、「能動的育成」への変革を提唱。内因性のアラインドAIに向けた新方向を示唆。
