---
layout: default
title: Home
---

# arXiv AI Papers

検索・推薦・マッチング系のAI論文サマリー

---

## 2026-02-11 注目論文：Meta推薦Scaling Law＆ICLR'26 VLA＆NVIDIA 3Dシーン生成

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🚀 Kunlun](papers/kunlun-meta-scaling-recsys-0211) | **Meta**: 推薦システムのスケーリング則、MFU 17%→37%、**deployed** |
| [🔍 QP-OneModel](papers/qp-onemodel-xiaohongshu-0211) | **Xiaohongshu**: 統一LLMでクエリ理解、リテンション+0.044%、**deployed** |
| [💎 Sparse Embeddings](papers/sparse-embeddings-www2026-0211) | **WWW 2026**: スパース埋め込みで**100倍圧縮**、精度損失2.5%、**GitHub公開** |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🌍 Agent World Model](papers/agent-world-model-snowflake-0211) | **Snowflake**: 合成環境1,000生成、OOD汎化実証、**GitHub公開** |
| [⚡ ATTNPO](papers/attnpo-baidu-reasoning-0211) | **Baidu**: アテンション信号で推論効率化、overthinking解消 |
| [🔗 DRIFT](papers/drift-dual-model-longcontext-0211) | 知識と推論を分離、長文脈で同サイズモデル最高性能、**GitHub公開** |
| [✏️ Steer2Edit](papers/steer2edit-weight-editing-0211) | 訓練なし重み編集、安全性+17.2%、真実性+9.8%向上 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [🎯 RLFR](papers/rlfr-features-as-rewards-0211) | 解釈可能性特徴を報酬に、幻覚**58%削減**しつつ性能維持 |
| [🐱 WildCat](papers/wildcat-near-linear-attention-0211) | **Microsoft**: 準線形アテンション、理論保証付きO(n^(1+o(1))) |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🏗️ SAGE](papers/sage-nvidia-3d-scene-gen-0211) | **NVIDIA**: エージェント型3Dシーン生成、SAGE-10kデータセット公開 |
| [🎬 VideoWorld 2](papers/videoworld2-realworld-video-0211) | 実世界動画から転移学習、成功率**最大70%向上**、**GitHub公開** |
| [📱 Code2World](papers/code2world-gui-worldmodel-0211) | **AMAP**: GUI World Model、AndroidWorldでGemini-2.5-Flash+9.5%、**GitHub公開** |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [🧠 Chain of Mindset](papers/chain-of-mindset-reasoning-0211) | 4認知モードを適応切替、Qwen3-VL-32Bで+4.96%、**GitHub公開** |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🎯 ST4VLA](papers/st4vla-iclr2026-spatial-vla-0211) | **ICLR 2026**: 空間誘導VLA、Google Robot 66.1→**84.6**、新SOTA |
| [🔮 VLA-JEPA](papers/vla-jepa-latent-worldmodel-0211) | JEPAスタイルVLA、汎化とロバスト性を両立 |

---

