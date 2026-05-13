---
layout: paper
title: "Task-Adaptive Embedding Refinement via Test-time LLM Guidance"
date: 2026-05-14
category: cs.CL
arxiv_id: "2605.12487"
url: https://arxiv.org/abs/2605.12487
authors:
  - Ariel Gera
  - Shir Ashury-Tahan
  - Gal Bloch
tags: [embedding, retrieval, test-time-adaptation, zero-shot, LLM-guidance]
---

# Task-Adaptive Embedding Refinement via Test-time LLM Guidance

## 概要

埋め込みモデルをゼロショット検索・分類タスクに拡張するためのLLMガイド付きクエリ改良パラダイムを探求する研究。少数のドキュメントに対する生成LLMのフィードバックを用いてユーザークエリの埋め込み表現をリファインし、対象タスクにリアルタイムで適応させる。

最先端テキスト埋め込みモデルを使った多様なベンチマークでの実験により、LLMガイド付きクエリ改良が一貫した性能向上をもたらすことを実証。

## 選定理由

- 埋め込みモデルのテスト時適応という実用的なトピック
- 検索・分類双方に適用可能な汎用フレームワーク
- ゼロショット設定での実用性が高い

## キーポイント

- **課題**: 埋め込みモデルの学習後の対象タスクへの適応が困難
- **手法**: テスト時にLLMフィードバックで埋め込みをリアルタイム改良
- **効果**: ゼロショット検索・分類で一貫した性能向上を実証

## arXiv

https://arxiv.org/abs/2605.12487
