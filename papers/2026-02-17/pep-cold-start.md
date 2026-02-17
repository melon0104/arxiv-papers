# Cold-Start Personalization via Training-Free Priors from Structured World Models

## 基本情報
- **arXiv**: [2602.15012](https://arxiv.org/abs/2602.15012)
- **カテゴリ**: cs.CL, cs.AI, cs.LG
- **投稿日**: 2026-02-16
- **著者**: Avinandan Bose, Shuyue Stella Li, Faeze Brahman, Pang Wei Koh, Simon Shaolei Du, Yulia Tsvetkov, Maryam Fazel, Lin Xiao, Asli Celikyilmaz
- **所属**: UW, Microsoft Research

## 概要
Cold-startパーソナライゼーションのための新しいフレームワーク。ユーザー履歴がない状況で、構造化されたワールドモデルからの事前知識を用いてベイズ推論を行う。

## 技術的特徴
1. **オフライン構造学習 + オンラインベイズ推論**: 2段階分離
2. **Pep (Preference Elicitation with Priors)**: 嗜好相関のワールドモデルをオフライン学習
3. **Training-free推論**: 有益な質問選択と完全嗜好プロファイル予測
4. **超軽量**: 約10Kパラメータ（RLベースは8B）

## 主要結果
- 医療、数学、社会、常識推論の4領域で評価
- **80.8%の嗜好アライメント**達成（RLは68.5%）
- **3-5倍少ない対話数**で同等以上の性能
- ユーザー回答に応じたフォローアップ変更: Pep 39-62% vs RL 0-28%

## 注目ポイント
🎯 **Microsoft Research**との共同研究、cold-startのボトルネックが嗜好データの因子構造活用にあることを証明
