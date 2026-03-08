---
layout: paper
title: "Reasoning Theater: Disentangling Model Beliefs from Chain-of-Thought"
date: 2026-03-08
categories: [cs.CL, cs.AI, cs.LG]
---

# Reasoning Theater: Disentangling Model Beliefs from Chain-of-Thought

- **arXiv**: [2603.05488](https://arxiv.org/abs/2603.05488)
- **著者**: Siddharth Boppana et al.
- **分析対象**: DeepSeek-R1 671B, GPT-OSS 120B

## 概要

推論モデルにおける「パフォーマティブCoT（演技的Chain-of-Thought）」の証拠を提供。モデルが最終回答に強い確信を持った後も、内部信念を明かさずにトークン生成を続ける現象を分析。

## 主な発見

1. **早期に回答が決定**: アクティベーションプローブにより、CoTモニターが検出するよりも遥かに早い段階で最終回答が復号可能
2. **タスク難易度依存**: 簡単なMMLU問題ではより顕著、難しいGPQA-Diamondでは真の推論が観察される
3. **変曲点の意味**: 「aha」モーメントやバックトラッキングは、信念シフトが大きい応答でのみ発生

## 実用的応用

- **プローブ誘導の早期終了**: MMLUで最大80%、GPQA-Diamondで30%のトークン削減
- パフォーマティブ推論検出のためのアテンションプローブ
- 適応的計算のツールとして位置づけ

## 注目ポイント

- **DeepSeek-R1 671Bの詳細分析**
- 推論モデルの「演技」vs「本物の推論」を識別
- 効率的な推論のための実践的手法を提案
