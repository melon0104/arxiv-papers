---
layout: default
title: OTIS - OOD Overconfidence
---

# OTIS: Optimal Transport-Induced Samples against Out-of-Distribution Overconfidence

**arXiv:** [2601.21320](https://arxiv.org/abs/2601.21320) | **カテゴリ:** cs.CV, cs.LG

## 🏆 ICLR 2026 採択

## 概要

DNNのOOD入力に対する過信問題を、最適輸送（OT）の幾何学を活用して解決。半離散OTの特異境界近傍からサンプリングし、意味的に曖昧なOODサンプル（OTIS）を構築。訓練時にOTISへの信頼度抑制損失を適用。

## 主要な貢献

1. **OT特異境界**: 分類器が不当な高信頼度予測を起こしやすい領域を特定
2. **OTIS生成**: 幾何学的に根拠のある、本質的に意味曖昧なOODサンプル
3. **信頼度抑制損失**: 構造的に不確実な領域でより較正された予測を誘導

## 結果

- OOD過信を大幅に軽減
- SOTAを上回る性能

## 選定理由

✅ ICLR 2026採択 | ✅ 最適輸送のCV応用

[← 戻る](/)
