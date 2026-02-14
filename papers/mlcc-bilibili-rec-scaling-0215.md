# MLCC: Multi-Level Compression Cross Networks for Efficient Scaling in Recommender Systems

[📄 arXiv:2602.12041](https://arxiv.org/abs/2602.12041)

## 概要
CTR/CVR予測における高次特徴量交差を効率的にモデル化。**Bilibili広告システムで本番運用中**。

## 提案手法
**MLCC (Multi-Level Compression Cross)**：階層的圧縮と動的合成による構造化特徴量交差アーキテクチャ
- 高次特徴量依存を効率的にキャプチャ
- 計算複雑度を抑制

**MC-MLCC**：マルチチャネル拡張版
- 特徴量交差を並列サブスペースに分解
- パラメータ増加を大幅に抑制しつつスケーリング

## 実験結果
- 3つの公開ベンチマーク＋大規模産業データセットで検証
- 強力なDLRMベースラインを最大**+0.52 AUC**で上回る
- 同等性能でパラメータ・FLOPsを最大**26倍削減**
- オンラインA/Bテストで実用性を検証済み

## 注目ポイント
- 🏭 **Bilibili広告システムで本番運用（deployed）**
- レイテンシ・リソース制約下での実用性

## カテゴリ
cs.IR
