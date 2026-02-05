---
layout: paper
title: "STM: Synthesize-Train-Merge for Biomedical Retrievers"
date: 2026-02-06
arxiv_id: "2602.04731"
categories: ["cs.CL", "cs.LG"]
---

# STM: Less Finetuning, Better Retrieval

**arXiv**: https://arxiv.org/abs/2602.04731

## 概要

汎用LLMをドメイン特化型リトリーバー（特に生物医学分野）に効率的に適応させる「Synthesize-Train-Merge（STM）」フレームワークを提案。

## 手法

1. **Synthesize**: 合成ハードネガティブの生成
2. **Train**: 検索プロンプト最適化
3. **Merge**: モデルマージング

## 実験結果

MTEBベンチマークの12タスク（医療＋汎用）で評価:
- タスク特化エキスパートを**最大23.5%向上**（平均7.5%）
- マージモデルは単一エキスパートと強力なベースラインの両方を上回る
- **大規模な事前学習なし**で達成

## 特長

- 汎用ドメインの能力を維持しつつ専門タスクで優れる
- スケーラブルで効率的なアプローチ
- モジュラー設計で拡張性が高い

## 所感

ドメイン特化リトリーバーの構築は従来、大規模な事前学習が必要だった。STMは合成データとモデルマージという効率的な手法で同等以上の性能を達成し、RAG実用化の敷居を下げる。
