---
layout: paper
title: "RAL: Reinforced Attention Learning for Multimodal LLMs"
date: 2026-02-06
arxiv_id: "2602.04884"
categories: ["cs.CL", "cs.CV", "cs.LG"]
---

# RAL: Reinforced Attention Learning

**arXiv**: https://arxiv.org/abs/2602.04884

## 概要

マルチモーダルLLM（MLLM）のポストトレーニングにおいて、出力トークン列ではなく**内部アテンション分布を直接最適化**する新しいRL手法「RAL」を提案。

## 問題意識

- RLによるポストトレーニングはLLMの推論を大幅に改善
- しかしMLLMに同じアプローチ（verbose rationales）を適用しても知覚タスクでの効果は限定的
- 場合によっては性能が**低下**することも

## 提案手法: Reinforced Attention Learning

- **最適化対象の転換**: 「何を生成するか」→「どこに注目するか」
- Policy gradient frameworkでアテンション分布を直接最適化
- 複雑なマルチモーダル入力での情報配分とgroundingを改善

## 追加貢献: On-Policy Attention Distillation

- 潜在的なアテンション挙動を転移
- 標準的なKnowledge Distillationより強いcross-modal alignmentを実現

## 実験結果

- 多様な画像・動画ベンチマークでGRPO等のベースラインを一貫して上回る
- アテンションポリシーがマルチモーダルポストトレーニングの原理的な代替手段として有効

## 所感

「何を生成するか」ではなく「どこを見るか」を最適化するという発想の転換が斬新。MLLMの知覚能力向上に新しい方向性を示す重要な研究。
