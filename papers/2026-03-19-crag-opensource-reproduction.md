---
layout: paper
title: "Open-Source Reproduction of Corrective RAG"
date: 2026-03-19
arxiv_id: "2603.16169"
categories: ["cs.IR", "cs.AI", "cs.CL"]
---

# Open-Source Reproduction and Explainability Analysis of Corrective Retrieval Augmented Generation

## 基本情報

| 項目 | 内容 |
|------|------|
| arXiv | [2603.16169](https://arxiv.org/abs/2603.16169) |
| GitHub | https://github.com/suryayalavarthi/crag-reproduction |
| 評価データ | PopQA, ARC-Challenge |

## 概要

CRAG（Corrective Retrieval Augmented Generation）の**完全オープンソース再現**と、T5ベース検索評価器の初めての**説明可能性分析**。

## 問題設定

- 元のCRAG実装はプロプライエタリコンポーネントに依存
  - Google Search API
  - クローズドなモデル重み
- **再現性が制限**されていた

## オープンソース再現

### 置き換え
| オリジナル | オープンソース版 |
|-----------|----------------|
| Google Search API | Wikipedia API |
| LLaMA-2 | Phi-3-mini-4k-instruct |

### 結果
- PopQA、ARC-Challengeで評価
- **オリジナルシステムに匹敵する性能**

## 説明可能性分析（初の貢献）

### 手法
- **SHAP**によるT5ベース検索評価器の分析

### 発見
- 評価器は主に**固有表現のアライメント**に依存
- 意味的類似度よりも表層的なマッチングを重視

### 限界の特定
- **ドメイン転移の限界** - 科学質問で顕著
- 科学ドメインでの性能低下

## 技術的貢献

1. CRAGの完全オープンソース再現
2. 検索評価器のSHAP説明可能性分析（初）
3. 失敗モードの体系的特定

## 公開物

- コード完全公開
- 結果データ
- 再現手順

## 意義

RAGシステムの再現性と理解を促進。検索評価器の限界を明らかにし、改善方向を示す。
