---
layout: paper
date: 2026-03-16
title: "OpenSanctions Pairs: Large-Scale Entity Matching with LLMs"
arxiv_id: "2603.11051"
categories: [cs.IR, cs.CL, cs.AI]
---

# OpenSanctions Pairs: Large-Scale Entity Matching with LLMs

## 基本情報
- **arXiv ID**: 2603.11051
- **カテゴリ**: cs.IR, cs.CL, cs.AI
- **GitHub**: https://github.com/chansmi/OSINT_entity_resolution

## 概要
国際制裁データベースの実運用アナリストによる重複排除から作成された大規模エンティティマッチングベンチマーク。755,540ラベル付きペア、293ソース、31カ国にまたがる多言語・クロススクリプト名、ノイズのある属性を含む。

## 主な成果
- **GPT-4o**: 98.95% F1（ルールベース91.33%を大幅に上回る）
- **DeepSeek-R1-Distill-Qwen-14B**: 98.23% F1（ローカル展開可能）
- ルールベースは過剰マッチ（偽陽性）、LLMはクロススクリプト翻字で失敗
- ペアワイズマッチングは実用上の上限に到達 → ブロッキング・クラスタリングに注力すべき

## 注目ポイント
- **実運用データ**: 実際の制裁コンプライアンスワークフローから構築
- **コード公開**: GitHub利用可能
- LLMがルールベースを圧倒的に上回る実例
