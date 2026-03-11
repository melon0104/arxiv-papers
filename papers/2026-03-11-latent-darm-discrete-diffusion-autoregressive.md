# Latent-DARM: Bridging Discrete Diffusion And Autoregressive Models For Reasoning

## 基本情報
- **arXiv ID**: 2603.09184
- **タイトル**: Latent-DARM: Bridging Discrete Diffusion And Autoregressive Models For Reasoning
- **著者**: Lina Berrayana, Ahmed Heakl, Abdullah Sohail, Thomas Hofmann, Salman Khan, Wei Chen
- **投稿日**: 2026-03-11
- **URL**: https://arxiv.org/abs/2603.09184

## 概要
マルチエージェントシステムは自己回帰言語モデル（ARM）に依存することが多いが、ARMは逐次生成に制限される。一方、離散拡散言語モデル（DDLM）は非逐次的でグローバルに修正可能な生成を可能にし強力な計画能力を示すが、テキスト流暢性は限定的でARMとの直接協業が困難。

## 提案手法: Latent-DARM
**潜在空間コミュニケーションフレームワーク**：
- DDLM（プランナー）とARM（実行者）を橋渡し
- テキストベースインターフェースではなく潜在空間で連携
- マルチエージェント協調の利点を最大化

## 実験結果
数学、科学、常識推論ベンチマークで評価：
- テキストベースインターフェースを平均上回る
- **DART-5**: 精度27.0% → 36.0%
- **AIME2024**: 精度0.0% → 14.0%
- 最先端推論モデルに迫る性能（トークン予算**2.2%以下**で達成）

## 注目ポイント
- 🔗 **異種モデル協調**: DDLMとARMの初の潜在空間橋渡し
- 🧮 **推論能力**: 計画（DDLM）と実行（ARM）の分離
- ⚡ **効率的**: 極小トークン予算で高性能

## カテゴリ
cs.LG, cs.AI

## 関連タグ
#拡散モデル #自己回帰 #マルチエージェント #推論 #潜在空間
