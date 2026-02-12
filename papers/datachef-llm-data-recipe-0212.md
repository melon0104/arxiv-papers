---
layout: paper
title: "DataChef: Cooking Up Optimal Data Recipes for LLM Adaptation via Reinforcement Learning"
arxiv_id: "2602.11089"
date: 2026-02-12
categories: [cs.CL, cs.AI]
---

# DataChef: Automated Data Recipe Generation

## 基本情報
- **arXiv**: [2602.11089](https://arxiv.org/abs/2602.11089)
- **カテゴリ**: cs.CL, cs.AI
- **著者**: Yicheng Chen et al.

## 概要

LLM適応のためのデータレシピ（処理パイプライン）を自動生成するフレームワーク。候補レシピの下流性能を予測するプロキシ報酬でオンライン強化学習を実行。

## 技術的貢献

### End-to-End Data Recipe Generation
- ターゲットベンチマークと利用可能データソースを入力
- 完全なデータレシピを出力

### DataChef-32B
- オンラインRLで学習
- 人間専門家がキュレーションしたレシピと同等の下流性能を達成

## 主要結果

| モデル | ベンチマーク | スコア |
|--------|-------------|--------|
| Qwen3-1.7B-Base + DataChef Recipe | AIME'25 | **66.7** |
| Qwen3-1.7B (公式) | AIME'25 | < 66.7 |

DataChefのレシピがQwen3-1.7B公式モデルを上回る性能を達成。

## 意義

LLM訓練の自動化と自己進化AIシステムの新たな可能性を示唆。
