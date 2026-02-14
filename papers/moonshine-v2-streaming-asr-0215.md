# Moonshine v2: Ergodic Streaming Encoder ASR for Latency-Critical Speech Applications

[📄 arXiv:2602.12241](https://arxiv.org/abs/2602.12241)

## 概要
リアルタイム音声アプリケーション（ライブ転写・音声コマンド・リアルタイム翻訳）向けの低レイテンシASRモデル。

## 課題認識
- Full-attention Transformerは精度が高いが、シーケンス長に対して二次複雑度
- ストリーミングではTTFT（最初のトークンまでの時間）が発話長に比例して増加

## 提案手法
**Moonshine v2**：
- Ergodic streaming-encoder ASRモデル
- Sliding-window self-attentionで有界・低レイテンシ推論を実現
- 強力なローカルコンテキストを維持

## 実験結果
- 標準ベンチマークでSOTA WER（単語誤り率）を達成
- **6倍大きいモデルと同等の精度**を達成
- 大幅に高速な推論

## 注目ポイント
- エッジデバイス向け対話型音声インターフェースの新可能性
- ローカルアテンションでフルアテンションに匹敵する精度

## カテゴリ
cs.CL, cs.LG, cs.SD
