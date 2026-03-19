---
layout: default
title: "LLM NL2SQL Robustness: Surface Noise vs. Linguistic Variation"
---

# LLM NL2SQL Robustness: Surface Noise vs. Linguistic Variation in Traditional and Agentic Settings

[arXiv:2603.17017](https://arxiv.org/abs/2603.17017) | cs.CL

## 著者
Lifu Tu et al.

## 一言まとめ
NL2SQLの**ロバストネス評価ベンチマーク**。Grok-4.1、Gemini-3-Pro、Claude-Opus-4.6、GPT-5.2を評価し、表面ノイズと言語的変動への脆弱性を特定。

## 概要
NL2SQLシステムのロバストネス評価は、実世界のデータベース環境が動的でノイジーかつ常に進化するため不可欠。従来のベンチマーク評価は静的スキーマと整形された入力を前提とする。本研究は約10種類の摂動を含むロバストネス評価ベンチマークを導入し、従来型とエージェンティック設定の両方で評価。

## 注目ポイント
- **最新LLM評価**: Grok-4.1、Gemini-3-Pro、Claude-Opus-4.6、GPT-5.2
- **設定別分析**: 従来パイプラインvs.エージェンティック設定
- **摂動タイプ分析**: 表面ノイズは従来型で、言語的変動はエージェンティック設定でより影響大
- **実用的示唆**: ロバストNL2SQL実現への残課題を明確化

## 技術的詳細
- 約10種類の摂動タイプを定義
- 表面レベルノイズ: 文字レベル破損等
- 言語的変動: 意味を保持しつつ語彙・構文形式を変更
- 両設定での性能劣化パターンを分析

## 関連リンク
- [arXiv](https://arxiv.org/abs/2603.17017)
- [PDF](https://arxiv.org/pdf/2603.17017)
