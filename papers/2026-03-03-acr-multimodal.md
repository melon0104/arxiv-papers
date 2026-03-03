---
layout: paper
title: "Adaptive Confidence Regularization for Multimodal Failure Detection"
date: 2026-03-03
arxiv_id: "2603.02200"
arxiv_url: "https://arxiv.org/abs/2603.02200"
pdf_url: "https://arxiv.org/pdf/2603.02200"
authors: ["Moru Liu", "Hao Dong", "Olga Fink", "Mario Trapp"]
categories: ["cs.LG", "cs.CV", "cs.AI"]
venue: "CVPR 2026"
code_url: "https://github.com/moruLiu/ACR"
---

## 一言まとめ

**CVPR 2026**: マルチモーダル故障検出のための**Adaptive Confidence Regularization (ACR)**フレームワーク。自動運転や医療診断など高リスクドメインでの信頼性を向上。

## 概要

自動運転車や医療診断などの高リスクドメインでは、強力な予測性能だけでなく、故障を検出する信頼性の高いメカニズムも求められる。本研究では、マルチモーダルコンテキストにおける故障検出という、ほぼ未開拓の問題に取り組む。

### 提案手法: Adaptive Confidence Regularization (ACR)

マルチモーダル故障を検出するために特別に設計されたフレームワーク。

#### 重要な観察

ほとんどの故障ケースにおいて、予測信頼度とモダリティ間の不一致パターンに相関がある。

#### ACRの特徴

1. **適応的信頼度正則化**: 故障ケースでの信頼度を適切に調整
2. **マルチモーダル不一致の活用**: モダリティ間の不整合を故障シグナルとして利用
3. **高リスクドメイン対応**: 安全性が重要なアプリケーション向け

## 所感

マルチモーダルAIの実世界デプロイにおける安全性向上の重要な一歩。自動運転や医療AIでは「間違いを認識できること」が極めて重要。GitHub公開済みで実装検証も可能。
