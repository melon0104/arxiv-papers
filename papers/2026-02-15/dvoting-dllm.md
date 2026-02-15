# dVoting: Fast Voting for dLLMs

## メタ情報
- **arXiv ID**: 2602.12153
- **カテゴリ**: cs.CL, cs.AI
- **投稿日**: 2026-02-12
- **機関**: National University of Singapore
- **著者**: Xinchao Wang他
- **注目理由**: 💻 コード公開

## 概要
Diffusion Large Language Models (dLLMs)向けの高速投票技術。学習なしで推論能力を向上させ、計算オーバーヘッドを最小限に抑える。

## 主要貢献
1. **一貫性分析**: サンプル間で一貫したトークン予測と、性能を決定する少数の変動トークンを発見
2. **反復的精緻化**: 投票による不確実トークンの再生成
3. **効率的なTTSスケーリング**: dLLMの任意位置生成能力を活用

## 実験結果
- **GSM8K**: +6.22%〜7.66%
- **MATH500**: +4.40%〜7.20%
- **ARC-C**: +3.16%〜14.84%
- **MMLU**: +4.83%〜5.74%

## リンク
- 論文: https://arxiv.org/abs/2602.12153
- コード: https://github.com/fscdc/dVoting
