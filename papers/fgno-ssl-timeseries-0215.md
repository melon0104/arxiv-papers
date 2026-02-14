# FGNO: Flow-Guided Neural Operator for Self-Supervised Learning on Time-Series

[📄 arXiv:2602.12267](https://arxiv.org/abs/2602.12267)

## 概要
時系列データの自己教師あり学習（SSL）の新フレームワーク。Masked Autoencoderの固定マスキング率の限界を克服。

## 提案手法
**FGNO (Flow-Guided Neural Operator)**：
- 破損レベルを表現学習の新たな自由度として扱う
- オペレータ学習＋フローマッチングを統合
- Short-Time Fourier Transformで異なる時間解像度を統一
- 異なるネットワーク層・フロー時刻で多様なノイズ強度を適用
- 低レベルパターンから高レベルグローバル特徴まで豊かな階層的特徴を抽出

## 推論の工夫
- 先行手法はノイズ入力で推論 → **クリーン入力**を使用
- ランダム性を排除し精度向上

## 実験結果（バイオメディカル3ドメイン）
- BrainTreeBank（神経信号デコーディング）: **+35% AUROC**
- DREAMT（皮膚温度予測）: **-16% RMSE**
- SleepEDF（低データ条件）: **+20%超** 精度・Macro-F1改善

## 注目ポイント
- データ不足に対するロバスト性
- マルチレゾリューション時系列への適用力

## カテゴリ
cs.LG
