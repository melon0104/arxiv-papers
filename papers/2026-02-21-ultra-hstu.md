# ULTRA-HSTU: Bending the Scaling Law Curve in Large-Scale Recommendation Systems

- **arXiv ID**: 2602.16986
- **カテゴリ**: cs.IR (情報検索)
- **投稿日**: 2026-02-19
- **URL**: https://arxiv.org/abs/2602.16986

## 著者
Qin Ding, Kevin Course, Linjian Ma, Jianhui Sun, et al.

## 選定理由
✅ **実運用記載**: 数十億ユーザーに本番デプロイ済み、4-8%のエンゲージメント改善

## 概要
シーケンシャル推薦モデルのスケーリング効率を大幅に改善したULTRA-HSTUを提案。モデルとシステムの共同設計により、学習・推論の両方で既存手法を大幅に上回る効率を実現。

## 主要な貢献
1. **入力シーケンス設計の革新**: ユーザー行動履歴の効率的な表現
2. **Sparse Attention Mechanisms**: Self-attentionの二次計算コストを回避
3. **モデルトポロジーの最適化**: 品質と効率のバランスを改善

## 実験結果
- **学習スケーリング**: 従来モデル比 **5倍以上高速**
- **推論スケーリング**: 従来モデル比 **21倍高速**
- **本番環境**: 数十億ユーザーへのサービスで **4-8%の消費・エンゲージメント改善**

## 技術的詳細
- Cross-attentionに依存せず、self-attentionの表現力を維持
- End-to-endでのモデル・システム共同設計

## 産業的インパクト
- 大規模推薦システムの実運用で検証済み
- Scalingの効率化により計算コストを大幅削減
