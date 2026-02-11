# ST4VLA: Spatially Guided Training for Vision-Language-Action Models

## 基本情報
- **arXiv**: [2602.10109](https://arxiv.org/abs/2602.10109)
- **カテゴリ**: cs.RO
- **投稿日**: 2026-02-10
- **採択**: **ICLR 2026**
- **プロジェクト**: [internrobotics.github.io](https://internrobotics.github.io/internvla-m1.github.io/)

## 一言まとめ
**ICLR 2026採択**: 空間誘導訓練でVLAを強化。Google Robotで66.1→**84.6**、SimplerEnvで新SOTA。

## 概要
大規模VLMはマルチモーダル理解に優れるが、低レベル運動制御を要するEmbodiedタスクでは不十分。ST4VLAは空間誘導訓練でアクション学習をVLMの空間事前知識と整合させるデュアルシステムVLAフレームワーク。

## 技術的貢献
- **2段階訓練**: (i) 空間接地事前訓練: Web規模＋ロボット特化データで転移可能な事前知識を獲得 (ii) 空間誘導アクション後訓練: 空間プロンプティングでリッチな空間事前知識を生成しアクション生成をガイド
- **空間プロンプティング**: ポイント、ボックス、軌跡予測をスケーラブルに学習
- **空間・アクション目的の一貫した最適化**

## 実験結果
- Google Robot: 66.1 → **84.6** (+18.5)
- WidowX Robot: 54.7 → **73.2** (+18.5)
- SimplerEnvで新SOTA
- 未見オブジェクト・パラフレーズ指示への汎化
- 長期ホライゾン摂動への実世界ロバスト性

## 選定理由
✅ トップ会議採択 (ICLR 2026)
✅ 大幅な性能向上を実証
