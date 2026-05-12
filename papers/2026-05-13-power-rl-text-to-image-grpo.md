# Power Reinforcement Post-Training of Text-to-Image Models with Super-Linear Advantage Shaping

- **arXiv ID**: 2605.10937
- **カテゴリ**: cs.CV (コンピュータビジョン)
- **投稿日**: 2026-05-11
- **URL**: https://arxiv.org/abs/2605.10937

## 著者
Haoyuan Sun, Jing Wang, Yuxin Song, Yu Lu et al.

## 選定理由
✅ **トレンド**: GRPO/RL後訓練のT2Iへの応用という最先端トピック
✅ **問題解決**: 報酬ハッキング問題という実用上の重要課題に取り組む

## 概要
GRPOを中心としたRLベースの後訓練はText-to-Image (T2I)モデルの改善に有望なパラダイムだが、「報酬ハッキング」（不完全な報酬関数のバイアスを悪用して見かけ上の性能を上げる）という問題がある。本論文はSuper-Linear Advantage Shapingにより正規化の誤較正を特定・解決し、真の性能向上を実現する新手法を提案。

## 主要な貢献
1. **正規化誤較正の特定**: プロンプトレベル正規化が報酬ハッキングを誘発することを発見
2. **Super-Linear Advantage Shaping**: 高品質サンプルへの超線形報酬付与で真の改善を促進
3. **報酬ハッキング防止**: バイアス悪用を防ぐ新しい最適化フレームワーク

## 実験結果
- GenEval、DPG-Benchなど複数ベンチマークで従来のGRPOを上回る
- 報酬スコアと実際の画質の相関が改善

## インパクト
T2I生成モデルのRL後訓練の信頼性を高める重要研究。DALL-E・Midjourney・Stable Diffusion等の後訓練改善に応用可能。
