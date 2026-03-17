---
layout: paper
title: "OpenSeeker: Democratizing Frontier Search Agents"
date: 2026-03-18
arxiv_id: "2603.15594"
categories: ["cs.AI", "cs.CL"]
importance: "★★★"
---

# OpenSeeker: Democratizing Frontier Search Agents by Fully Open-Sourcing Training Data

## 基本情報
- **arXiv ID**: 2603.15594
- **タイトル**: OpenSeeker: Democratizing Frontier Search Agents by Fully Open-Sourcing Training Data
- **著者**: Rui Ye et al.
- **投稿日**: 2026-03-16
- **分野**: cs.AI, cs.CL
- **オープンソース**: モデル重み + 完全な訓練データセット

## 概要
高性能検索エージェントの開発が産業大手に独占されている問題を解決。初の完全オープンソース（モデル+データ）検索エージェントOpenSeekerを公開。

## 技術的貢献
1. **Fact-grounded Scalable Controllable QA Synthesis**:
   - ウェブグラフをトポロジカル展開とエンティティ難読化で逆工学
   - 制御可能なカバレッジと複雑性で複雑なマルチホップ推論タスクを生成
2. **Denoised Trajectory Synthesis**:
   - 回顧的要約メカニズムで軌跡をデノイズ
   - 教師LLMが高品質なアクションを生成

## 実験結果
- **わずか11.7K合成サンプル**で単一訓練実行
- **BrowseComp**: 29.5%（2位のDeepDive 15.3%を大幅に上回る）
- **BrowseComp-ZH**: 48.4%（Tongyi DeepResearchの46.7%を上回る）
- 単純なSFTのみで産業競合を凌駕

## 意義
フロンティア検索エージェント研究の民主化。完全なデータセットとモデルを公開し、透明で協力的なエコシステムを促進。
