---
layout: paper
title: "FinTRACE: Financial Transaction Retrieval"
date: 2026-03-18
arxiv_id: "2603.15459"
categories: ["cs.IR"]
importance: "★★☆"
---

# FinTRACE: Financial Transaction Retrieval and Contextual Evidence for Knowledge-Grounded Reasoning

## 基本情報
- **arXiv ID**: 2603.15459
- **タイトル**: Financial Transaction Retrieval and Contextual Evidence for Knowledge-Grounded Reasoning
- **著者**: Maksim Makarenko et al.
- **投稿日**: 2026-03-16
- **分野**: cs.IR

## 概要
金融機関のトランザクション分析における汎用LLMの限界（時系列テーブルデータへの対応困難）を解決。検索ファーストアーキテクチャFinTRACEを提案。

## 技術的貢献
- **検索優先アーキテクチャ**: 生トランザクションを再利用可能な特徴表現に変換
- **ルールベース検出器**: 行動シグナルを抽出しタスク目標と段階的関連付け
- **行動知識ベース**: 検出シグナルを下流タスクの目標と関連付けて格納
- **LLMグラウンディング**: 検索した行動パターンに基づくインストラクションチューニング

## 実験結果
- **ゼロショットチャーン予測**: MCC 0.19→0.38（約2倍）
- **16-shot MCC**: 0.25→0.40
- トランザクション分析問題でSOTA LLM結果を達成

## 意義
ラベル付きデータ不要で低監視トランザクション分析を実現。専門的なテーブル/シーケンスモデルの転移性制限を克服。
