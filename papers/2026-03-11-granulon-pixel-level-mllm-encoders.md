# Granulon: Awakening Pixel-Level Visual Encoders with Multi-Granularity Semantics for MLLM

## 基本情報
- **arXiv ID**: 2603.08800
- **タイトル**: Granulon: Awakening Pixel-Level Visual Encoders with Adaptive Multi-Granularity Semantics for MLLM
- **著者**: Junyuan Mao, Qiankun Li, Linghao Meng, Zhicheng He 他
- **投稿日**: 2026-03-11
- **URL**: https://arxiv.org/abs/2603.08800

## 概要
マルチモーダル大規模言語モデルの最近の進展はCLIPベースの視覚エンコーダに大きく依存するが、CLIPはグローバルセマンティックアラインメントを強調し**細粒度視覚理解**に苦戦する。一方DINOv3は強力なピクセルレベル知覚を提供するが、粗粒度セマンティック抽象化が欠如し、マルチ粒度推論が制限される。

## 提案手法: Granulon
**DINOv3ベースのMLLMに適応的粒度拡張**を導入：
1. **テキスト条件付き粒度Controller**: テキスト入力のセマンティックスコープに応じて視覚抽象化レベルを動的調整
2. **Adaptive Token Aggregation**: 粒度ガイドのプーリング＋関係認識クラスタリングでコンパクトでセマンティックリッチな視覚トークン生成
3. **統一「pixel-to-fine-to-coarse」推論**: 単一フォワードパス内で実現

## 実験結果
広範かつ解釈可能な実験で：
- 精度**約30%向上**
- ハルシネーション**約20%削減**
- 同一設定下で全視覚エンコーダを上回る

## 注目ポイント
- 🔬 **DINOv3拡張**: ピクセルレベル＋セマンティック粒度の両立
- 🎯 **動的粒度**: テキストに応じた適応的視覚処理
- 📉 **ハルシネーション削減**: 20%の大幅改善

## カテゴリ
cs.CV

## 関連タグ
#MLLM #視覚エンコーダ #DINOv3 #粒度 #ハルシネーション
