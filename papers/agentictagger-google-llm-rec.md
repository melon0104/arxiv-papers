---
layout: paper
title: "AgenticTagger: LLMエージェントによる構造化アイテム表現の生成"
date: 2026-02-07
arxiv_id: "2602.05945"
categories: [cs.IR, Recommendation]
---

# AgenticTagger: Structured Item Representation for Recommendation with LLM Agents

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.05945
- **著者**: Zhouhang Xie, Bo Peng, Zhankui He, **Julian McAuley** (UCSD), **Fernando Pereira** (Google), **Wang-Cheng Kang** (Google), **Derek Zhiyuan Cheng** (Google) 他
- **機関**: Google, UCSD

## 概要
LLMを活用した**記述子（descriptor）生成フレームワーク**。アイテムをキーフレーズ的な自然言語表現で記述し、推薦システムの下流タスクに活用。

## 技術的ポイント
- **2段階アプローチ**:
  1. **Vocabulary Building**: 階層的で低カーディナリティの記述子セットを特定
  2. **Vocabulary Assignment**: LLMがアイテムに記述子を割り当て
- **Multi-Agent Reflection**: アーキテクトLLMがアノテーターLLMからのフィードバックを基に語彙を反復改善
- **オープンエンド生成の制御**: 高カーディナリティ・低品質な記述子を防止

## 実験結果
- 生成的検索、term-based検索、ランキング、critique-based推薦で一貫した改善
- 公開・非公開データセットの両方で検証

## 注目ポイント
- **Google Research + UCSD**の共同研究
- LLMの推薦システムへの実践的統合アプローチ
- 多様な推薦シナリオへの汎用性
