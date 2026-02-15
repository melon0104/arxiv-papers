# LASER: An Efficient Target-Aware Segmented Attention Framework for End-to-End Long Sequence Modeling

## メタ情報
- **arXiv ID**: 2602.11562
- **カテゴリ**: cs.IR
- **投稿日**: 2026-02-12
- **機関**: Xiaohongshu (RedNote)
- **注目理由**: 🏭 実運用（1億DAU以上へデプロイ済み）

## 概要
Xiaohongshu（小紅書/RedNote）で開発・デプロイされた、超長いユーザー行動系列をモデル化するためのフルスタック最適化フレームワーク。推論の「レイテンシ壁」を2つのボトルネック（I/O遅延と注意機構の二次計算量）から突破。

## 主要貢献
1. **SeqVault**: DRAM-SSDハイブリッドインデックス戦略で検索遅延50%削減、CPU使用量75%削減
2. **Segmented Target Attention (STA)**: シグモイドゲーティングによるノイズフィルタリングで効率的な系列圧縮
3. **Global Stacked Target Attention (GSTA)**: セグメント間依存性を低コストで捕捉

## 実験結果
- オフライン評価でSOTAベースラインを一貫して上回る
- **オンラインA/Bテスト**: ADVV +2.36%、収益 +2.08%
- 1億DAU以上へデプロイ済み

## リンク
- 論文: https://arxiv.org/abs/2602.11562
