# VideoGPA: 3D-Consistent Video Generation via Geometric Preference Alignment

**arXiv**: [2601.23286](https://arxiv.org/abs/2601.23286)  
**カテゴリ**: cs.CV, cs.AI, cs.LG  

## 概要

幾何学ファウンデーションモデルを活用したDPOで、ビデオ拡散モデルの3D整合性を向上。

## 問題提起

ビデオ拡散モデル (VDM) の課題:
- 視覚的に印象的な結果を生成
- しかし**3D構造の整合性維持に根本的な困難**
- オブジェクト変形や空間的ドリフトが発生

**仮説**: 標準的なデノイジング目的に幾何的コヒーレンスへの明示的インセンティブがない

## VideoGPAの手法

**Video Geometric Preference Alignment**:
1. 幾何学ファウンデーションモデルから密な嗜好信号を自動導出
2. Direct Preference Optimization (DPO)でVDMをガイド
3. 人間アノテーション不要の自己教師あり学習

## 結果

最小限の嗜好ペアで:
- **時間的安定性**: 大幅に向上
- **物理的妥当性**: 改善
- **動きのコヒーレンス**: 強化
- 最先端ベースラインを広範な実験で上回る

## 一言

**幾何学ファウンデーションモデル＋DPOで、VDMの3D整合性を自動的に向上**
