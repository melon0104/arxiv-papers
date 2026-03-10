---
layout: paper
title: "SmartThinker: Progressive Chain-of-Thought Length Calibration for Efficient LLM Reasoning"
date: 2026-03-10
categories: [cs.CL, cs.LG]
arxiv_id: "2603.08000"
github: "https://github.com/SJTU-RTEAS/SmartThinker"
---

# SmartThinker: Progressive Chain-of-Thought Length Calibration for Efficient LLM Reasoning

## 基本情報
- **arXiv ID**: 2603.08000
- **カテゴリ**: cs.CL, cs.LG
- **投稿日**: 2026-03-09
- **GitHub**: https://github.com/SJTU-RTEAS/SmartThinker

## 著者
Chenzhi Hu, Qinzhe Hu, Yuhang Xu, Junyi Chen, Ruijie Wang, Shengzhong Liu, Jianxin Li, Fan Wu, Guihai Chen

## 概要
OpenAI o1やDeepSeek-R1のような大規模推論モデルは、長いChain-of-Thought (CoT)推論パスで高精度を達成。しかし固有の冗長性が**redundancy**と**overthinking**を引き起こす。既存手法はGRPOを活用して出力長を削減するが、静的な長さ報酬設計は問題の相対的難易度や応答長分布に動的に適応できず、**過圧縮と精度低下**を招く。

**SmartThinker**の提案：プログレッシブCoT長キャリブレーションを備えた効率的推論手法

主要貢献：
1. **訓練中の最適長動的推定**: ピーク精度での最適長を推定し、過長応答を誘導
2. **長さ報酬係数の動的調整**: 正しい推論パスへの不当なペナルティを回避
3. **精度を維持しながら長さ圧縮**: 応答長削減と精度向上の両立

## 主要結果
- **平均52.5%の長さ圧縮**で精度向上
- AIME25のような挑戦的ベンチマークで**16.6%の精度向上**
- 複数のモデルスケールとベンチマークで一貫した性能

## 技術的詳細
- GRPOベースのアプローチに動的キャリブレーション導入
- 問題難易度に応じた適応的長さ目標
- 過圧縮防止のための動的報酬調整

## 実用的意義
- 推論モデルの効率化
- 計算コスト削減（52%+のトークン削減）
- 実世界デプロイメントの実用性向上

## 関連リンク
- arXiv: https://arxiv.org/abs/2603.08000
- GitHub: https://github.com/SJTU-RTEAS/SmartThinker
