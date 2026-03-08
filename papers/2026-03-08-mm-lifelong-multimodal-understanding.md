---
layout: paper
title: "MM-Lifelong: Towards Multimodal Lifelong Understanding"
date: 2026-03-08
categories: [cs.CV]
---

# MM-Lifelong: Towards Multimodal Lifelong Understanding

- **arXiv**: [2603.05484](https://arxiv.org/abs/2603.05484)
- **著者**: Guo Chen, ..., **Zhiding Yu, Andrew Tao, Guilin Liu (NVIDIA)**, Tong Lu
- **関連機関**: NVIDIA

## 概要

マルチモーダル生涯理解のためのデータセット。181.1時間の映像で構成され、日・週・月スケールで時間的密度の変化を捉える。既存のビデオ理解データセットとは異なり、自然で台本なしの日常生活を反映。

## 主な発見

1. **作業記憶ボトルネック**: エンドツーエンドMLLMはコンテキスト飽和で失敗
2. **グローバル位置特定崩壊**: エージェントベースラインが月スケールで失敗

## 提案手法：Recursive Multimodal Agent (ReMA)

- 動的メモリ管理
- 再帰的信念状態の反復更新
- 既存手法を大幅に上回る

## 注目ポイント

- **NVIDIA研究者が共著**
- 181時間の大規模生涯理解データセット
- 現行MLLMの限界を明確に特定
- 時間的・ドメインバイアスを分離する評価設計
