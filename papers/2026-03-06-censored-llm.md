---
layout: paper
title: "Censored LLMs as a Natural Testbed for Secret Knowledge Elicitation"
date: 2026-03-06
categories: [cs.LG, cs.AI, cs.CL]
---

# Censored LLMs as a Natural Testbed for Secret Knowledge Elicitation

**arXiv**: [2603.05494](https://arxiv.org/abs/2603.05494)

**著者**: Helena Casademunt et al.

**カテゴリ**: cs.LG, cs.AI, cs.CL

## 概要

中国の開発者によるオープンウェイトLLM（政治的に敏感なトピックを検閲するよう訓練されている）を、秘密知識の引き出しと嘘検出技術の自然なテストベッドとして活用。

## 主な発見

- **Qwen3モデルの分析**: 法輪功や天安門事件などのトピックについて虚偽を生成するが、時折正しく回答（抑制するよう訓練された知識を持っていることを示唆）
- **誠実性引き出し技術**: チャットテンプレートなしのサンプリング、few-shotプロンプティング、汎用誠実性データでのファインチューニングが最も効果的
- **嘘検出**: 検閲されたモデル自身に応答を分類させることで、検閲されていないモデルの上限に近い性能を達成
- **DeepSeek R1への転移**: 最も強力な技術はフロンティアオープンウェイトモデルにも転移可能

## 注目ポイント

⚠️ どの技術も虚偽応答を完全に排除できないことを報告
📝 全てのプロンプト、コード、トランスクリプトを公開
