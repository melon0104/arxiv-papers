# Singular Value Calibration: When Shared Knowledge Hurts in Model Merging

- **arXiv**: [2602.05536](https://arxiv.org/abs/2602.05536)
- **カテゴリ**: cs.LG, cs.AI, cs.CL, cs.CV
- **投稿日**: 2026-02-05
- **GitHub**: https://github.com/lyymuwu/SVC

## 概要

モデルマージにおいて、共有知識の過剰蓄積（Spectral Over-Accumulation）問題を特定し、これに対処するポストプロセッシング手法「Singular Value Calibration (SVC)」を提案。

## 問題提起

- 既存のマージ手法はタスク更新間の競合解決に焦点
- **見落とされた失敗モード**: 共有知識の過剰カウント
- タスクが整列したスペクトル方向を共有する場合、線形結合で特異値が膨張

## 主要な貢献

- **SVC**: トレーニング不要・データ不要のポストプロセッシング
- サブスペースオーバーラップを定量化し、膨張した特異値をリスケール
- バランスの取れたスペクトルを復元

## 実験結果

- ビジョン・言語ベンチマークで強力なマージベースラインを一貫して改善
- SOTA性能を達成
- 特異値のみの修正でTask Arithmeticの性能を**13.0%向上**

## コード公開

GitHubでコード公開済み

## リンク

- [PDF](https://arxiv.org/pdf/2602.05536)
- [GitHub](https://github.com/lyymuwu/SVC)