## 2026-02-10 注目論文：ByteDance 15B推薦＆4BがClaude超え＆ImageNet FID 1.52

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🚀 TokenMixer-Large](papers/tokenmixer-large-bytedance-0210) | **ByteDance**: 15Bパラメータ推薦モデル、複数シナリオで**deployed** |
| [🔄 MuCo](papers/muco-multiturn-contrastive-0210) | **NAVER AI**: マルチターン対比学習で埋め込み効率化、**GitHub公開** |
| [🍜 Meituan Multimodal](papers/meituan-multimodal-retrieval-0210) | **Meituan**: フードデリバリー検索、オンラインA/Bで**+1.12%収益** |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🎙️ PersonaPlex](papers/personaplex-nvidia-duplex-0210) | **NVIDIA**: フルデュプレックス音声でロール＆ボイス制御 |
| [🧪 CauGym](papers/caugym-causal-reasoning-0210) | 因果推論で**o3を38pt上回る**（93.5% vs 55.4%）、**GitHub公開** |
| [🏥 Baichuan-M3](papers/baichuan-m3-medical-llm-0210) | 医療LLMで**GPT-5.2超え**、**HuggingFace公開** |
| [⚡ SHINE](papers/shine-hypernetwork-lora-0210) | 1パスでLoRA生成、SFT不要でパラメータ更新、**GitHub公開** |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [📊 μA (LoRA LR Scaling)](papers/lora-lr-scaling-mua-0210) | LoRAランクと学習率のスケーリング則、**Full FT転移**可能 |
| [⚡ 2:4 Sparsity](papers/24-sparsity-meta-0210) | **Meta**: ハードウェア加速スパース性で**1.4-1.7倍**高速化 |
| [🔬 Condensate Theorem](papers/condensate-theorem-on-attention-0210) | TransformerはO(n)と証明、131Kトークンで**159倍高速** |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🚗 Driving with DINO](papers/driving-with-dino-sim2real-0210) | DINOv3でSim2Real、一貫性とリアリズムを両立 |
| [🎨 FlowConsist](papers/flowconsist-sota-imagenet-0210) | ImageNet 256×256で**FID 1.52**（1ステップSOTA） |
| [🤖 M3](papers/m3-multiagent-t2i-0210) | マルチエージェントT2Iで**Imagen4/Seedream超え** |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [🔍 AgentCPM-Explore](papers/agentcpm-explore-4b-gaia-0210) | **清華大学**: 4BモデルがGAIA 97%、**Claude-4.5-Sonnet超え** |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🚶 HiWET](papers/hiwet-humanoid-locomanip-0210) | 世界座標系でヒューマノイド操作、**Sim2Real転移**実証 |
| [🌍 DreamDojo](papers/dreamdojo-world-model-44k-0210) | **NVIDIA/Berkeley**: 44K時間動画から汎用ロボットWorld Model |

---

## 2026-02-09 注目論文：ICLR'26採択＆ICRA'26採択＆RAG新手法多数

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [📐 Scaling Laws Embedding](papers/scaling-laws-embedding-ir) | 埋め込み次元のスケーリング則発見、**べき乗則**に従う |
| [🧠 ERM](papers/erm-evolving-retrieval-memory) | RAGの一時的適応を持続的改善に変換、**推論オーバーヘッドなし** |
| [🔬 Atomic Info Flow](papers/atomic-info-flow-rag) | RAGのツール帰属をネットワークフローでモデル化、**+28pt精度** |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🎯 BudgetMem](papers/budgetmem-agent-memory-0209) | エージェントメモリの予算ティアルーティング、**RLポリシー** |
| [📊 REAL](papers/real-rewards-as-labels) | RLVRを分類問題化、DAPO比**6.7%向上** |
| [🔗 Structured Context](papers/structured-context-engineering) | 9,649実験でLLMエージェントの文脈構造を分析 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [⚡ CSRv2](papers/csrv2-ultrasparse-iclr2026) | **ICLR'26**: 超スパース埋め込み(k=2)、**300倍効率** |
| [🌊 DFPO](papers/dfpo-distributional-flow-rl) | 分布型Value FlowでPPO超え、ノイズ耐性 |
| [🔧 HGF](papers/hgf-158bit-llm) | 1.58bit LLMの品質を**55%回復**、12-15%オーバーヘッド |
| [⚖️ SVC](papers/svc-model-merging) | モデルマージの過剰蓄積問題解決、**+13%改善** |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [⚡ FlashBlock](papers/flashblock-attention-caching) | ブロック拡散のアテンションキャッシュ、**1.44倍高速** |
| [🧭 MerNav](papers/mernav-zero-shot-navigation) | Memory-Execute-Reviewで**ZS/TF両立**、SFT超え |
| [🤖 VISTA](papers/vista-vla-visual-conditioning) | VLAの視覚条件付け強化、データ追加不要 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [🕸️ HugRAG](papers/hugrag-hierarchical-causal-kg) | 階層的因果KGでグラフRAG改善、スプリアス抑制 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🤝 CommCP](papers/commcp-multiagent-icra2026) | **ICRA'26**: LLM通信＋Conformal Predictionでマルチエージェント協調 |
| [🎯 DIG](papers/dig-zero-shot-grasping) | 微分可能逆グラフィクスでゼロショット把持 |

