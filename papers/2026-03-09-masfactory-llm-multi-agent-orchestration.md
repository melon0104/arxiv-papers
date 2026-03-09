---
layout: paper
title: "MASFactory: A Graph-centric Framework for Orchestrating LLM-Based Multi-Agent Systems with Vibe Graphing"
date: 2026-03-09
categories: [cs.CL, cs.AI, cs.MA]
arxiv_id: "2603.06007"
---

# MASFactory: A Graph-centric Framework for Orchestrating LLM-Based Multi-Agent Systems with Vibe Graphing

## 基本情報
- **arXiv ID**: 2603.06007
- **カテゴリ**: cs.CL, cs.AI, cs.MA
- **投稿日**: 2026-03-09
- **コード**: https://github.com/BUPT-GAMMA/MASFactory
- **動画**: https://youtu.be/ANynzVfY32k

## 著者
Yang Liu, Jinxuan Cai, Yishen Li, Qi Meng, Zedi Liu, Xin Li, Chen Qian, Chuan Shi, Cheng Yang

## 概要
LLMベースのマルチエージェントシステム（MAS）は、役割特化とコラボレーションによるエージェント的問題解決の拡張に活用されている。MASワークフローは**有向計算グラフ**として自然にモデル化でき、ノードはエージェント/サブワークフローを実行し、エッジは依存関係とメッセージパッシングをエンコード。

しかし、現在のフレームワークで複雑なグラフワークフローを実装するには依然として多大な手作業が必要で、再利用性が限られ、異種外部コンテキストソースの統合が困難。

## 技術的詳細
**MASFactory**を提案：LLMベースMASをオーケストレートするグラフ中心フレームワーク

**Vibe Graphing**を導入：human-in-the-loopアプローチ
1. 自然言語意図を編集可能なワークフロー仕様にコンパイル
2. 実行可能グラフに変換

追加機能：
- 再利用可能コンポーネントとプラガブルコンテキスト統合
- トポロジプレビュー、ランタイムトレーシング、human-in-the-loopインタラクション用ビジュアライザー

## 主要結果
7つの公開ベンチマークで評価：
- 代表的MAS手法の再現一貫性を検証
- Vibe Graphingの有効性を実証

## 実用的意義
- マルチエージェントシステムの迅速なプロトタイピング
- 複雑なAIワークフローの視覚的設計・デバッグ
- 既存MAS手法の統一的評価プラットフォーム
- 企業向けAIオーケストレーション

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.06007
- GitHub: https://github.com/BUPT-GAMMA/MASFactory
- YouTube: https://youtu.be/ANynzVfY32k
