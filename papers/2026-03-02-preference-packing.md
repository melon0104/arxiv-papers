---
layout: paper
title: "Preference Packing: Efficient Preference Optimization"
date: 2026-03-02
arxiv_id: "2602.24082"
categories: [cs.CL, cs.AI]
---

# Preference Packing: Efficient Preference Optimization for Large Language Models

## 基本情報
- **arXiv**: [2602.24082](https://arxiv.org/abs/2602.24082)
- **カテゴリ**: cs.CL, cs.AI

## 概要
LLMのサイズ増大に伴い、リソース効率の良い訓練最適化技術が重要に。バッチパッキングは事前学習やSFTで広く使われるが、DPOなど同一プロンプトに対する複数応答を使う手法には適用されていなかった。本研究では**Preference Packing**を提案。

## 主要貢献
1. **重複入力プロンプトの効率化**: 同一プロンプトへのattention演算を削減
2. **KVキャッシュメモリ使用量削減**
3. **既存最適化技術との併用可能**: バッチソートなどと組み合わせ可能

## 実験結果
- テキストのみデータセット: **37%以上の訓練時間削減**
- 画像含むデータセット: 同様の効率改善
- バッチソートとの併用: **3.22倍の高速化**

## 適用範囲
- 報酬モデル訓練
- DPO（Direct Preference Optimization）
- その他の選好学習手法

## 注目ポイント
⚡ **訓練効率大幅改善**: 37%以上の時間削減
🔧 既存手法と組み合わせて**3.22倍高速化**
📷 テキストとマルチモーダル両方に対応