---

## 2026-02-07 注目論文：ICLR'26複数採択＆Google推薦＆Meta触覚World Model

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🏷️ AgenticTagger](papers/agentictagger-google-llm-rec) | **Google/UCSD**: LLMエージェントによる構造化アイテム表現生成 |
| [⚡ CSRv2](papers/csrv2-ultrasparse-iclr2026) | **ICLR'26**: 超スパース埋め込み(k=2)でMRL同等性能、**300倍効率** |
| [🔬 SAGE](papers/sage-deep-research-retrieval) | Deep Researchエージェント向けベンチマーク、**BM25がLLMリトリーバーを30%上回る** |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [⚡ DFlash](papers/dflash-block-diffusion-decoding) | ブロック拡散で投機的デコーディング、**EAGLE-3比2.5倍高速** |
| [🧠 BudgetMem](papers/budgetmem-agent-memory) | クエリ認識型エージェントメモリ、**RLルーターで予算-性能最適化** |
| [🔧 Dr.Kernel](papers/dr-kernel-rl-triton) | **HKUST**: RLでTritonカーネル生成、**Claude-4.5-Sonnet超え** |
| [🌍 EuroLLM-22B](papers/eurollm-22b-multilingual) | 35言語対応LLM、モデル・データ・コード全て公開 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [🔄 Share LoRA](papers/share-lora-continual-learning) | **JHU (Yuille/Chellappa)**: 継続学習で**100倍パラメータ削減**、281倍メモリ節約 |
| [🎯 AP-OOD](papers/ap-ood-iclr2026) | **ICLR'26 (Hochreiter)**: テキストOOD検出、FPR95を27%→4.7%に |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🦢 SwimBird](papers/swimbird-hybrid-mllm) | ハイブリッドMLLMで3推論モード切替（テキスト/視覚/混合） |
| [🎬 Context Forcing](papers/context-forcing-long-video) | **Ming-Hsuan Yang**: 長動画生成で**20秒以上のコンテキスト**、SOTA超え |
| [🧊 Splat and Distill](papers/splat-distill-iclr2026) | **ICLR'26**: 3D Gaussianで2D VFMに3D認識を注入 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [🕸️ DyTopo](papers/dytopo-multiagent-routing) | 動的トポロジーでマルチエージェント推論、**+6.2pt改善** |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🖐️ VT-WM](papers/vt-worldmodels-meta) | **Meta AI**: 触覚World Model、ゼロショット実機で**+35%成功率** |
| [🤖 XHugWBC](papers/xhugwbc-crossembodiment) | 1回訓練で**12種のヒューマノイド**に汎化、7台の実機で検証 |

---

