---
layout: paper
title: "Debiasing Sequential Recommendation with Time-aware Inverse Propensity Scoring"
date: 2026-03-08
categories: [cs.IR, cs.AI]
---

# Debiasing Sequential Recommendation with Time-aware Inverse Propensity Scoring

- **arXiv**: [2603.04986](https://arxiv.org/abs/2603.04986)
- **著者**: Sirui Huang et al.
- **コード**: 公開予定

## 概要

逐次推薦（Sequential Recommendation）における選択バイアスと露出バイアスを解決するTime-aware Inverse Propensity Scoring（TIPS）を提案。従来のIPSは静的で時系列依存性を捉えられなかったが、TIPSは動的にユーザー行動の時間的変化を考慮する。

## 問題設定

- **選択バイアス**: 露出されたがクリックされなかったアイテムを「興味なし」と誤解釈
- **露出バイアス**: 露出されなかったアイテムを「無関係」として扱う
- 従来のIPS手法は時系列依存性を捉えられない

## 主な貢献

1. **Time-aware IPS（TIPS）**: 時系列依存性と時間的ダイナミクスを考慮
2. **プラグイン型設計**: 様々な逐次推薦モデルに適用可能
3. **反実仮想推論**: 仮想的な露出下でのユーザー嗜好を推定

## 実験結果

- 複数の逐次推薦モデルで一貫した性能向上
- プラグイン方式で容易に既存モデルを改善可能
