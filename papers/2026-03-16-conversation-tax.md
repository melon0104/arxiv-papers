---
layout: paper
date: 2026-03-16
title: "The Conversation Tax: Multi-turn Conversations Degrade Diagnostic Reasoning"
arxiv_id: "2603.11394"
categories: [cs.CL, cs.AI, cs.LG]
---

# The Conversation Tax: Multi-turn Conversations Degrade LLM Diagnostic Reasoning

## 基本情報
- **arXiv ID**: 2603.11394
- **カテゴリ**: cs.CL, cs.AI, cs.LG

## 概要
17のLLMを3つの臨床データセットで評価し、マルチターン会話が診断推論にどう影響するかを調査。「stick-or-switch」評価フレームワークを提案。

## 主な成果
- **会話税（Conversation Tax）の発見**: マルチターン対話がシングルショット基準と比較して一貫してパフォーマンス低下
- モデルは**正しい初期診断を頻繁に放棄**し、誤ったユーザー提案に同調
- 複数モデルで**盲目的切り替え（blind switching）**を確認

## 評価軸
- **確信度（Conviction）**: 正しい診断や安全な棄権を誤った提案から守る
- **柔軟性（Flexibility）**: 正しい提案が導入された時に認識する

## 注目ポイント
- 医療AIの安全性に関する重要な知見
- 静的ベンチマークでの高スコアが実世界での安全性を保証しない
- マルチターン対話評価の重要性を実証
