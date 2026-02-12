---
layout: paper
title: "Training-Induced Bias Toward LLM-Generated Content in Dense Retrieval"
arxiv_id: "2602.10833"
date: 2026-02-12
categories: [cs.IR, cs.CL]
conference: "ECIR 2026"
---

# Training-Induced Bias Toward LLM-Generated Content in Dense Retrieval

## 基本情報
- **arXiv**: [2602.10833](https://arxiv.org/abs/2602.10833)
- **カテゴリ**: cs.IR, cs.CL
- **採択**: ECIR 2026
- **著者**: William Xion et al.

## 概要

Dense Retrieverが訓練データに応じてLLM生成テキストを優先的にランキングする「ソースバイアス」を詳細に分析した研究。

## 主要な発見

1. **教師なしRetrieverにはバイアスがない**: バイアスの方向と大きさはデータセットに依存
2. **MS MARCOでの訓練でバイアス発生**: 全設定でLLM生成テキストへのランキングシフト
3. **LLM生成コーパスでの訓練で顕著なバイアス**: Pro-LLMバイアスが強く誘発

## 技術的貢献

- SciFact、NQ320Kの人間/LLM並列コーパスで評価
- 言語モデルヘッドをRetrieverエンコーダに再接続してPerplexityと関連性の相関を調査
- Perplexityの説明力が弱いことを実証

## 結論

ソースバイアスはDense Retrieverの固有の性質ではなく、訓練によって誘発される現象であることを実証。RAGシステム設計への重要な示唆。
