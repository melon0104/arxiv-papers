# When Vision Overrides Language: Evaluating and Mitigating Counterfactual Failures in VLAs

- **arXiv ID**: 2602.17659
- **カテゴリ**: cs.CV, cs.RO
- **投稿日**: 2026-02-19
- **URL**: https://arxiv.org/abs/2602.17659
- **Website**: https://vla-va.github.io/

## 著者
Yu Fang, Yuchun Feng, Dong Jing, Jiaqi Liu, Yue Yang, Zhenyu Wei, Daniel Szafir, Mingyu Ding

## 選定理由
✅ **重要な新規ベンチマーク**: LIBERO-CF（初のVLA counterfactualベンチマーク）
✅ **実世界評価**: 実ロボットでの検証

## 概要
Vision-Language-Action models (VLAs)が言語指示を無視し、視覚ショートカットに依存する「counterfactual failures」問題を体系的に研究。初のcounterfactualベンチマークLIBERO-CFを導入。

## 主要な貢献
1. **LIBERO-CF**: VLAs向け初のcounterfactualベンチマーク
2. **Counterfactual Action Guidance (CAG)**: Training-freeのdual-branch推論スキーム
3. **言語条件付けの明示的正則化**: 視覚ショートカットへの依存を軽減

## 実験結果
- **π_{0.5}の改善**: Language following accuracy +9.7%、Task success +3.6%（training-free）
- **VAモデル併用時**: +15.5%、+8.5%の追加改善
- **実世界**: Counterfactual failures 9.4%削減、Task success 17.2%向上

## 技術的詳細
- Language-unconditioned Vision-Action (VA)モジュールとの併用
- Plug-and-play: 既存アーキテクチャの変更不要

## 関連研究
- Vision-Language-Action models
- Robot learning
- Multimodal grounding
