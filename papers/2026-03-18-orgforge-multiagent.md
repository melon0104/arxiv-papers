---
layout: paper
title: "OrgForge: Multi-Agent Simulation for Synthetic Corporate Corpora"
date: 2026-03-18
arxiv_id: "2603.14997"
categories: ["cs.CL", "cs.AI", "cs.IR"]
importance: "★★★"
---

# OrgForge: A Multi-Agent Simulation Framework for Verifiable Synthetic Corporate Corpora

## 基本情報
- **arXiv ID**: 2603.14997
- **タイトル**: OrgForge: A Multi-Agent Simulation Framework for Verifiable Synthetic Corporate Corpora
- **著者**: Jeffrey Flynt et al.
- **投稿日**: 2026-03-16
- **分野**: cs.CL, cs.AI, cs.IR
- **ライセンス**: MIT License

## 概要
RAGパイプライン評価のための、検証可能なグラウンドトゥルース付き合成企業コーパス生成フレームワーク。Enronコーパスの法的曖昧性や人口偏りを解決。マルチエージェントシミュレーションで一貫性のあるSlack、JIRA、Confluence、Git、Emailを生成。

## 技術的貢献
- **物理-認知境界**: 決定論的Pythonエンジンが SimEvent グラウンドトゥルースバスを維持、LLMは検証済みプロポーザルに基づく表面文章のみ生成
- **アクターローカルクロック**: 全アーティファクトタイプで因果的タイムスタンプ正確性を強制、独立サンプリングによるタイムライン矛盾を排除
- **3つのグラフ動的サブシステム**:
  - 媒介中心性によるストレス伝播
  - 時間的エッジ重み減衰
  - Dijkstraエスカレーションルーティング

## 生成アーティファクト
- Slackスレッド、JIRAチケット、Confluenceページ、Git PR、Eメール
- すべて共有の不変イベントログにトレース可能

## 意義
RAG評価のためのクリーンなグラウンドトゥルース付きデータセット生成を可能に。LLMのハルシネーションによるドキュメント間矛盾を構造的に排除。
