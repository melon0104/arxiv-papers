---
layout: paper
title: "Censored LLMs as a Natural Testbed for Secret Knowledge Elicitation"
date: 2026-03-08
categories: [cs.LG, cs.AI, cs.CL]
---

# Censored LLMs as a Natural Testbed for Secret Knowledge Elicitation

- **arXiv**: [2603.05494](https://arxiv.org/abs/2603.05494)
- **著者**: Helena Casademunt et al.
- **コード・データ**: 公開

## 概要

中国製オープンウェイトLLM（Qwen3など）を「秘密知識引き出し」のテストベッドとして活用。これらのモデルは政治的に敏感なトピックを検閲するよう訓練されており、知識を持ちながら抑制している自然発生的なケースを提供する。

## 実験設定

- **対象モデル**: Qwen3、DeepSeek R1
- **対象トピック**: 法輪功、天安門事件など
- **評価手法**: 誠実性引き出し手法と嘘検出手法の網羅的評価

## 主な発見

1. **誠実性引き出しの効果**: チャットテンプレートなしのサンプリング、Few-shot prompting、汎用誠実性データでのファインチューニングが最も効果的
2. **嘘検出**: 検閲されたモデル自身による自己分類が非検閲モデル上限に近い性能
3. **DeepSeek R1への転移**: 最強の誠実性引き出し手法はDeepSeek R1にも適用可能

## 限界と示唆

- **完全な虚偽応答の排除は困難**
- 自然発生的な検閲モデルは人工的なデータセットより現実的
- AI安全性研究への示唆

## 注目ポイント

- 検閲モデルを活用した新しい研究アプローチ
- DeepSeek R1への転移可能性
- プロンプト・コード公開
