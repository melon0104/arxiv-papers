---
layout: paper
date: 2026-03-16
title: "Simple Recipe: VLAs are Natural Continual Learners with RL"
arxiv_id: "2603.11653"
categories: [cs.LG, cs.RO]
---

# Simple Recipe: VLAs are Natural Continual Learners with RL

## 基本情報
- **arXiv ID**: 2603.11653
- **カテゴリ**: cs.LG, cs.RO
- **機関**: UT Austin
- **GitHub**: https://github.com/UT-Austin-RobIn/continual-vla-rl

## 概要
Vision-Language-Action (VLA)モデルにおける継続強化学習を体系的に調査。通説に反し、LoRA付きの単純なSequential Fine-Tuningが驚くほど強力であることを発見。

## 主な成果
- Sequential FT + LoRAは**高い可塑性、忘却ほぼなし**
- ゼロショット汎化を維持しつつ、より複雑なCRL手法を頻繁に上回る
- 大規模事前学習モデル + パラメータ効率的適応 + オンポリシーRLの**シナジー**

## 注目ポイント
- 従来の「catastrophic forgetting」の懸念がVLA+LoRAでは当てはまらない
- Sequential FTが継続RLの**強力なベースライン**に
- 大規模モデル時代の生涯学習に新しい洞察
