# Fun-DDPS: Function-Space Decoupled Diffusion for Carbon Capture and Storage

[📄 arXiv:2602.12274](https://arxiv.org/abs/2602.12274)

## 概要
CO2回収貯留（CCS）のための順問題・逆問題モデリング。疎な観測からのill-posedな逆問題を解決する生成フレームワーク。

## 提案手法
**Fun-DDPS**：
- 関数空間拡散モデル＋微分可能ニューラルオペレータサロゲートを統合
- 単一チャネル拡散モデルで地質パラメータ（ジオモデル）の事前分布を学習
- **Local Neural Operator (LNO)** サロゲートが物理整合的なガイダンスを提供
- 拡散事前分布とサロゲートの分離により、欠損情報の頑健な復元とデータ同化を実現

## 実験結果
**順問題（25%観測のみ）**：
- Fun-DDPS: **7.7%** 相対誤差
- 標準サロゲート: 86.9%（11倍改善）

**逆問題**：
- 漸近的に正確なRejection Samplingとの比較で初の厳密検証
- JS divergence 0.06未満を達成
- 物理的に整合的な実現を高周波アーティファクトなしで生成
- サンプル効率4倍改善

## 注目ポイント
- CCS（カーボンニュートラル技術）への応用
- 極端なデータ疎性への対応力

## カテゴリ
cs.LG, physics.geo-ph
