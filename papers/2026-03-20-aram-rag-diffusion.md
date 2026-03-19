---
layout: default
title: "ARAM: Adaptive Guidance for Retrieval-Augmented Masked Diffusion Models"
---

# ARAM: Adaptive Guidance for Retrieval-Augmented Masked Diffusion Models

[arXiv:2603.17677](https://arxiv.org/abs/2603.17677) | cs.CL

## 著者
Jong Chul Ye et al.

## 一言まとめ
拡散ベース言語モデルにおける**検索先行コンフリクト問題**を解決。SNRベースの適応的ガイダンスでRAG品質を向上。

## 概要
RAGは外部知識を組み込むことで事実的グラウンディングを改善するが、検索コンテキストがノイジーだったりモデルのパラメトリック知識と矛盾する場合、生成品質が劣化する。この問題は自己回帰モデルでは研究されてきたが、反復的デノイジングを行う拡散ベース言語モデルでは未探索。ARAMは訓練不要の適応的ガイダンスフレームワークを提案。

## 注目ポイント
- **訓練不要**: 追加学習なしで既存MDMに適用可能
- **SNRベース適応**: 検索コンテキストの分布シフトに応じてガイダンス強度を動的調整
- **競合ベースライン超え**: 複数の知識集約型QAベンチマークで性能向上
- **直感的動作**: 信頼できる修正エビデンス時は強化、ノイジー時は抑制

## 技術的詳細
- Masked Diffusion Models (MDM) のRAG設定に特化
- デノイジング中にSNRに応じてガイダンススケールを動的較正
- コンテキスト信号が非支持的な場合は自動的に抑制

## 関連リンク
- [arXiv](https://arxiv.org/abs/2603.17677)
- [PDF](https://arxiv.org/pdf/2603.17677)