## 2026-02-06 注目論文：WWW'26 2本採択＆ICLR'26＆SWE-bench 71%

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🎬 VK-LSVD](papers/vk-lsvd-www2026) | **WWW'26**: ショート動画推薦、**400億インタラクション**の最大級データセット |
| [🏪 DOS](papers/dos-meituan-www2026) | **WWW'26/Meituan**: Dual-Flow Semantic ID、**数億ユーザーにデプロイ済** |
| [🛡️ SDAG](papers/sdag-rag-defense) | RAGのcorpus poisoning攻撃防御、Sparse Attention |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🤐 Abstention](papers/abstention-temporal-qa-iclr2026) | **ICLR'26**: LLMに「答えない」を教える、Qwen1.5BがGPT-4o超え |
| [👁️ RAL](papers/ral-attention-mllm) | MLLM向けRL、**アテンション分布を直接最適化** |
| [🧬 STM](papers/stm-biomedical-retrieval) | 生物医学リトリーバー、合成データ＋モデルマージで+23.5% |
| [📝 SE-Bench](papers/se-bench-thunlp) | **THUNLP**: 自己進化ベンチマーク、Open-Book Paradox発見 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [🎯 DPPO](papers/dppo-llm-rl) | PPOのratio clippingがLLMに不適合→Divergence制約で改善 |
| [🧪 PAR](papers/par-bytedance-protein) | **ByteDance**: マルチスケール自己回帰タンパク質生成 |
| [⚡ MH-LatentMoE](papers/mhlmoe-head-parallel) | Head Parallelで**1.61倍高速**、O(1)通信コスト |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [📍 CoWTracker](papers/cowtracker-dense-tracking) | Cost volume不要の密点追跡、**TAP-Vid SOTA** |
| [🎮 PerpetualWonder](papers/perpetualwonder-4d-scene) | 長期4Dシーン生成、初の真のクローズドループ |
| [🎭 Mask-LLaVA](papers/mask-llava-efficient-vlm) | マルチレベル特徴でVLM効率化、推論時トークン動的調整 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [👥 GEA](papers/gea-group-evolving-agents) | Group進化エージェント、**SWE-bench 71%**達成 |
| [🌊 Fluid Reasoning](papers/fluid-reasoning-qwq) | QwQ-32Bのメカニズム解析、推論中の表現変化を発見 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🤸 PDF-HR](papers/pdf-hr-humanoid-pose) | Pose Distance Fieldsでヒューマノイド姿勢事前知識 |
| [👓 Vision Exo](papers/vision-gated-exoskeleton) | 視覚ゲート外骨格制御、15名ユーザースタディで有効性実証 |

---

## 2026-02-05 注目論文：Google Gemini科学研究＆マルチエージェントスケーリング

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🎯 GRAB-CTR](papers/grab-ctr-baidu) | **Baidu**: LLM着想の生成的CTR予測、CamAアテンション |
| [🔄 RecID Tokenizer](papers/rethinking-gen-rec-tokenizer) | Semantic IDを推薦ネイティブに再設計 |
| [🧠 Reasoning GR](papers/reasoning-gen-rec) | 生成型推薦のバイアス増幅問題を解消 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🔬 Gemini Scientific](papers/gemini-scientific-research) | **Google**: Gemini Deep Thinkで科学研究加速事例集 |
| [🚀 A-RAG](papers/a-rag-hierarchical) | エージェント型RAG、階層的検索インターフェース |
| [⚡ V0 Value Model](papers/v0-generalist-value-model) | 汎用Value Modelで任意ポリシーに適用 |
| [🌐 FactNet](papers/factnet-billion-kg) | 17億アサーションの多言語KG、ハルシネーション対策 |
| [🛡️ Privasis](papers/privasis-synthetic-privacy) | 100万件合成プライバシーデータセット |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [🔒 Antidistillation](papers/antidistillation-fingerprint) | LLM蒸留検出フィンガープリント |
| [📱 MeKi](papers/meki-edge-llm) | エッジLLMのストレージベーススケーリング |
| [🎨 R1-SyntheticVL](papers/r1-synthetic-mllm) | 敵対的合成データでMLLM強化（CADS） |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🎬 LIVE](papers/live-video-world-model) | 長期インタラクティブビデオWorld Model |
| [⚡ Fast-Slow VTP](papers/fast-slow-mllm-training) | Visual Token Pruningで訓練効率化 |
| [🤖 RDT2](papers/rdt2-zero-shot-vla) | 1万時間データで**ゼロショットVLA**、7B |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [📊 Agent Scaling](papers/agent-scaling-mas) | MASスケーリング限界と**多様性の重要性** |
| [🔧 AOrchestra](papers/aorchestra-subagent) | サブエージェント自動生成オーケストレーション |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🛹 HUSKY](papers/husky-humanoid-skateboard) | ヒューマノイドスケートボード、全身制御 |
| [🌉 BridgeV2W](papers/bridgev2w-world-model) | ビデオ生成→エンボディドWorld Model変換 |

---

