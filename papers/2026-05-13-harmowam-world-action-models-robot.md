# HarmoWAM: Harmonizing Generalizable and Precise Manipulation via Adaptive World Action Models

- **arXiv ID**: 2605.10942
- **カテゴリ**: cs.RO (ロボティクス)
- **投稿日**: 2026-05-11
- **URL**: https://arxiv.org/abs/2605.10942

## 著者
Qiuxuan Feng, Jiale Yu, Jiaming Liu, Yueru Jia et al.

## 選定理由
✅ **研究の重要性**: World Action Models (WAMs)という新パラダイムの根本的なトレードオフを解決
✅ **技術的新規性**: 「一般化」と「精度」の二律背反を適応的に調和させる設計

## 概要
World Action Models（物理ダイナミクスをモデル化してロボット制御を行うモデル）には2大パラダイムがある：(1) Imagine-then-Execute（動画予測で逆動力学からアクションを推定）と(2) Joint Modeling（アクションと動画表現を共同モデル化）。体系的実験でこの2者の根本的トレードオフ（一般化 vs 精度）を明らかにし、HarmoWAMがこれを適応的に調和。

## 主要な貢献
1. **トレードオフの体系化**: 2パラダイムの根本的差異を実験的に定量化
2. **適応的調和メカニズム**: タスクに応じて両パラダイムの利点を動的に統合
3. **HarmoWAM**: 一般化能力と精密制御を両立した新WAMアーキテクチャ

## 実験結果
- 単一パラダイムの手法を複数のマニピュレーションタスクで上回る
- 未知環境での一般化と精密操作の両立を実証

## インパクト
ロボットマニピュレーションのためのWorld Action Modelsの実用性を大幅向上。汎用ロボットの実現に向けた重要な一歩。
