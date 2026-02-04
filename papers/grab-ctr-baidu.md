# GRAB: An LLM-Inspired Sequence-First Click-Through Rate Prediction Modeling Paradigm

## 概要
Baiduによる生成的CTR予測フレームワーク。従来のDLRM（Deep Learning Recommendation Models）のボトルネックを打破し、LLMのスケーリング成功を推薦システムに適用。

## 主要貢献
- **Causal Action-aware Multi-channel Attention (CamA)**: 時系列ダイナミクスを効果的に捕捉する新しいアテンション機構
- End-to-end生成フレームワークでCTR予測を再定式化
- LLMスケーリング則を推薦タスクに適用

## 技術詳細
- シーケンス優先パラダイム：ユーザー行動列を生成モデルとして処理
- マルチチャネルアテンションで異種シグナルを統合
- 因果関係を考慮した動的な特徴量集約

## 注目ポイント
🏢 **Baidu** - 実運用システムへの適用を想定した設計

## リンク
- arXiv: https://arxiv.org/abs/2602.01865
