---
layout: paper
title: "Towards Provably Unbiased LLM Judges via Bias-Bounded Evaluation"
date: 2026-03-08
categories: [cs.AI]
---

# Towards Provably Unbiased LLM Judges via Bias-Bounded Evaluation

- **arXiv**: [2603.05485](https://arxiv.org/abs/2603.05485)
- **著者**: Benjamin Feuer et al.
- **GitHub**: https://github.com/penfever/bias-bounded-evaluation

## 概要

自律的AIシステムにおけるLLM-as-a-Judgeのバイアス問題を解決するための理論的保証付きフレームワーク。測定可能なバイアスによる害・影響を形式的に低減することを保証。

## 主な貢献

1. **Average Bias-Boundedness (A-BB)**: 任意の測定可能なバイアスに対する形式的な害削減保証
2. **未知・敵対的発見バイアスにも対応**: バイアスベクトルが不明または敵対的に発見された場合も適用可能
3. **高い相関性を維持**: オリジナルランキングとの相関を61-99%維持

## 実験結果

- Arena-Hard-Autoで評価
- 4つのLLMジャッジを使用
- (τ=0.5, δ=0.01) バイアス有界保証を達成
- フォーマット・スキーマバイアス設定でほとんどのジャッジ-バイアス組み合わせが80%超の相関

## 注目ポイント

- 自律的AIシステムの信頼性向上
- 理論的保証と実践的性能の両立
- コード公開
