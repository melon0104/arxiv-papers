# VisionCreator-R1: A Reflection-Enhanced Native Visual-Generation Agentic Model

## 基本情報
- **arXiv ID**: 2603.08812
- **タイトル**: VisionCreator-R1: A Reflection-Enhanced Native Visual-Generation Agentic Model
- **著者**: Jinxiang Lai, Wenzhe Zhao, Zexin Lu, Hualei Zhang 他
- **投稿日**: 2026-03-11
- **URL**: https://arxiv.org/abs/2603.08812

## 概要
視覚コンテンツ生成は単一画像からマルチ画像ワークフローへと進化したが、既存のエージェントは計画駆動のままで、軌跡途中の視覚エラーを修正する**体系的なリフレクションメカニズム**が欠如。

## 提案手法: VisionCreator-R1
**明示的リフレクション付きネイティブ視覚生成エージェント**と**Reflection-Plan Co-Optimization (RPCO)**学習方法論：

### RPCO訓練方法論
強化学習（RL）での観察：計画とリフレクションの間に**最適化非対称性**が存在
- 計画はプラン報酬で確実に最適化可能
- リフレクション学習はノイジーなクレジット割り当てで阻害

### 解決策
1. **SFT段階**: VCR-SFTデータセット（リフレクション強シングル画像軌跡＋計画強マルチ画像軌跡）で訓練
2. **RL段階**: VCR-RLデータセットでRLによる共同最適化

## 実験結果
VisionCreator-R1は既存ベンチマークとVCR-bench（シングル画像・マルチ画像タスク）で**Gemini2.5Pro**を一貫して上回る。

## 注目ポイント
- 🔄 **リフレクション機構**: 視覚生成エージェント初の体系的エラー修正
- 📊 **Gemini2.5Pro超え**: シングル・マルチ画像両タスクで
- 🎯 **非対称性発見**: 計画vs.リフレクション最適化の違いを解明

## カテゴリ
cs.CV

## 関連タグ
#視覚生成 #エージェント #リフレクション #RL #マルチモーダル
