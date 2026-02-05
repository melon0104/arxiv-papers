---
layout: paper
title: "SDAG: Sparse Document Attention RAG for Corpus Knowledge Poisoning Defense"
date: 2026-02-06
arxiv_id: "2602.04711"
categories: ["cs.IR", "cs.AI"]
---

# SDAG: Sparse Document Attention RAG

**arXiv**: https://arxiv.org/abs/2602.04711

## 概要

RAGシステムに対するcorpus knowledge poisoning攻撃（悪意あるドキュメント注入）への防御手法「SDAG」を提案。

## 問題意識

- RAGは情報を最新に保ちハルシネーションを減らす効果的なパラダイム
- しかし攻撃者が誤導的ドキュメントを注入してLLM出力を操作できる脆弱性あり
- **標準的なcausal attentionが有害なクロスドキュメント相互作用を許してしまう**

## 提案手法: SDAG (Sparse Document Attention RAG)

- **Block-sparse attention機構**: 検索されたドキュメント間のクロスアテンションを禁止
- **最小限の変更**: 推論時のattention maskの変更のみ
- **Fine-tuning不要**: アーキテクチャ変更も不要

## 実験結果

- 様々な攻撃戦略に対してAttack Success Rateを大幅に低減
- 最新のRAG防御手法との統合でさらに性能向上
- 統合結果はSOTAを統計的有意に上回る

## 所感

RAGの普及とともにセキュリティの重要性が増している。SDAGは実装が容易でありながら効果的な防御策を提供する実用的なアプローチ。
