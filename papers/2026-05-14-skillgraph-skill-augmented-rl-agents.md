---
layout: paper
title: "SkillGraph: Skill-Augmented Reinforcement Learning for Agents via Evolving Skill Graph"
date: 2026-05-14
category: cs.CL
arxiv_id: "2605.12039"
url: https://arxiv.org/abs/2605.12039
authors:
  - Xiaoyuan Li
  - Moxin Li
  - Keqin Bao
tags: [agent, skill-library, reinforcement-learning, graph, compositional]
---

# SkillGraph: Skill-Augmented Reinforcement Learning for Agents via Evolving Skill Graph

## 概要

LLMエージェントのスキルライブラリ問題に取り組む研究。現状のスキルライブラリは孤立したエントリーとして保存し意味的類似度のみで検索するため、複合タスクで2つの課題が生じる：(1) 関連スキルのみでなく依存関係も特定が必要、(2) スキルのマージ・分割判断のための構造的手がかりがない。

SkillGraphは**進化するスキルグラフ**でスキル間の依存関係を構造化し、複合タスクでの効率的なスキル選択・更新を実現。

## 選定理由

- エージェントのスキル管理という実用的かつ重要なトピック
- グラフ構造による構造化スキルライブラリの新アプローチ
- 複合タスクへの対応という実運用課題への取り組み

## キーポイント

- **課題**: 孤立したスキルエントリーでは依存関係を捉えられない
- **手法**: 進化するスキルグラフでスキル間依存関係を構造化
- **効果**: 複合タスクでの適切なスキル選択と保守が可能に

## arXiv

https://arxiv.org/abs/2605.12039
