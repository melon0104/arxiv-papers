---
layout: paper
title: "SoftMatcha 2: A Fast and Soft Pattern Matcher for Trillion-Scale Corpora"
arxiv_id: "2602.10908"
date: 2026-02-12
categories: [cs.CL, cs.LG, stat.ML]
github: "https://github.com/softmatcha/softmatcha2"
---

# SoftMatcha 2: Trillion-Scale Soft Search

## 基本情報
- **arXiv**: [2602.10908](https://arxiv.org/abs/2602.10908)
- **カテゴリ**: cs.CL, cs.LG, stat.ML
- **著者**: Masataka Yoneda et al.
- **プロジェクト**: [softmatcha.github.io/v2](https://softmatcha.github.io/v2/)
- **コード**: [GitHub](https://github.com/softmatcha/softmatcha2)

## 概要

1兆トークン規模のコーパスを0.3秒未満で検索可能な超高速柔軟検索アルゴリズム。置換・挿入・削除などの意味的変異を処理。

## 技術的貢献

### サフィックス配列ベース文字列マッチング
- コーパスサイズに対してスケール

### 2つのアルゴリズムアイデア
1. **ディスク対応設計による高速精密検索**
2. **動的コーパス対応プルーニング**

### 理論的保証
- 自然言語の統計的性質を活用
- クエリ長に対する指数的増加を抑制

## 性能比較

FineWeb-Edu (1.4Tトークン) での検索遅延：
- **infini-gram、infini-gram mini、SoftMatcha**より大幅に高速

## 応用

- 既存手法で検出不可能だったベンチマーク汚染を訓練コーパスから特定
- 7言語対応オンラインデモ公開
