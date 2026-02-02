# Audio Narrative Attacks Against Large Audio-Language Models

**arXiv**: [2601.23255](https://arxiv.org/abs/2601.23255)  
**カテゴリ**: cs.CL, cs.AI, cs.CR  
**採択**: EACL 2026 Main Conference  

## 概要

音声入力を受け付けるLLMに対する新しいjailbreak攻撃手法。ナラティブ形式の音声ストリームに禁止指示を埋め込む。

## 背景

Large Audio-Language Models (LALMs)の普及:
- 音声アシスタント
- 教育
- 臨床トリアージ

生の音声入力への移行により、未解明の脆弱性クラスが出現。

## 攻撃手法

**Text-to-Audio Jailbreak**:
1. 高度な指示追従型TTS（Text-to-Speech）モデルを活用
2. ナラティブ形式の音声ストリームに禁止指示を埋め込み
3. 構造的・音響的特性を利用してテキスト向け安全機構を回避

## 実験結果

- **対象**: Gemini 2.0 Flash等の最先端モデル
- **成功率**: 98.26%（テキストのみのベースラインを大幅に超過）

## 提言

言語的・パラ言語的表現を統合的に推論できる安全フレームワークの必要性。

## 一言

**ナラティブ音声でLLMの安全機構を98%回避、音声ベースインターフェースの脆弱性を警告**
