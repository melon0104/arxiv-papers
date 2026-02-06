---
layout: paper
title: "DFlash: ブロック拡散による高速推論デコーディング"
date: 2026-02-07
arxiv_id: "2602.06036"
categories: [cs.CL, LLM, Inference]
---

# DFlash: Block Diffusion for Flash Speculative Decoding

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.06036
- **著者**: Jian Chen, Yesheng Liang, Zhijian Liu

## 概要
軽量なブロック拡散モデルを用いた**投機的デコーディング**フレームワーク。単一フォワードパスでドラフトトークンを並列生成し、ターゲットモデルで検証。

## 技術的ポイント
- **並列ドラフティング**: 従来の逐次的自己回帰ドラフトを置き換え
- **Context Features**: ターゲットモデルから抽出した文脈特徴でドラフトを条件付け
- **高い受理率**: 効率的ドラフティングと高品質出力を両立

## 実験結果
| 手法 | 高速化率 |
|------|----------|
| EAGLE-3 | ベースライン |
| **DFlash** | **最大2.5倍** |

- 複数モデル・タスクで**6倍以上のロスレス高速化**を達成
- SOTA手法EAGLE-3に対して最大2.5倍のスピードアップ

## 注目ポイント
- 拡散モデルのLLM推論への新しい応用
- 実用的な高速化を実現
- speculative decodingの新パラダイム
