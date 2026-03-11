# The $qs$ Inequality: Quantifying the Double Penalty of MoE at Inference

## 基本情報
- **arXiv ID**: 2603.08960
- **タイトル**: The $qs$ Inequality: Quantifying the Double Penalty of Mixture-of-Experts at Inference
- **著者**: Vignesh Adhinarayanan, Nuwan Jayasena
- **投稿日**: 2026-03-11
- **URL**: https://arxiv.org/abs/2603.08960

## 概要
Mixture-of-Experts（MoE）モデルは低学習FLOPsで高品質を達成するが、この効率性は推論時に消失することが多い。本研究は**二重ペナルティ**を特定：
1. エキスパートルーティングがマイクロバッチを断片化し重み再利用を減少
2. 大規模な常駐エキスパートプールがKVキャッシュ用のHBMヘッドルームを減少

## $qs$不等式
MoEが構造的に不利になる条件を予測する基準を導入：
- **s（sparsity）**: トークンあたりに活性化されるパラメータの割合
- **q（quality-equivalence factor）**: 密モデルがMoE性能にマッチするために必要なサイズ倍率

## 実証評価
DeepSeek-V3、Qwen3-235B、Grok-1、Switch-Cを含むフロンティアモデルで評価：
- この断片化は一般的なアーキテクチャ現象
- **DeepSeek-V3（128kコンテキスト）**: 品質マッチ密ベースラインが**4.5倍のスループット優位**
- Switch-Cのような大規模アーキテクチャは、品質マッチ密モデルが実行可能なクラスタサイズで実行不能に

## 含意
- 学習時FLOP効率は推論時性能の不完全なプロキシ
- MoEは「学習時最適化」として捉え、密モデルへの蒸留が推論効率的展開への道筋

## 注目ポイント
- 📊 **DeepSeek-V3分析**: 最新MoEモデルの推論ボトルネックを解明
- ⚡ **4.5x差**: 長コンテキストでの密モデル優位を定量化
- 🔧 **設計指針**: MoEの適切なユースケースを明確化

## カテゴリ
cs.LG, cs.AR, cs.DC

## 関連タグ
#MoE #推論効率 #DeepSeek #アーキテクチャ分析 #HBM
