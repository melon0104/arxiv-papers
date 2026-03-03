---
layout: paper
title: "Multi-Head Low-Rank Attention"
date: 2026-03-03
arxiv_id: "2603.02188"
arxiv_url: "https://arxiv.org/abs/2603.02188"
pdf_url: "https://arxiv.org/pdf/2603.02188"
authors: ["Songtao Liu", "Hongwu Peng", "Zhiwei Zhang", "Zhengyu Chen", "Yue Guo"]
categories: ["cs.LG"]
venue: "ICLR 2026"
code_url: "https://github.com/SongtaoLiu0823/MHLRA"
---

## 一言まとめ

**ICLR 2026**: 長コンテキスト推論のKVキャッシュボトルネックを解決する**Multi-Head Low-Rank Attention**。MLAのTensor Parallelismシャーディング問題を克服。

## 概要

LLMの長コンテキスト推論は、デコーディング段階でのKey-Value (KV) キャッシュローディングがボトルネック。各ステップでKVキャッシュをオフチップHBMからオンチップSRAMに繰り返し転送する必要がある。

### 既存手法の課題

**Multi-Head Latent Attention (MLA)**はKVキャッシュサイズを大幅に削減するが、Tensor Parallelism (TP)による分散デコーディング時に**シャーディングボトルネック**が発生。

### 提案手法の特徴

1. **低ランクアテンション構造**: KVキャッシュサイズを効率的に圧縮
2. **マルチヘッド設計**: TPとの互換性を維持
3. **分散推論対応**: シャーディング問題を回避

## 所感

長コンテキストLLMのデプロイにおける実践的な最適化。MLAの改良版として、分散推論環境での効率改善に直結。ICLR採択+GitHub公開で信頼性も高い。
