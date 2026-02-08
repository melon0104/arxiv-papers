# VISTA: Enhancing Visual Conditioning in Vision-Language-Action Models

- **arXiv**: [2602.05049](https://arxiv.org/abs/2602.05049)
- **カテゴリ**: cs.CV, cs.AI, cs.LG, cs.RO
- **投稿日**: 2026-02-04
- **プロジェクト**: https://vista-vla.github.io/

## 概要

Vision-Language-Action (VLA)モデルにおける視覚-行動ミスアライメント問題に対処。視覚条件付けを明示的に強化するトレーニングフレームワーク「VISTA」を提案。

## 問題提起

- VLMをアクション空間に拡張すると視覚-行動ミスアライメントが発生
- 行動予測が現在の視覚状態への依存が弱くなり、信頼性の低い出力に

## 発見

成功したロールアウトは失敗したものより一貫して強い視覚依存性を示す

## 主要な貢献

2段階アプローチ:
1. **トラック追従サロゲートタスク**: 選好最適化で行動予測を視覚入力に整合
2. **潜在空間蒸留**: 強化された整合をinstruction-followingタスクに転送

## 特徴

- アーキテクチャ変更なし
- 追加データ収集なし
- 離散OpenVLAと連続OpenVLA-OFT設定の両方で一貫した改善

## リンク

- [PDF](https://arxiv.org/pdf/2602.05049)
- [プロジェクト](https://vista-vla.github.io/)
