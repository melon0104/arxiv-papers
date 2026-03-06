---
layout: paper
title: "FinRetrieval: A Benchmark for Financial Data Retrieval by AI Agents"
date: 2026-03-06
categories: [cs.IR, cs.AI, cs.CL]
---

# FinRetrieval: A Benchmark for Financial Data Retrieval by AI Agents

**arXiv**: [2603.04403](https://arxiv.org/abs/2603.04403)

**著者**: Eric Y. Kim et al.

**カテゴリ**: cs.IR, cs.AI, cs.CL

## 概要

AIエージェントが構造化データベースから特定の数値を取得する能力を評価する初のベンチマーク「FinRetrieval」を提案。500の金融検索質問と、Anthropic・OpenAI・Googleの3つのフロンティアプロバイダーにわたる14の設定のエージェント応答を含む。

## 主な発見

- **ツール可用性が支配的**: Claude Opusは構造化データAPIで**90.8%**の精度を達成するが、Web検索のみでは**19.8%**と71ポイントのギャップ
- **推論モードの効果**: 推論モードの恩恵はベース能力と逆相関（OpenAI +9.0pp vs Claude +2.8pp）
- **地理的パフォーマンス差**: 米国優位5.6ppは会計年度の命名規則に起因
- **完全なツールコール実行トレースを公開**

## 注目ポイント

- Claude Opus、GPT、Geminiなどフロンティアモデルの包括的評価
- 金融AIシステム研究のためにデータセット・評価コード・ツールトレースを公開
