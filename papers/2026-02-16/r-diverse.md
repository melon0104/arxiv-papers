---
layout: paper
title: "R-Diverse: Mitigating Diversity Illusion in Self-Play LLM Training"
date: 2026-02-17
arxiv_id: "2602.13103"
category: cs.LG
tags: [llm, self-play, reinforcement-learning, reasoning, github]
---

# R-Diverse: Mitigating Diversity Illusion in Self-Play LLM Training

## 基本情報
- **arXiv**: [2602.13103](https://arxiv.org/abs/2602.13103)
- **GitHub**: [Gengsheng-Li/R-Diverse](https://github.com/Gengsheng-Li/R-Diverse)
- **著者**: Gengsheng Li, Jinghan He, Shijie Wang et al.

## 一言まとめ
Self-Play LLM推論学習における「多様性幻想」問題を特定し、Memory-Augmented PenaltyとSkill-Aware Measurementで解決。

## 課題: Diversity Illusion
Self-Playでは初期の改善が学習が進むと劣化する現象が発生

1. **Local Diversity Illusion**: バッチ内のみで多様性を強制→イテレーション間でモードサイクリング
2. **Surface Diversity Illusion**: 表面的には多様だが同一の推論スキルを要求

## 提案手法: R-Diverse
### Memory-Augmented Penalty (MAP)
- 永続的メモリバンクを使用
- イテレーション間のリサイクリングを抑制

### Skill-Aware Measurement (SAM)
- 表面的な問題のバリエーションではなく、使用される推論スキルで多様性を評価

## 実験結果
### 10の数学・汎用推論ベンチマーク
- より多くのイテレーションで持続的な改善を維持
- 既存のSelf-Play手法を一貫して上回る

## キーポイント
- Self-Play学習の重要な失敗モードを特定
- 真の多様性を確保するメカニズム
- コード公開で再現可能
