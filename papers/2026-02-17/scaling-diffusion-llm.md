# Scaling Beyond Masked Diffusion Language Models

## 基本情報
- **arXiv**: [2602.15014](https://arxiv.org/abs/2602.15014)
- **カテゴリ**: cs.LG, cs.CL
- **投稿日**: 2026-02-16
- **著者**: Subham Sekhar Sahoo, Jean-Marie Lemercier, Zhihan Yang, et al.
- **コード**: [GitHub](https://github.com/s-sahoo/scaling-dllms)
- **プロジェクト**: http://s-sahoo.github.io/scaling-dllms

## 概要
離散拡散言語モデルの**初のスケーリング則研究**。Masked diffusionが支配的な現状に疑問を呈し、uniform-stateおよびinterpolating手法の比較分析を実施。

## 技術的特徴
1. **スケーリング則**: uniform-stateとinterpolating discrete diffusionの初の体系的分析
2. **Masked diffusionの効率化**: 単純なcross-entropy目的で約12% FLOPs効率化
3. **パープレキシティの再考**: 同一ファミリー内では有用だがファミリー間比較では誤解を招く
4. **速度-品質パレートフロンティア**: 実用的なサンプリング速度を考慮した評価

## 主要結果
- 全手法を1.7Bパラメータまでスケール
- Uniform-state diffusionはvalidation perplexityで劣るが**GSM8Kで自己回帰・Masked diffusionを上回る**
- Masked diffusionが「唯一の未来」という見方に挑戦

## 注目ポイント
🎯 **拡散言語モデルの新しいスケーリング法則**を提示、モデル・チェックポイント・チュートリアル公開