## 2026-02-04 注目論文：WWW/SIGIR採択＆SWE-bench 93.7%

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🏆 PARSE](papers/parse-sigir2026) | **SIGIR'26**: パーソナライズド適応検索、リアルタイム意図推定 |
| [🌐 Inferential QA](papers/inferential-qa-www2026) | **WWW'26**: 知識グラフ上のマルチホップ推論QA |
| [🔬 GRAB](papers/grab-baidu-graph-rag) | **Baidu**: バイオメディカル向けGraph RAG |
| [🍎 Query AutoComplete](papers/query-autocompletion-apple) | **Apple/Berkeley**: LLMによるクエリ自動補完 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🚀 Kimi K2.5](papers/kimi-k25-moonshot) | **Moonshot AI**: RLスケーリングの新テクニカルレポート |
| [💻 RPG-Encoder](papers/rpg-encoder-swebench) | **SWE-bench 93.7%** 達成の検索拡張コード生成 |
| [🔧 RE-TRAC](papers/re-trac-microsoft) | **Microsoft**: 検索拡張によるコード生成訓練 |
| [🛒 D-CORE](papers/d-core-alibaba) | **Alibaba**: Dense対照学習で検索精度向上 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🏆 World-Gymnast](papers/world-gymnast-rl) | World Modelでアジャイル学習、**SFT比18倍** |
| [🤖 BTGenBot-2](papers/btgenbot2-gpt5) | Behavior Tree生成で**GPT-5超え** |
| [🌊 Flow Policy](papers/flow-policy-gradients) | Flow-based連続制御で滑らか動作生成 |
| [👤 HumanX](papers/humanx-generalization) | ヒューマノイド汎化性能**8倍向上** |

---

## 2026-02-03 注目論文：ECIR/EACL/ICASSP採択＆プロダクション事例

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🔮 OrLog](papers/orlog-neuro-symbolic) | **ECIR'26**: ニューロシンボリック検索、OR/ANDクエリでtop精度向上 |
| [🎯 BEAR](papers/bear-beam-search) | Beam Search認識型LLM推薦、訓練-推論ギャップを解消 |
| [🏷️ TRM](papers/trm-semantic-tokens) | Semantic TokensでItem ID脱却、**大規模検索にデプロイ済み** |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [⚡ FOCUS](papers/focus-dllm-inference) | Diffusion LLMのスループット3.5倍、GitHub公開 |
| [🎨 ReGuLaR](papers/regular-latent-reasoning) | CoTを画像化して潜在推論、マルチモーダルでCoT超え |
| [🔊 Audio Jailbreak](papers/audio-narrative-attack) | **EACL'26**: 音声ナラティブでGemini 2.0を98%突破 |
| [🧠 DS-MCM](papers/ds-mcm-deep-search) | 認知神経科学着想のメタ認知でDeep Search改善 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [📐 TEON](papers/teon-llm-optimizer) | Muon超えのテンソル直交化、LLM事前学習を改善 |
| [🌊 Particle-Guided Diffusion](papers/particle-guided-diffusion) | 物理ガイダンス＋SMCでPDEソルバーがSOTA |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🎬 VideoGPA](papers/videogpa-3d-consistency) | 幾何学ファウンデーション＋DPOでVDM 3D整合性向上 |
| [📊 TaTa](papers/tata-vision-language) | **ICASSP'26**: ブラウン距離共分散で訓練不要VLM適応 |
| [🎥 Video-o3](papers/video-o3-long-video) | ネイティブツール呼び出しで長時間ビデオ多段階推論 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [🛡️ ThinkSafe](papers/thinksafe-reasoning-safety) | 自己生成で推論モデルの安全性復元、GitHub公開 |
| [👥 MAPPA](papers/mappa-multiagent) | アクション単位報酬でマルチエージェントをスケール |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🌀 LG-Flow](papers/lg-flow-robotic) | 潜在Flow Matchingで高速＋滑らかなロボット操作 |
| [🚀 MOSAIC](papers/mosaic-multi-robot) | POIベース抽象化で5台異種ロボット探査、86%自律率 |

---

