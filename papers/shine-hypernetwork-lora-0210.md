# SHINE: A Scalable In-Context Hypernetwork for Mapping Context to LoRA

**arXiv**: [2602.06358](https://arxiv.org/abs/2602.06358)  
**日付**: 2026-02-09  
**分野**: cs.CL（自然言語処理）  
**機関**: 複数大学

## 概要

多様なコンテキストから高品質なLoRAアダプタを単一フォワードパスで生成するスケーラブルなハイパーネットワーク。Fine-tuningなしでLLMパラメータを更新し、コンテキスト内知識をパラメータ内知識に即座に変換。

## 技術的ポイント

- **In-Context Hypernetwork**: LLM自身のパラメータを再利用
- **Pretraining + Instruction Fine-tuning**: 高品質LoRA生成のための2段階パイプライン
- **Single Forward Pass**: Fine-tuningなしでパラメータ更新
- **Knowledge Transfer**: in-context → in-parameter変換

## 結果

- 複数タスクで優れた結果
- SFTベースのLLM適応と比較して時間・計算・メモリコストを大幅削減
- スケーリングの可能性を実証

## コード

GitHub: https://github.com/Yewei-Liu/SHINE

## 選定理由

- **コード公開**: GitHub
- LoRA生成の新パラダイムを提示
