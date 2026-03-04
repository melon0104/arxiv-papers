---
layout: paper
title: "Beyond Language Modeling: An Exploration of Multimodal Pretraining"
date: 2026-03-04
categories: [cs.CV]
venue: "Meta AI / NYU"
arxiv_id: "2603.03276"
website: "https://beyond-llms.github.io/"
---

# Beyond Language Modeling: An Exploration of Multimodal Pretraining

## 基本情報
- **arXiv**: https://arxiv.org/abs/2603.03276
- **著者**: Shengbang Tong, David Fan, John Nguyen, Ellis Brown, ..., Rob Fergus, Mike Lewis, Jakob Verbeek, Luke Zettlemoyer, Koustuv Sinha, **Yann LeCun**, Saining Xie
- **機関**: Meta AI / NYU
- **Project**: https://beyond-llms.github.io/

## 概要
ネイティブマルチモーダルモデルの設計空間を制御された事前学習実験で明確化。Transfusionフレームワーク（言語にはnext-token prediction、ビジョンにはdiffusion）を採用し、テキスト、ビデオ、画像テキストペア、アクション条件付きビデオを含む多様なデータで訓練。

## 主要知見
1. **RAE (Representation Autoencoder)**: 視覚理解と生成の両方に優れた統一的視覚表現
2. **Visual-language synergy**: 視覚と言語データは相補的で下流能力に相乗効果
3. **World modeling emergence**: 統一的マルチモーダル事前学習から世界モデリング能力が創発
4. **MoE for scaling asymmetry**: 言語の高モデル容量要求と視覚のデータ集約的性質を調和

## IsoFLOP分析
- 両モダリティのスケーリング則を計算
- **Scaling asymmetry発見**: ビジョンは言語よりはるかにデータハングリー
- MoEアーキテクチャがこの非対称性を調和

## なぜ注目？
- **Yann LeCun**（Meta Chief AI Scientist）の共著
- マルチモーダル基盤モデル設計の包括的実証研究
- 次世代マルチモーダルモデル設計の指針
