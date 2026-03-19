---
layout: default
title: "PIER: Physics-informed offline reinforcement learning eliminates catastrophic fuel waste in maritime routing"
---

# PIER: Physics-informed offline reinforcement learning eliminates catastrophic fuel waste in maritime routing

[arXiv:2603.17319](https://arxiv.org/abs/2603.17319) | cs.AI

## 著者
Aniruddha Bora et al.

## 一言まとめ
物理情報を組み込んだオフラインRLによる**海上ルーティング最適化**。壊滅的燃料浪費を**9分の1に削減**、予測非依存で実運用向き。

## 概要
国際海運は世界の温室効果ガス排出の約3%を占めるが、航海ルーティングはヒューリスティック手法が支配的。PIERは物理キャリブレーション環境から燃料効率・安全性を考慮したルーティングポリシーを学習するオフラインRLフレームワーク。履歴船舶追跡データと海洋再解析製品を活用し、オンラインシミュレータ不要。

## 注目ポイント
- **壊滅的浪費9分の1**: 大圏航路の極端燃料消費(中央値1.5倍超)発生率4.8%→0.5%
- **平均CO2削減10%**: 大圏航路比較
- **予測非依存**: ローカル観測のみで動作、予測不確実性の影響なし
- **大規模検証**: 2023年全年AISデータ、メキシコ湾7ルート、840エピソード

## 技術的詳細
- 物理情報状態構成 + デモンストレーション拡張オフラインデータ
- 分離されたポストホック安全シールド
- 航海ごと燃料分散3.5倍低減(p<0.001)
- 実観測AIS船舶動作との部分検証で最速実航海と一致、分散23.1倍低

## 関連リンク
- [arXiv](https://arxiv.org/abs/2603.17319)
- [PDF](https://arxiv.org/pdf/2603.17319)
