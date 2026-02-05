---
layout: paper
title: "When Silence Is Golden: LLM Abstention in Temporal QA"
date: 2026-02-06
arxiv_id: "2602.04755"
categories: ["cs.CL", "cs.AI"]
venue: "ICLR'26"
---

# When Silence Is Golden: LLM Abstention in Temporal QA

**arXiv**: https://arxiv.org/abs/2602.04755

**採択**: ICLR 2026

## 概要

LLMが不確実な場合に「答えない」（abstain）能力を、時間的QAタスクで訓練する初の実証研究。

## 問題意識

- LLMは不確実性を認めず、流暢だが誤解を招く回答を生成しがち
- 時間的QAでは、時間に敏感な証拠を無視し、異なる時期の事実を混同
- 既存のキャリブレーション手法は複雑な推論での不確実性を捉えられない

## 提案手法

- **Abstentionを教えられるスキル**として定式化
- Chain-of-Thought (CoT) 教師あり学習 + abstention-aware報酬によるRL

## 主な発見

1. **RLの有効性**: Qwen2.5-1.5B-InstructベースでGPT-4oをExact Matchで上回る
   - TimeQA-Easy: +3.46%
   - TimeQA-Hard: +5.80%
   - 回答不能質問のTrue Positive率: SFTより20%向上

2. **SFTの問題**: 過信を誘発し信頼性を損なう
3. **RLの課題**: 精度は向上するが同様のリスクあり
4. **暗黙的情報の限界**: コンテキストやKGなどの暗黙的推論手がかりは、明示的CoT教師ありに比べ効果薄い

## 所感

「答えない」という能力は実用的なLLMにとって極めて重要。この研究は推論と棄権を共同最適化する基盤を提供し、より信頼性の高いLLM構築への道を開く。
