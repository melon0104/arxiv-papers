# ConFu: Contemplate the Future for Better Speculative Sampling

## 基本情報
- **arXiv ID**: 2603.08899
- **タイトル**: ConFu: Contemplate the Future for Better Speculative Sampling
- **著者**: Zongyue Qin, Raghavv Goel, Mukul Gagrani, Risheek Garrepalli, Mingu Lee, Yizhou Sun
- **投稿日**: 2026-03-11
- **URL**: https://arxiv.org/abs/2603.08899

## 概要
スペキュラティブデコーディングはドラフトモデルで候補トークンを提案し、ターゲットモデルで検証することでLLM推論を高速化する。EAGLEシリーズなどの最先端手法は優れた高速化を達成するが、既存ドラフトモデルには**誤差蓄積**の制限がある：現在のプレフィックスのみを条件とし、ステップを経るごとにターゲットモデルからドリフトする。

## 提案手法: ConFu
**Contemplate the Future**を提案：
1. **Contemplate tokens & Soft prompts**: ドラフトモデルがターゲットモデルからの将来指向信号を活用（オーバーヘッド極小）
2. **動的contemplate tokenメカニズム with MoE**: 文脈認識の将来予測を実現
3. **アンカートークンサンプリング+将来予測複製の学習フレームワーク**: 堅牢な将来予測を学習

## 実験結果
Llama-3 3B/8Bモデルで、様々な下流タスクにおいて：
- EAGLE-3比でトークン受理率が**8-11%向上**
- 生成速度も同様に向上

## 注目ポイント
- ⚡ **推論高速化**: スペキュラティブデコーディングの新パラダイム
- 🔮 **将来予測**: 連続推論トークンとスペキュラティブデコーディングの初の橋渡し
- 📈 **EAGLE-3超え**: 最新手法を上回る性能

## カテゴリ
cs.CL

## 関連タグ
#スペキュラティブデコーディング #推論高速化 #LLM #将来予測 #効率化
