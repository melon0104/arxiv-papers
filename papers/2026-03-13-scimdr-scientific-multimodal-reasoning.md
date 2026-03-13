---
layout: paper
title: "SciMDR: Benchmarking Scientific Multimodal Document Reasoning"
date: 2026-03-13
arxiv_id: "2603.12249"
categories: [cs.CL, cs.AI, cs.CV]
---

# SciMDR: Scientific Multimodal Document Reasoning

## 基本情報
- **arXiv ID**: 2603.12249
- **カテゴリ**: cs.CL, cs.AI, cs.CV
- **投稿日**: 2026年3月12日

## 概要
科学論文における図表・数式を含むマルチモーダル文書推論のための大規模データセット「SciMDR」と評価ベンチマーク「SciMDR-Eval」を提案。

## フレームワーク: Synthesize-and-Reground
1. **Claim-Centric QA Synthesis**: 文書の焦点セグメントから忠実なQAペアと推論を生成
2. **Document-Scale Regrounding**: フル文書タスクにプログラム的に再埋め込みし現実的な複雑さを保証

## データセット規模
- **SciMDR**: 300K QAペア、20K科学論文、明示的推論チェーン付き
- **SciMDR-Eval**: 専門家アノテーションによる評価ベンチマーク

## 結果
SciMDRでファインチューニングしたモデルは、複雑な文書レベル推論を要するタスクで特に大幅な改善を達成。

## リンク
- [arXiv](https://arxiv.org/abs/2603.12249)
- [PDF](https://arxiv.org/pdf/2603.12249)
