---
layout: paper
title: "EchoSafe: Evolving Contextual Safety in Multi-Modal Large Language Models"
date: 2026-03-19
arxiv_id: "2603.15800"
categories: ["cs.CV", "cs.CL", "cs.CR"]
venue: "CVPR 2026"
---

# EchoSafe: Evolving Contextual Safety in Multi-Modal Large Language Models via Inference-Time Self-Reflective Memory

## 基本情報

| 項目 | 内容 |
|------|------|
| arXiv | [2603.15800](https://arxiv.org/abs/2603.15800) |
| 採択 | **CVPR 2026** |
| GitHub | https://echosafe-mllm.github.io |

## 概要

マルチモーダルLLM（MLLM）のコンテキスト安全性評価に特化した新ベンチマーク **MM-SafetyBench++** と、自己反省型メモリを活用した推論時フレームワーク **EchoSafe** を提案。

## 問題設定

- 既存の安全性研究は明示的に危険な入力の検出・拒否に集中
- **コンテキスト安全性**（微妙な文脈の違いによる安全意図の分岐）は見落とされていた
- 似た入力でも文脈次第で安全/危険が分かれる状況への対応が課題

## 提案手法

### MM-SafetyBench++
- 各unsafe画像-テキストペアに対し、最小限の修正で安全なカウンターパートを構築
- 文脈理解に基づいた安全性判断能力を制御的に評価

### EchoSafe
- **自己反省型メモリバンク**を維持
- 過去のインタラクションから安全性に関する知見を蓄積・検索
- 関連する過去の経験を現在のプロンプトに統合
- 推論時に文脈依存の安全性推論を実現

## 主要な結果

- 複数のマルチモーダル安全性ベンチマークで一貫した性能向上
- **訓練不要**で既存モデルに適用可能
- コンテキスト安全性の強力なベースラインを確立

## 技術的貢献

1. コンテキスト安全性評価のための新ベンチマーク
2. 自己反省メモリによる推論時安全性強化フレームワーク
3. 継続的な安全性行動の進化機構

## 意義

MLLMの安全性を「単純な拒否」から「文脈理解に基づく適応的判断」へと進化させる重要な一歩。
