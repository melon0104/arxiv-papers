---
layout: paper
title: "OpenSanctions Pairs: Large-Scale Entity Matching with LLMs"
date: 2026-03-13
arxiv_id: "2603.11051"
categories: [cs.IR, cs.AI, cs.CL, cs.LG]
---

# OpenSanctions Pairs: Large-Scale Entity Matching with LLMs

## 基本情報
- **arXiv ID**: 2603.11051
- **カテゴリ**: cs.IR, cs.AI, cs.CL, cs.LG
- **投稿日**: 2026年2月24日
- **注目ポイント**: 💻 **GitHub公開**

## 概要
国際制裁データの重複排除から派生した大規模エンティティマッチングベンチマーク「OpenSanctions Pairs」を公開。755,540ラベル付きペア、293の異種ソース、31カ国、多言語・クロススクリプト対応。

## 主要な貢献
1. **大規模ベンチマーク**: 現実のコンプライアンスワークフローに基づく75万超のペア
2. **LLMの優位性**: GPT-4oで98.95% F1、DeepSeek-R1-Distill-Qwen-14Bで98.23% F1
3. **エラー分析**: ルールベースは過剰マッチ（偽陽性多）、LLMはクロススクリプト音訳で失敗

## 主要結果
| モデル | F1スコア |
|--------|----------|
| 本番ルールベース | 91.33% |
| GPT-4o | 98.95% |
| DeepSeek-R1-Distill-Qwen-14B | 98.23% |

## 実用的示唆
- ペアワイズマッチングは実用的な精度上限に到達しつつある
- 今後はブロッキング、クラスタリング、不確実性対応レビューへの注力が重要

## リンク
- [arXiv](https://arxiv.org/abs/2603.11051)
- [GitHub](https://github.com/chansmi/OSINT_entity_resolution)
