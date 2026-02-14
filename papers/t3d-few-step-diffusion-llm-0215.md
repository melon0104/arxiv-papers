# T3D: Few-Step Diffusion Language Models via Trajectory Self-Distillation

[📄 arXiv:2602.12262](https://arxiv.org/abs/2602.12262) | [GitHub](https://github.com/Tyrion58/T3D)

## 概要
Diffusion LLMの少ステップ推論を改善。並列トークン生成の可能性を持つDLLMだが、ステップ数削減で品質が大幅に劣化する課題を解決。

## 提案手法
**T3D (Trajectory Self-Distillation with Direct Discriminative Optimization)**：
- 自己の生成軌跡を蒸留
- **DDO (Direct Discriminative Optimization)**：Reverse-KL目的関数でモード探索型蒸留を促進
- 学生モデルが高確率の教師モードに集中

## 実験結果
- 複数ベンチマークで強力な少ステップベースラインを上回る
- タイトなステップ予算下での標準訓練も上回る
- フルステップには及ばないが、そのギャップを大幅に縮小

## 注目ポイント
- 💻 **GitHub公開**
- 実用的な少ステップDLLMに向けた強固な基盤
- Diffusion LLMの推論効率化に貢献

## カテゴリ
cs.CL, cs.LG
