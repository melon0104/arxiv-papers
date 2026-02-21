# Sink-Aware Pruning for Diffusion Language Models

- **arXiv ID**: 2602.17664
- **カテゴリ**: cs.CL (自然言語処理)
- **投稿日**: 2026-02-19
- **URL**: https://arxiv.org/abs/2602.17664
- **GitHub**: https://github.com/VILA-Lab/Sink-Aware-Pruning

## 著者
Aidar Myrzakhan, Tianyi Li, Bowei Guo, Shengkun Tang, Zhiqiang Shen

## 選定理由
✅ **コード公開**: GitHubリポジトリ公開済み

## 概要
Diffusion Language Models (DLMs)の効率的なpruning手法を提案。Autoregressive LLMでは安定したglobal anchorとして機能するattention sinkが、DLMでは不安定であることを発見。

## 主要な貢献
1. **DLMにおけるSinkの挙動分析**: 生成軌跡全体でsink位置の分散が大きく、transientで構造的に本質的でないことを発見
2. **Sink-Aware Pruning**: 不安定なsinkを自動識別・pruneする手法を提案
3. **再学習不要**: 既存モデルにそのまま適用可能

## 実験結果
- 同等の計算量で既存のpruningベースラインを上回る品質・効率トレードオフ
- 再学習なしで適用可能

## 技術的詳細
- ARモデルではsinkを保持するのが一般的だが、DLMでは逆にpruning対象とすべき
- Timestep間でのdominant sink locationのシフトを計測

## 関連研究
- Token pruning
- Attention mechanism analysis
- Diffusion models for text generation
