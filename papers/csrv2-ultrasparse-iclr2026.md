---
layout: paper
title: "CSRv2: 超スパース埋め込みの実用化"
date: 2026-02-07
arxiv_id: "2602.05735"
categories: [cs.LG, cs.IR, Embeddings]
---

# CSRv2: Unlocking Ultra-Sparse Embeddings

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.05735
- **著者**: Lixuan Guo, Yifei Wang, Tiansheng Wen, **Stefanie Jegelka** (MIT), Chenyu You 他
- **採択**: **ICLR 2026**

## 概要
超スパース埋め込み（k=2〜4の活性ニューロン）を実用レベルに引き上げる訓練手法。密な埋め込みと比較して**最大300倍**の計算・メモリ効率を達成。

## 技術的ポイント
- **Progressive k-annealing**: スパース性学習の安定化
- **Supervised contrastive objectives**: 表現品質の向上
- **Full backbone finetuning**: エンドツーエンドの適応性確保
- **Dead neuron問題の解決**: 80%→20%に削減

## 実験結果
| 設定 | CSRv2改善（vs CSR） |
|------|---------------------|
| k=4（テキスト） | +7% |
| k=2（テキスト） | +14% |
| k=4（ビジョン） | +4% |
| k=2（ビジョン） | +6% |

- **MRLと同等の性能**をわずか2活性特徴で達成
- MRL比で**7倍の高速化**

## 注目ポイント
- **ICLR'26採択**
- エッジデバイスへのAIデプロイに直結する技術
- テキスト・ビジョン両方で有効性を実証
