---
layout: paper
title: "SAGE: 深層リサーチエージェント向け検索ベンチマーク"
date: 2026-02-07
arxiv_id: "2602.05975"
categories: [cs.IR, cs.CL, RAG]
---

# SAGE: Benchmarking and Improving Retrieval for Deep Research Agents

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.05975
- **著者**: Tiansheng Hu, Yilun Zhao, Canyu Zhang, **Arman Cohan**, Chen Zhao
- **投稿先**: ACL ARR 2026 January

## 概要
深層リサーチエージェント向けの科学文献検索ベンチマーク。**1,200クエリ × 200,000論文**のコーパスを提供。

## 驚きの発見
**BM25がLLMベースリトリーバーを約30%上回る**
- 既存エージェントはキーワード指向のサブクエリを生成するため
- ReasonIR、gte-Qwen2-7Bなどの最新LLMリトリーバーと比較

## 提案手法
**Corpus-level Test-time Scaling**:
- LLMでドキュメントにメタデータ・キーワードを付与
- オフザシェルフのリトリーバーでの検索を容易化
- 短形式QAで+8%、オープンエンドQAで+2%の改善

## 注目ポイント
- Deep Researchエージェント（Perplexity等）の検索能力を客観評価
- LLMリトリーバーの限界を明らかに
- 実践的な改善手法を提案