## 2026-02-02 注目論文：WWW/ICLR/ICASSP採択＆有名機関

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🛒 LRKD-ECom](papers/lrkd-ecom) | **WWW'26**: MPCoT＋LRKDで EC検索を低レイテンシ蒸留、数千万DAU運用 |
| [🕸️ A2RAG](papers/a2rag-graph) | 適応型GraphRAGでRecall+10pt、コスト50%削減 |
| [🦎 LEMUR](papers/lemur-multivec) | マルチベクトル検索を1桁高速化 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🤝 Human-LLM FE](papers/human-llm-fe) | **ICLR'26**: 人間-LLM協調の特徴量エンジニアリング |
| [🔄 Self-Improving Pretrain](papers/self-improving-pretrain) | 事前学習時RLで安全性+36%、事実性+18%（Jason Weston） |
| [📈 Scaling Embeddings](papers/scaling-embeddings) | 埋め込みスケーリングがMoEを上回る条件を分析 |
| [📊 MADI](papers/madi-timeseries) | 時系列×LLMのマルチモーダル理解 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [🎬 Thinking in Frames](papers/thinking-frames) | ビデオ生成でVisual Test-Time Scaling（Cambridge/Belongie） |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [⚖️ OTIS](papers/otis-ood) | **ICLR'26**: 最適輸送でOOD過信を解消 |
| [🎥 Spava](papers/spava-video) | 長時間ビデオ推論を12.7倍高速化（THUNLP、GitHub公開） |
| [📝 UEval](papers/ueval-unified) | 統一マルチモーダル生成ベンチマーク、GPT-5-Thinking: 66.4点 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [⚡ MAR](papers/mar-efficient-llm) | **ICASSP'26**: SSM+SNN融合で効率的LLM |
| [🔍 RLVR分析](papers/reasoning-embedding) | 推論モデルは埋め込みを改善しない（Manifold Realignment） |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🏥 MoE-ACT](papers/moe-act-surgical) | 手術ロボットMoE模倣学習、in vivo豚実験成功 |
| [🔊 Sound-Triggered](papers/sound-triggered-robot) | 音響イベント駆動型モバイル操作、Habitat-Echo |

---

## 2026-02-02 RAG・推薦の最前線

| 論文 | 一言 |
|------|------|
| [🛒 LRKD](papers/lrkd) | WWW'26: EC検索にLLM推論を低レイテンシ蒸留 |
| [⚖️ CDFA](papers/cdfa) | WWW'26: CDR推薦の公平性問題を理論分析＆解決 |
| [🎯 ProRAG](papers/prorag) | ステップレベルRLでRAGのプロセス幻覚を解消 |
| [🕸️ A2RAG](papers/a2rag) | 適応型GraphRAGでRecall+10pt、コスト半減 |
| [🤖 JADE](papers/jade) | Agentic RAGの計画・実行を共同最適化 |
| [🔍 ACQO](papers/acqo) | 複雑クエリのRL最適化で3ベンチマークSOTA |

---

## 2026-01-30 検索・マッチング特集

| 論文 | 一言 |
|------|------|
| [🔍 LEMUR](papers/lemur) | マルチベクトル検索を1桁高速化 |
| [📊 LANCER](papers/lancer) | 情報カバレッジ重視のLLMリランカー |
| [🎭 Rank-Nexus](papers/rank-nexus) | 2Bで画像+テキストリランキング |
| [🎯 SpecTran](papers/spectran) | LLM埋め込みを推薦モデルに注入 |
| [🛒 OneMall](papers/onemall) | Kuaishouの生成的推薦、4億DAU運用 |
| [🧠 ToT Track](papers/tot-trec) | 「思い出せない」検索のTREC評価 |

---

## 2026-02-01 AI全般（速報）

- **🔐 RedSage** - サイバーセキュリティ特化LLM。11.8B tokensで訓練
- **🖼️ pixel MeanFlow** - 1ステップ画像生成、pixel直接生成
- **💎 Hidden Gems** - HuggingFaceの隠れた名作モデル発掘
- **🧠 Hybrid Linear Attention** - Transformer→RNN蒸留で長文脈効率化
- **🤖 Agent-RRM** - エージェントRL用報酬モデル
- **🦾 DynamicVLA** - 0.4Bで動的物体のロボット操作

---

## About

検索・推薦・マッチング領域のarXiv論文を日本語でサマリー。
