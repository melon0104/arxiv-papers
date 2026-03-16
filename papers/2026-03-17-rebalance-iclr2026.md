# ReBalance: Efficient Reasoning with Balanced Thinking

**arXiv**: [2603.12372](https://arxiv.org/abs/2603.12372)
**カテゴリ**: cs.AI, cs.CL, cs.LG
**採択**: ICLR 2026

## 概要

Large Reasoning Models (LRMs) の**overthinking（過剰思考）**と**underthinking（思考不足）**問題を解決する訓練不要フレームワーク。

## 問題設定

- **Overthinking**: 簡単な問題に対して不必要な計算ステップを費やす
- **Underthinking**: 能力があるにもかかわらず十分な推論パスを探索しない
- 既存手法（反省キーワード抑制、推論長調整）は逆効果になりがち

## 手法: ReBalance

1. **信頼度ベースの動的制御**: 高い信頼度分散でoverthinking、一貫した過信でunderthinkingを検出
2. **推論モードプロトタイプ**: 小規模データセットから隠れ状態を集約し、ステアリングベクトルを計算
3. **動的制御関数**: リアルタイム信頼度に基づきベクトルの強度・方向を調整

## 実験結果

- **評価モデル**: 0.5B〜32Bの4モデル
- **ベンチマーク**: 数学推論、一般QA、コーディングの9つ
- **効果**: 出力冗長性を削減しながら精度向上

## GitHub

https://github.com/yu-lin-li/ReBalance

## 注目ポイント

- **ICLR 2026採択**
- Training-free、plug-and-play
- 推論効率化の実用的アプローチ
