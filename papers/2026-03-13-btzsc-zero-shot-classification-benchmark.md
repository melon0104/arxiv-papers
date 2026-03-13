---
layout: paper
title: "BTZSC: A Benchmark for Zero-Shot Text Classification"
date: 2026-03-13
arxiv_id: "2603.11991"
categories: [cs.CL, cs.AI, cs.LG]
---

# BTZSC: Benchmark for Zero-Shot Text Classification

## 基本情報
- **arXiv ID**: 2603.11991
- **カテゴリ**: cs.CL, cs.AI, cs.LG, stat.ML
- **投稿日**: 2026年3月12日
- **注目ポイント**: 🏆 **ICLR 2026採択**

## 概要
真のゼロショットテキスト分類能力を評価するための包括的ベンチマーク「BTZSC」を提案。22の公開データセット、38モデル、4つのモデルファミリーを体系的に比較。

## ベンチマーク構成
- **データセット**: 22種（感情、トピック、意図、感情分類）
- **モデル**: NLIクロスエンコーダ、埋め込みモデル、リランカー、LLM

## 主要な発見
| モデルファミリー | Macro F1 |
|------------------|----------|
| Qwen3-Reranker-8B（最高） | 0.72 |
| GTE-large-en-v1.5 | 精度・レイテンシ最良トレードオフ |
| 命令チューニングLLM（4-12B） | 最大0.67 |
| NLIクロスエンコーダ | 精度頭打ち |

## 実用的示唆
- リランカーが新しいSOTAを達成
- 埋め込みモデルは精度と速度の最良バランス
- LLMはトピック分類で特に優秀

## リンク
- [arXiv](https://arxiv.org/abs/2603.11991)
- [GitHub](https://github.com/IliasAarab/btzsc)
- [データセット](https://huggingface.co/datasets/btzsc/btzsc)
- [リーダーボード](https://huggingface.co/spaces/btzsc/btzsc-leaderboard)
