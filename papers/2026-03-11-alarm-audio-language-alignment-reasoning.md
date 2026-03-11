# ALARM: Audio-Language Alignment for Reasoning Models

## 基本情報
- **arXiv ID**: 2603.09556
- **タイトル**: ALARM: Audio-Language Alignment for Reasoning Models
- **著者**: Petr Grinberg, Hassan Shahmohammadi
- **投稿日**: 2026-03-11
- **URL**: https://arxiv.org/abs/2603.09556

## 概要
大規模オーディオ言語モデル（ALM）はLLMを聴覚理解で拡張する。一般的アプローチはLLMを凍結しアダプタのみを自己生成ターゲットで学習する。しかし推論LLM（RLM）では、組み込みのChain-of-Thoughtトレースがテキスト代理入力を露出し、不自然な応答を生成。

## 提案手法: ALARM
**Self-rephrasing**を提案：
- 自己生成応答をオーディオ理解バリアントに変換
- RLMとの互換性を確保しつつ分布アラインメントを維持

### 技術的貢献
1. 複数オーディオエンコーダの融合・圧縮で強力な表現獲得
2. 19K時間（音声・音楽・音響）の6M件マルチタスクコーパス構築

## 実験結果
**4Bパラメータ**でオープンソース最高性能：
- **MMAU-speech**: オープンソース最高
- **MMSU**: オープンソース最高、全体3位
- テキスト能力を維持しつつ低学習コスト

## 注目ポイント
- 🎵 **マルチモーダル推論**: 音声・音楽・環境音に対応
- 🔄 **Self-rephrasing**: RLMとの互換性を確保する新技術
- ⚡ **効率的**: 4Bで大規模モデルを上回る

## カテゴリ
cs.CL

## 関連タグ
#オーディオ #マルチモーダル #推論 #LLM #音声理解
