---
layout: paper
title: "SearchGym: A Modular Infrastructure for Cross-Platform Benchmarking and Hybrid Search Orchestration"
date: 2026-03-06
categories: [cs.IR, cs.CL]
---

# SearchGym: A Modular Infrastructure for Cross-Platform Benchmarking and Hybrid Search Orchestration

**arXiv**: [2603.04402](https://arxiv.org/abs/2603.04402)

**著者**: Jerome Hsu et al.

**カテゴリ**: cs.IR, cs.CL

## 概要

RAG（Retrieval-Augmented Generation）の急速な成長に伴い、実験的プロトタイプと本番環境対応システムの間のギャップを埋めるモジュラーインフラストラクチャ「SearchGym」を提案。

## 主な貢献

- **モジュラー抽象化**: Dataset、VectorSet、Appというステートフルな抽象化によりデータ表現・埋め込み戦略・検索ロジックを分離
- **Compositional Config Algebra**: 階層的な設定から完全なシステムを合成可能で、完全な再現性を保証
- **Top-k Cognizance分析**: ハイブリッド検索パイプラインにおいて、セマンティックランキングと構造化フィルタリングの最適な順序がフィルタ強度に依存することを実証
- **LitSearchベンチマーク**: 専門家がアノテーションしたベンチマークで70%のTop-100検索率を達成

## コード

GitHub: https://github.com/JeromeTH/search-gym

## 注目ポイント

- RAGシステムの設計における汎用性と最適化可能性のトレードオフを明らかに
- オープンソース実装を公開
