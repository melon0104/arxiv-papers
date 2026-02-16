---
layout: paper
title: "DiffuRank: Effective Document Reranking with Diffusion Language Models"
date: 2026-02-17
arxiv_id: "2602.12528"
category: cs.CL
tags: [llm, diffusion, reranking, information-retrieval, github]
---

# DiffuRank: Effective Document Reranking with Diffusion Language Models

## 基本情報
- **arXiv**: [2602.12528](https://arxiv.org/abs/2602.12528)
- **GitHub**: [liuqi6777/DiffusionRank](https://github.com/liuqi6777/DiffusionRank)
- **著者**: Qi Liu, Kun Ai, Jiaxin Mao et al.
- **機関**: Renmin University, Alibaba

## 一言まとめ
拡散言語モデル(dLLM)を文書リランキングに適用。自己回帰モデルの固定的な左から右への生成順序の制約を克服し、柔軟なデコーディングと並列処理を実現。

## 課題
- 既存LLMリランカーは自己回帰生成に依存
- トークンごとのデコードによる高レイテンシ
- 左から右への固定順序で初期予測エラーが伝播

## 提案手法: DiffuRank
### 3つのリランキング戦略
1. **Pointwiseアプローチ**: dLLMで各クエリ-文書ペアの関連性を推定
2. **Logitベース Listwiseアプローチ**: 複数文書の関連性を同時評価、モデルロジットから直接ランキング
3. **Permutationベース Listwiseアプローチ**: dLLMのデコーディングプロセスをリランキングタスクに適応

### 各アプローチ用の学習手法も設計

## 実験結果
- dLLMは同サイズの自己回帰LLMと同等以上の性能
- ゼロショット・ファインチューニング両方で評価
- 複数ベンチマークで有効性を実証

## キーポイント
- 拡散LLMのリランキングへの初の本格適用
- 並列デコーディングによる効率化の可能性
- コード公開で再現性確保
