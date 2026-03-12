# Too Vivid to Be Real? Benchmarking and Calibrating Generative Color Fidelity

- **arXiv**: [2603.10990](https://arxiv.org/abs/2603.10990)
- **採択**: **CVPR 2026**
- **GitHub**: https://github.com/ZhengyaoFang/CFM
- **分野**: cs.CV（コンピュータビジョン）
- **著者**: Zhengyao Fang et al.

## 概要

Text-to-Image (T2I)生成は視覚品質が向上したが、実写のような視覚的真正性を持つ画像の生成は依然として困難。人間評価や嗜好訓練済みメトリクスは**過度に鮮やかな**画像（誇張された彩度とコントラスト）を好む傾向があり、リアルスタイル画像でも「リアルすぎて偽物」になる問題がある。

## 提案

1. **Color Fidelity Dataset (CFD)**: **130万枚以上**の実画像と合成画像、色リアリズムの順序付きレベル
2. **Color Fidelity Metric (CFM)**: マルチモーダルエンコーダで知覚的色忠実度を学習
3. **Color Fidelity Refinement (CFR)**: 訓練不要、生成時に空間-時間ガイダンススケールを適応的に調整し色真正性を向上

## フレームワーク

CFD → CFM（評価）→ CFMの学習済みアテンション → CFR（改善）という段階的フレームワークで、リアルスタイルT2I生成の色忠実度を評価・改善。

## 注目ポイント

CVPR 2026採択。T2I生成における「過度な鮮やかさ」問題に取り組む初の体系的研究。データセットとコード公開。
