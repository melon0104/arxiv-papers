---
layout: paper
title: "AP-OOD: テキストOOD検出のためのアテンションプーリング"
date: 2026-02-07
arxiv_id: "2602.06031"
categories: [cs.LG, OOD Detection]
---

# AP-OOD: Attention Pooling for Out-of-Distribution Detection

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.06031
- **著者**: Claus Hofmann, Christian Huber, Bernhard Lehner, Daniel Klotz, **Sepp Hochreiter**, Werner Zellinger
- **採択**: **ICLR 2026**
- **機関**: Johannes Kepler University Linz

## 概要
自然言語のOOD検出のための新手法。トークンレベル情報を活用し、単純な平均ベースの集約を超えた**半教師あり**アプローチ。

## 技術的ポイント
- **Multi-head Attentive Average Pooling / QKV Pooling**
- **教師なし〜教師ありの柔軟な補間**: 限られた外れ値データの活用が可能
- 従来の平均プーリングの限界を克服

## 実験結果
| データセット | FPR95改善 |
|--------------|-----------|
| XSUM要約 | 27.84% → **4.67%** |
| WMT15 En-Fr翻訳 | 77.08% → **70.37%** |

## 注目ポイント
- **ICLR'26採択 + Sepp Hochreiter（LSTM発明者）が共著**
- テキストドメインでのOOD検出の大幅改善
- 実践的な半教師ありアプローチ
