# EditCtrl: Disentangled Local and Global Control for Real-Time Generative Video Editing

## 基本情報
- **arXiv**: [2602.15031](https://arxiv.org/abs/2602.15031)
- **カテゴリ**: cs.CV
- **投稿日**: 2026-02-16
- **著者**: Yehonathan Litman, Shikun Liu, et al.
- **プロジェクト**: https://yehonathanlitman.github.io/edit_ctrl

## 概要
効率的なビデオインペインティング制御フレームワーク。従来手法はマスクサイズに関係なく全ビデオコンテキストを処理するが、EditCtrlは**必要な箇所のみに計算を集中**。

## 技術的特徴
1. **Local Video Context Module**: マスクトークンのみで動作、編集サイズに比例した計算コスト
2. **Temporal Global Context Embedder**: 軽量ながらビデオ全体の一貫性を確保
3. **Multi-region Editing**: テキストプロンプトによる複数領域同時編集
4. **Autoregressive Content Propagation**: 内容の時間方向への伝播

## 主要結果
- **SOTA生成編集手法の10倍効率的**
- フルアテンション設計の手法より編集品質も向上
- 新機能のアンロック: マルチリージョン編集、自己回帰伝播

## 注目ポイント
🎯 **リアルタイム動画編集**を可能にする効率的フレームワーク、実用的なユースケースを開拓
