---
layout: paper
title: "Verifiable Reasoning for LLM-based Generative Recommendation"
date: 2026-03-10
categories: [cs.IR]
arxiv_id: "2603.07725"
github: "https://github.com/Linxyhaha/Verifiable-Rec"
---

# Verifiable Reasoning for LLM-based Generative Recommendation

## 基本情報
- **arXiv ID**: 2603.07725
- **カテゴリ**: cs.IR (Information Retrieval)
- **投稿日**: 2026-03-08
- **GitHub**: https://github.com/Linxyhaha/Verifiable-Rec

## 著者
Xinyu Lin, Hanqing Zeng, Hanchao Yu, Yinglong Xia, Jiang Zhang, Aashu Singh, Fei Liu, Wenjie Wang, Fuli Feng, Tat-Seng Chua, Qifan Wang

## 概要
LLMの推論能力は、複雑なユーザー嗜好の深い理解を通じて生成的推薦を強化する可能性を示す。既存手法は**reason-then-recommend**パラダイムに従うが、中間検証がないため**推論劣化**（同質的・誤差蓄積的推論）に陥り、推薦品質を損なう。

本研究では新しい**reason-verify-recommend**パラダイムを提案。推論と検証をインターリーブし、信頼性のあるフィードバックで推論プロセスを忠実なユーザー嗜好理解に導く。

**VRec**の主要設計：
1. **Mixture of Verifiers**: 多次元性を確保する複数検証器
2. **Proxy Prediction Objective**: 信頼性を追求する代理予測目的
3. **Multi-dimensional User Preferences**: 包括的な多次元嗜好検証

## 主要結果
- 4つの実世界データセットで既存手法を大幅に上回る
- 効率を維持しながら推薦効果と拡張性を向上
- 検証可能な推論により**幻覚の抑制**と**説明可能性向上**

## 技術的詳細
- 検証器は推論の正確性と情報性を評価
- 多次元ユーザー嗜好の包括的検証を強調
- プロキシ予測目的で信頼性を追求

## 実用的意義
- LLM推薦システムの信頼性・説明可能性向上
- ユーザー嗜好の忠実な理解に基づく推薦
- コード公開により再現・拡張が容易

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.07725
- GitHub: https://github.com/Linxyhaha/Verifiable-Rec
