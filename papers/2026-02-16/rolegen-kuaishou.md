---
layout: paper
title: "RoleGen: Generative Recommendation with Counterfactual Functional Role Reasoning"
date: 2026-02-17
arxiv_id: "2602.13134"
category: cs.IR
tags: [recommender-systems, llm, production, kuaishou, e-commerce]
---

# RoleGen: Awakening Dormant Users: Generative Recommendation with Counterfactual Functional Role Reasoning

## 基本情報
- **arXiv**: [2602.13134](https://arxiv.org/abs/2602.13134)
- **著者**: Huishi Luo, Shuokai Li, Hanchen Yang, Zhongbo Sun et al. (Kuaishou)
- **機関**: Kuaishou（快手）

## 🏭 Industry Deployment
**Kuaishou Eコマースプラットフォームで大規模運用中**

## 一言まとめ
休眠ユーザー（engaged but低コンバージョン）を活性化するLLM推薦フレームワーク。アイテムの「Functional Role」を明示的にモデル化し、コンバージョン軌跡を反実仮想推論でシミュレーション。

## 課題
- 休眠ユーザー：エンゲージメントはあるがコンバージョンが低い
- 既存手法：アイテムの即時価値（クリック確率など）のみを推定
- アイテムの「道具的効果」（Instrumental Effect）を無視

## 提案手法: RoleGen
1. **Conversion Trajectory Reasoner** (LLMベース)
   - アイテムの文脈依存「Functional Role」をモデル化
   - 意図進化の再構成
   - 反実仮想推論で多様なコンバージョン経路をシミュレート
   
2. **Generative Behavioral Backbone**
   - 推論→実行→フィードバック→反省のクローズドループ学習

## 実験結果
### オフライン
- **Recall@1**: +6.2%

### オンラインA/Bテスト (Kuaishou Eコマース)
- **注文数**: +7.3%

## キーポイント
- 休眠ユーザー活性化という実用的な問題設定
- LLMを推薦の「意図推論」に活用
- 大規模Eコマースでの実証済み効果
