# MerNav: Memory-Execute-Review Framework for Zero-Shot Object Goal Navigation

- **arXiv**: [2602.05467](https://arxiv.org/abs/2602.05467)
- **カテゴリ**: cs.CV, cs.CL, cs.RO
- **投稿日**: 2026-02-05

## 概要

Visual Language Navigation (VLN)において、成功率と汎化性を両立するMemory-Execute-Reviewフレームワーク「MerNav」を提案。

## 問題背景

- SFTアプローチ: 高い成功率だが汎化性に課題
- Training-Free (TF)アプローチ: 良い汎化性だが成功率に課題
- 両方を同時に達成するのは困難

## 主要な貢献

3つのモジュールで構成:
1. **Memory**: 階層的メモリモジュールで情報サポート
2. **Execute**: ルーチン意思決定と行動
3. **Review**: 異常状況の処理と行動修正

## 実験結果

4データセットでの評価:
- TF/ZS設定で全ベースラインに対し平均SR **7%/5%**の絶対改善
- HM3D_v0.1とHM3D_OVON（ZS設定）: SR **8%/6%**改善
- MP3DとHM3D_OVONではTF手法だけでなく**全SFT手法も上回る**
- SR（5%/2%）と汎化性の両方でリーダーシップ

## リンク

- [PDF](https://arxiv.org/pdf/2602.05467)
