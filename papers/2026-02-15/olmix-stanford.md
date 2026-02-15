# Olmix: A Framework for Data Mixing Throughout LM Development

## メタ情報
- **arXiv ID**: 2602.12237
- **カテゴリ**: cs.LG, cs.AI, cs.CL
- **投稿日**: 2026-02-12
- **機関**: Stanford, AI2
- **著者**: Christopher Ré, Hannaneh Hajishirzi他
- **注目理由**: 🏫 Stanford/AI2

## 概要
言語モデル開発全体を通じたデータ混合フレームワーク。実世界のLM開発で直面する課題（設計空間の理解不足、ドメインセットの進化）に対応。

## 主要貢献
1. **設計空間の実証研究**: 強力な混合手法に繋がる設計選択を特定
2. **Mixture Reuse**: 更新されたドメインのみ再計算し、過去の混合情報を活用
3. **効率的な再計算**: 74%の計算削減で完全再計算と同等性能

## 実験結果
- 5回のドメインセット更新シーケンスで検証
- 混合なし学習と比較して下流タスクで**11.6%改善**

## リンク
- 論文: https://arxiv.org/abs/2602.12237
