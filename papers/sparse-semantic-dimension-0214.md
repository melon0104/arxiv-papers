---
layout: paper
title: "Sparse Semantic Dimension: LLM汎化の新理論"
---

# Sparse Semantic Dimension as a Generalization Certificate for LLMs

## 基本情報
- **arXiv**: https://arxiv.org/abs/2602.11388
- **カテゴリ**: cs.LG, cs.CL
- **著者**: Dibyanayan Bandyopadhyay et al.
- **投稿日**: 2026-02-11
- **GitHub**: https://github.com/newcodevelop/sparse-semantic-dimension

## 選定理由
✅ **コード公開**: GitHubでコード公開
✅ **理論的貢献**: LLM汎化の新しい理論的フレームワーク

## 概要
統計的学習理論はLLMsがパラメータ数が訓練トークン数を大幅に超えるため過学習すると予測するが、実際には頑健に汎化。本論文は汎化を制御する有効容量がモデルの内部表現の幾何学にあると提案。

## 技術的貢献
- **Sparse Semantic Dimension (SSD)**: Sparse Autoencoder（SAE）のアクティブ特徴語彙から導出される複雑性尺度
- **汎化帰属**: モデルの汎化能力を総パラメータ数ではなく辞書のスパース性に帰属
- **Feature Sharpness Scaling Law**: Gemma-2Bは1桁大きいにもかかわらず、GPT-2よりも少ないキャリブレーションサンプルでアクティブマニフォールドを特定

## 実験結果
- GPT-2 SmallとGemma-2Bで検証
- 現実的なサンプルサイズで非自明な証明書を提供
- OOD入力は「特徴爆発」を引き起こし、認識論的不確実性を示す

## 所感
スーパーポジション仮説の理論的証拠を提供。安全監視としての応用も興味深い。
