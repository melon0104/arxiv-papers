---
layout: paper
title: "MoDA: Mixture-of-Depths Attention"
date: 2026-03-18
arxiv_id: "2603.15619"
categories: ["cs.CL", "cs.AI"]
importance: "★★★"
---

# MoDA: Mixture-of-Depths Attention

## 基本情報
- **arXiv ID**: 2603.15619
- **タイトル**: Mixture-of-Depths Attention
- **著者**: Lianghui Zhu, Yuxin Fang, Bencheng Liao, et al.
- **投稿日**: 2026-03-16
- **分野**: cs.CL, cs.AI
- **コード**: https://github.com/hustvl/MoDA

## 概要
LLMの深層化に伴う信号劣化問題（浅い層で形成された特徴が深い層で希釈される）を解決するMixture-of-Depths Attention (MoDA)を提案。各アテンションヘッドが現在のレイヤーのKVペアだけでなく、先行レイヤーの「深度KVペア」にもアテンドできる機構。

## 技術的貢献
- **深度方向アテンション**: 従来のシーケンス方向に加え、レイヤー深度方向にもアテンションを拡張
- **高効率アルゴリズム**: 非連続メモリアクセスパターンを解決し、64Kシーケンスで FlashAttention-2 の 97.3% 効率を達成
- **Post-normとの相性**: pre-normよりpost-normとの組み合わせでより良い性能

## 実験結果
- **ベースライン比較**: 10個の検証ベンチマークで平均パープレキシティ 0.2 改善
- **下流タスク**: 10個の下流タスクで平均 2.11% 性能向上
- **計算コスト**: わずか 3.7% の FLOPs オーバーヘッド

## 意義
深層LLMのスケーリングにおける新しいプリミティブとして、深度方向の情報フローを明示的にモデル化。コード公開済み。
