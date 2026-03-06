---
layout: paper
title: "Reasoning Theater: Disentangling Model Beliefs from Chain-of-Thought"
date: 2026-03-06
categories: [cs.CL, cs.AI, cs.LG]
---

# Reasoning Theater: Disentangling Model Beliefs from Chain-of-Thought

**arXiv**: [2603.05488](https://arxiv.org/abs/2603.05488)

**著者**: Siddharth Boppana et al.

**カテゴリ**: cs.CL, cs.AI, cs.LG

## 概要

推論モデルにおける「パフォーマティブCoT」（モデルが最終回答に強い確信を持ちながらも、内部的な信念を明かさずにトークン生成を続ける現象）の証拠を提供。

## 主な発見

- **大規模モデルでの検証**: DeepSeek-R1 671B と GPT-OSS 120B の2つの大規模モデルで分析
- **タスク難易度依存の差異**: 簡単なMMLU問題ではCoTモニターが判断できるよりもはるかに早い段階で活性化から最終回答がデコード可能
- **真の推論との対比**: 難しいGPQA-Diamondのマルチホップ問題では本物の推論を確認
- **変曲点の発生**: バックトラッキングや「aha」モーメントは、プローブが大きな信念シフトを示す応答でほぼ独占的に発生

## 実用的応用

- **プローブガイド早期終了**: MMLUでトークンを最大**80%削減**、GPQA-Diamondで**30%削減**、精度は同等を維持
- 注意プローブがパフォーマティブ推論検出と適応的計算のための効率的ツールに

## 注目ポイント

🔍 DeepSeek-R1やGPTなどフロンティア推論モデルの内部動作を深く分析
