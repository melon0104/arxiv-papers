---
layout: paper
title: "SRLM: Self-Reflective Program Search for Long Context"
date: 2026-03-19
arxiv_id: "2603.15653"
categories: ["cs.CL", "cs.AI", "cs.LG"]
---

# Recursive Language Models Meet Uncertainty: Self-Reflective Program Search for Long Context

## 基本情報

| 項目 | 内容 |
|------|------|
| arXiv | [2603.15653](https://arxiv.org/abs/2603.15653) |
| カテゴリ | cs.CL, cs.AI, cs.LG |

## 概要

長文脈処理の課題に対し、Recursive Language Models（RLM）のプログラム選択問題を研究。不確実性を考慮した自己反省機構**SRLM**を提案し、RLMを**最大22%改善**。

## 問題設定

- 拡張コンテキストウィンドウでも長文脈からの情報抽出・推論は困難
- RLMはプログラム的インタラクションで再帰的分解を行うが、プログラム選択が重要
- 最適なプログラム選択方法は未探索

## 提案手法: SRLM

### 3つの内部不確実性シグナル

1. **Self Consistency** - 自己一貫性
2. **Reasoning Length** - 推論長
3. **Verbalized Confidence** - 言語化された確信度

### 仕組み
- これらを相補的な不確実性指標として活用
- モデルが候補プログラムを評価・比較
- 自己反省的なプログラム探索を実現

## 主要な発見

| 発見 | 詳細 |
|------|------|
| RLM改善 | 同一時間予算で**最大+22%** |
| 再帰は必須でない | 単純な自己反省探索がRLM無し/再帰無しで同等以上 |
| 短文脈での劣化 | モデルウィンドウ内の長さでは再帰RLMが性能低下 |
| 意味集約的タスク | RLMはヒューリスティック探索が不十分な場合に弱い |

## 技術的貢献

1. プログラム選択問題の定式化
2. 不確実性ベースの自己反省フレームワーク
3. RLMの限界と改善方向の実証的分析

## 意義

再帰そのものより、自己反省的な意味信号が長文脈推論の鍵。RLMの理解を深め、より効果的なアプローチへの道を示す。
