# MonarchRT: Efficient Attention for Real-Time Video Generation

## メタ情報
- **arXiv ID**: 2602.12271
- **カテゴリ**: cs.CV, cs.LG
- **投稿日**: 2026-02-12
- **機関**: CMU, Meta
- **著者**: Beidi Chen（CMU/Meta）他
- **注目理由**: 🏫 CMU + 史上初のリアルタイム動画生成

## 概要
Diffusion Transformerによるリアルタイム動画生成のための効率的注意機構。Monarch行列を用いた構造化注意パラメータ化で、高い表現力と計算効率を両立。

## 主要貢献
1. **Monarch-RT**: 動画拡散モデル向け構造化注意パラメータ化
2. **95%注意スパース性**: 品質低下なしで達成
3. **カスタムTritonカーネル**: FlashAttention-2/3/4を上回る実装

## 実験結果
- **カーネル速度向上**: 1.4〜11.8倍（RTX 5090, H100, B200）
- **史上初**: RTX 5090単体でSelf-Forcingによる**16 FPSリアルタイム動画生成**を達成

## リンク
- 論文: https://arxiv.org/abs/2602.12271
