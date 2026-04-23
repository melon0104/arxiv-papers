---
layout: default
title: Home
---

# arXiv AI Papers

検索・推薦・マッチング系のAI論文サマリー

---

## 2026-04-24 注目論文：4/22公開分（RAG評価・LLM推薦最適化・RLVR高速化・マルチモーダル拡散・ロボット操作VLA中心）

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [Coverage, Not Averages: Semantic Stratification for Trustworthy Retrieval Evaluation](papers/2604.20763-coverage-semantic-stratification-retrieval-eval.md) | RAGの検索評価にカバレッジ視点を導入：意味的層別サンプリングで平均値に隠れたニッチ失敗を検出 |
| [Break the Optimization Barrier of LLM-Enhanced Recommenders](papers/2604.20490-break-optimization-barrier-llm-enhanced-recommenders.md) | LLM強化推薦の「最適化バリア」を理論的に解明し実践フレームワークを提案 |
| [HaS: Accelerating RAG through Homology-Aware Speculative Retrieval](papers/2604.20452-has-homology-aware-speculative-retrieval.md) | クエリ間のホモロジー構造を活用したSpeculative Retrievalで RAG検索レイテンシを削減 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [Parallel-SFT: Improving Zero-Shot Cross-Programming-Language Transfer for Code RL](papers/2604.20835-parallel-sft-cross-programming-language-code-rl.md) | Amazon：RL学習中のSFT並列実行でコードLLMの多言語転移能力を維持・強化 |
| [Convergent Evolution: How Different Language Models Learn Similar Number Representations](papers/2604.20817-convergent-evolution-language-models-number-representations.md) | USC/UCSD：異なるLLMが数値表現で収束進化──T=2,5,10の周期特徴が普遍的に出現 |
| [Intersectional Fairness in Large Language Models](papers/2604.20677-intersectional-fairness-llm.md) | 単属性バイアス評価では見えない交差性バイアスをLLMで体系的に検証 |
| [Knowledge Capsules: Structured Nonparametric Memory Units for LLMs](papers/2604.20487-knowledge-capsules-nonparametric-memory-llm.md) | 構造化カプセル単位での知識管理でRAGのチャンク境界・更新コスト問題を解消 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [Near-Future Policy Optimization](papers/2604.20733-near-future-policy-optimization-rlvr.md) | RLVR収束加速：「近未来ポリシー」軌跡のオフポリシー活用でGRPO/PPOを上回る |
| [Stream-CQSA: Avoiding Out-of-Memory in Attention Computation](papers/2604.20819-stream-cqsa-long-context-attention-oom.md) | 長文コンテキストLLMのAttention OOMをチャンクストリーミングで解決 |
| [ParetoSlider: Diffusion Models Post-Training for Continuous Reward Control](papers/2604.20816-paretoslider-diffusion-post-training-reward-control.md) | 複数報酬をParetoフロント上でスライダー制御──Diffusionモデルのマルチ目的ポストトレーニング |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [LLaDA2.0-Uni: Unifying Multimodal Understanding and Generation with Diffusion LLM](papers/2604.20796-llada2-uni-multimodal-diffusion-llm.md) | Inclusion AI（アリババ）：Discrete Diffusion LLMで理解+生成を単一フレームワークに統合 |
| [DeVI: Physics-based Dexterous Human-Object Interaction via Synthetic Video Imitation](papers/2604.20841-devi-physics-dexterous-human-object-interaction.md) | 生成AI合成HOI動画を教師にPhysics-based模倣学習で巧みな物体操作を習得 |
| [OMIBench: Benchmarking Olympiad-Level Multi-Image Reasoning in LVLMs](papers/2604.20806-omibench-olympiad-multi-image-reasoning.md) | 複数画像横断推論のオリンピックレベルベンチマーク──現行LVLMの限界を明確化 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [SWE-chat: Coding Agent Interactions From Real Users in the Wild](papers/2604.20779-swe-chat-coding-agent-real-users.md) | 実ユーザー×AIコーディングエージェントの大規模利用データ分析──初の野生調査 |
| [Learning to Evolve: Self-Improving Multi-Agent Systems via Textual Parameter Graph Optimization](papers/2604.20714-learning-evolve-multi-agent-textual-optimization.md) | テキストパラメータグラフ最適化でマルチエージェントシステムが自己改善 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [PokeVLA: Pocket-Sized VLA with Comprehensive World Knowledge Guidance](papers/2604.20834-pokevla-pocket-sized-vla-world-knowledge.md) | 小型VLAモデルにワールドナレッジを蒸留──エッジデプロイ可能なロボット操作モデル |
| [FingerEye: Continuous and Unified Vision-Tactile Sensing for Dexterous Manipulation](papers/2604.20692-fingereye-vision-tactile-dexterous-manipulation.md) | 視触覚統合センシングで連続的な巧みな操作制御を実現 |

---

## 2026-04-23 注目論文：4/21公開分（CTR産業スケーリング・LLMエージェント効率化・RL理論・4D顔再構成・ヒューマノイド基盤モデル中心）

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [LoopCTR: Unlocking the Loop Scaling Power for Click-Through Rate Prediction](papers/2604.19550-loopctr-loop-scaling-ctr-prediction.md) | 産業制約下でのCTRモデルスケーリング：共有レイヤー再帰再利用で学習時計算↑・推論コスト固定 |
| [CAST: Modeling Semantic-Level Transitions for Complementary-Aware Sequential Recommendation](papers/2604.19414-cast-complementary-sequential-recommendation.md) | 逐次推薦における真の補完アイテム関係を意味遷移モデリングで抽出、人気バイアス回避 |
| [RARE: Redundancy-Aware Retrieval Evaluation Framework for High-Similarity Corpora](papers/2604.19047-rare-redundancy-aware-retrieval-evaluation.md) | 金融報告書・法律文書など高冗長コーパスでのRAG検索を公正評価するフレームワーク |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [EVPO: Explained Variance Policy Optimization for Adaptive Critic Utilization in LLM Post-Training](papers/2604.19485-evpo-explained-variance-policy-optimization-llm.md) | PPO vs GRPO問題に決着：説明分散でクリティック有効性を動的判定し両者を上回る |
| [DASH-KV: Accelerating Long-Context LLM Inference via Asymmetric KV Cache Hashing](papers/2604.19351-dash-kv-asymmetric-kv-cache-long-context.md) | 非対称ハッシングでKVキャッシュ重要エントリを高速特定、長文脈推論を高速化 |
| [A Self-Evolving Framework for Efficient Terminal Agents via Observational Context Compression](papers/2604.19572-self-evolving-terminal-agents-context-compression.md) | エージェント履歴の2乗コスト爆発を観測コンテキスト圧縮+自己進化で解消 |
| [Are Large Language Models Economically Viable for Industry Deployment?](papers/2604.19342-llm-economic-viability-industry-deployment.md) | LLM産業デプロイの経済性を定量分析：エネルギー・レイテンシ・コストの統合評価フレームワーク |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [FASTER: Value-Guided Sampling for Fast RL](papers/2604.19730-faster-value-guided-sampling-rl.md) | Stanford Sadigh/Finn：拡散ポリシーのテスト時スケーリングを価値関数ガイドで大幅効率化 |
| [Generalization at the Edge of Stability](papers/2604.19740-generalization-edge-of-stability.md) | 大学習率訓練（Edge of Stability）がなぜ汎化を改善するかをランダム動力系理論で解明 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [CityRAG: Stepping Into a City via Spatially-Grounded Video Generation](papers/2604.19741-cityrag-spatially-grounded-video-generation.md) | 地理参照画像RAGで実在都市の任意天候・構成をナビゲーブル3D動画として生成 |
| [Face Anything: 4D Face Reconstruction from Any Image Sequence](papers/2604.19702-face-anything-4d-reconstruction.md) | TUM Nießner研究室：任意画像シーケンスからの高品質4D顔再構成を統一フレームワークで実現 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [An AI Agent Execution Environment to Safeguard User Data](papers/2604.19657-ai-agent-execution-environment-safeguard.md) | プロンプトインジェクション対策：AIエージェントの隔離実行環境でプライベートデータを保護 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [UniT: Toward a Unified Physical Language for Human-to-Humanoid Policy Learning and World Modeling](papers/2604.19734-unit-unified-physical-language-humanoid.md) | 視覚アンカーで人間↔ヒューマノイドの統一潜在行動言語を構築、エゴセントリックデータを活用 |
| [VLA Foundry: A Unified Framework for Training Vision-Language-Action Models](papers/2604.19728-vla-foundry-unified-training-framework.md) | コード公開：LLM→VLM→VLAを単一コードベースで統合するオープンソース訓練フレームワーク |

---

## 2026-04-22 注目論文：4/21公開分（SIGIR/ACL/ICRA/ICLR 2026採択・産業推薦・LLM効率化・ロボティクス中心）

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [BACO: Balanced Co-Clustering of Users and Items for Embedding Table Compression in Recommender Systems](papers/2604.18351-baco-balanced-coclustering-embedding-compression.md) | SIGIR 2026：ユーザー/アイテム協調クラスタリングで埋め込みテーブルを75%圧縮、recall低下最大1.85%・最強ベースライン比346倍高速 |
| [DocQAC: Adaptive Trie-Guided Decoding for In-Document Query Auto-Completion](papers/2604.18257-docqac-adaptive-trie-query-autocompletion.md) | GitHub公開：ドキュメント内検索専用QACのTrie誘導デコーディング、T5/BARTがLLaMA-3・Phi-3を凌駕 |
| [MLTFR: Multi-LLM Token Filtering and Routing for Sequential Recommendation](papers/2604.18200-mltfr-multi-llm-token-filtering-routing-seqrec.md) | GitHub公開：テキスト入力なし・複数LLMのMoE統合でLLMトークン埋め込みを逐次推薦に安定活用 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [GSQ: Highly-Accurate Low-Precision Scalar Quantization for LLMs via Gumbel-Softmax](papers/2604.18556-gsq-gumbel-softmax-quantization-llm.md) | Gumbel-Softmax緩和でスカラー量子化をベクトル量子化レベルに引き上げ、Kimi-K2.5等の兆規模MoEにも適用可能 |
| [StepPO: Step-Aligned Policy Optimization for Agentic Reinforcement Learning](papers/2604.18401-steppo-step-aligned-agentic-rl.md) | エージェントRLをトークンからステップレベルMDPへ昇格しツール使用・意思決定の粒度でクレジット割り当て |
| [River-LLM: Seamless Early Exit via KV Share](papers/2604.18396-river-llm-early-exit-kv-share.md) | ACL 2026：KVキャッシュ欠如問題を共有リバーで解消しLLM推論を1.71〜2.16倍高速化（学習不要） |
| [Dual Alignment: LLM Layers vs Human Sentence Processing](papers/2604.18563-dual-alignment-llm-layers-sentence-processing.md) | ACL 2026 Main：前半層≒自然読解、後半層≒統語的難文処理という二重アライメントを発見 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [Sessa: Selective State Space Attention](papers/2604.18580-sessa-selective-state-space-attention.md) | GitHub公開：AttentionをフィードバックパスへFusion、長距離依存性をべき乗則メモリで保持しTransformer/Mambaを超える |
| [BRRL: Bounded Ratio Reinforcement Learning](papers/2604.18578-brrl-bounded-ratio-reinforcement-learning.md) | PPOを信頼領域から理論再導出したBPO/GBPOを提案、MuJoCo・Humanoid・LLMファインチューニングでPPO/GRPO匹敵以上 |
| [When Can LLMs Learn to Reason with Weak Supervision?](papers/2604.18574-when-llm-learn-reason-weak-supervision.md) | 報酬飽和ダイナミクスと推論忠実度がRLVR汎化を規定、SFTがRLVR汎化の必要条件と実証 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [T-REN: Text-Aligned Region Tokens for Dense Vision-Language Alignment](papers/2604.18573-t-ren-text-aligned-region-encoder.md) | GitHub公開：3.7%パラメータ追加でセグメンテーション+5.9 mIoU、動画トークン数187倍削減 |
| [MUA: Mobile Ultra-detailed Animatable Avatars](papers/2604.18583-mua-mobile-ultra-detailed-animatable-avatars.md) | 高品質アバターを2000倍低コスト・10倍小モデルにモバイル蒸留、Meta Quest 3で24FPS達成 |
| [Back into Plato's Cave: Cross-modal Representational Convergence at Scale](papers/2604.18572-back-into-platons-cave-cross-modal-convergence.md) | Platonic Representation Hypothesis の実証的証拠がスケールで消えることを示す批判的論文 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [MathNet: Global Multimodal Benchmark for Math Reasoning & Retrieval](papers/2604.18584-mathnet-multimodal-multilingual-math-benchmark.md) | ICLR 2026・MIT：47カ国17言語3万問のオリンピック数学ベンチマーク、数学問題検索の初評価基盤 |
| [BLF: Agentic Forecasting via Bayesian Linguistic Beliefs](papers/2604.18576-blf-bayesian-linguistic-forecaster.md) | Google Research（Kevin Murphy）：ForecastBenchでGPT-5・Grok 4.20を超えるベイジアン予測エージェント |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [DAG-STL: Zero-Shot Trajectory Planning under Signal Temporal Logic](papers/2604.18343-dag-stl-hierarchical-trajectory-planning.md) | 未知ダイナミクス下でSTL制約のゼロショット長距離計画—論理分解×ウェイポイント割り当て×拡散生成の3段階 |
| [SNOOPIE: Robot Quadruped Pacer Trainer for Interval Running](papers/2604.18331-snoopie-robot-quadruped-pacer-trainer.md) | ICRA 2026：Apple Watch比60.6%高いペース遵守率を達成した四足ロボットペーサートレーナー |

---

## 2026-04-20 注目論文：4/16-17公開分（SIGIR/ACL/CVPR 2026採択・産業応用中心）

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [GenRec: A Preference-Oriented Generative Framework for Large-Scale Recommendation](papers/2604.14878-genrec-preference-oriented-generative-recommendation.md) | SIGIR 2026・産業デプロイ済み：大規模Generative Retrievalの3課題（一貫性・エンコードコスト・嗜好アライメント）を同時解決 |
| [Category-based and Popularity-guided Video Game Recommendation](papers/2604.14598-category-popularity-video-game-recommendation.md) | WWW 2024・GitHub公開：精度×多様性×人気バイアスをバランスするビデオゲーム推薦フレームワーク |
| [Well Begun is Half Done: Training-Free User Representation Initialization for Multimodal Rec](papers/2604.14839-training-free-user-representation-initialization-multimodal-rec.md) | SIGIR 2026：既存マルチモーダル推薦が見落とすユーザー表現初期化問題を学習不要・モデル非依存で解決 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [MARS²: Scaling Multi-Agent Tree Search via RL for Code Generation](papers/2604.14564-mars2-multi-agent-tree-search-code-generation.md) | ACL 2026・GitHub公開：マルチエージェントツリー探索×RLでコード生成の多様性と性能上限を大幅向上 |
| [RACER: Retrieval-Augmented Contextual Rapid Speculative Decoding](papers/2604.14885-racer-retrieval-augmented-speculative-decoding.md) | ACL 2026 Findings・GitHub公開：検索ベース×ロジットベースドラフトを相補的統合しLLM推論を高速化 |
| [Modeling LLM Unlearning as an Asymmetric Two-Task Learning Problem](papers/2604.14808-llm-unlearning-asymmetric-two-task.md) | ACL 2026：LLM Machine Unlearningを保持主・忘却従の非対称二タスクに再定式化し保持優先勾配合成を提案 |
| [XQ-MEval: Cross-lingual Parallel Quality Dataset for Translation Metrics](papers/2604.14934-xq-meval-crosslingual-translation-metrics.md) | ACL 2026 Findings・Meta FAIR：翻訳品質の言語間スコアバイアスを初の体系的研究、並列品質ベンチマーク構築 |
| [Explain the Flag: Contextualizing Hate Speech Beyond Censorship](papers/2604.14970-explain-the-flag-hate-speech-contextualization.md) | ACL 2026 Findings：検閲を超えてヘイトスピーチを文脈化・説明するアプローチ、透明性と表現の自由を両立 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [MambaSL: Exploring Single-Layer Mamba for Time Series Classification](papers/2604.15174-mambasl-single-layer-mamba-time-series.md) | ICLR 2026：単一層Mambaを4仮説で再設計し時系列分類を包括評価、SSMの時系列応用を開拓 |
| [Mean Flow Policy Optimization](papers/2604.14698-mean-flow-policy-optimization.md) | Google DeepMind・GitHub公開：MeanFlow（少ステップFlow）でポリシー表現し拡散ポリシーRLの推論コスト問題を解決 |
| [LAMAE: Latent Attention MAE for Multi-View Echocardiography](papers/2604.15096-lamae-multi-view-echocardiography.md) | ICLR 2026 Workshop：潜在アテンションMAEでマルチビュー心エコー図の時空間構造を統合する医療AIモデル |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [Bi-CMPStereo: Bidirectional Cross-Modal Prompting for Event-Frame Stereo](papers/2604.15312-bicmpstereo-event-frame-stereo.md) | CVPR 2026・GitHub公開：双方向クロスモーダルプロンプティングでEvent-Frameステレオのモダリティギャップを克服 |
| [G-MIXER: Geodesic Mixup for Zero-Shot Composed Image Retrieval](papers/2604.14710-gmixer-geodesic-mixup-composed-image-retrieval.md) | CVPR 2026・GitHub公開：Geodesic Mixupで潜在空間補間しZS-CIRの暗黙的ビジュアル情報損失を解決 |
| [Robustness of Vision Foundation Models to Common Perturbations](papers/2604.14973-robustness-vision-foundation-models-perturbations.md) | CVPR 2026 Workshop・Meta：CLIP/DINOv2等のFoundation Model埋め込みが一般的画像編集に対してどれだけ堅牢かを初の体系的研究 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [Meituan Merchant Diagnosis via Policy-Guided Dual-Process User Simulation](papers/2604.15190-meituan-merchant-diagnosis-user-simulation.md) | SIGIR 2026 Industry Track・美団：二重プロセスユーザーシミュレーションでオンライン実験不要のマーチャント戦略評価 |
| [Discovering Novel LLM Experts via Task-Capability Coevolution](papers/2604.14969-discovering-llm-experts-task-capability-coevolution.md) | ICLR 2026：タスクとモデル能力の共進化（coevolution）により単一runで新規スキルを持つLLMを自動発見 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [R3D: Revisiting 3D Policy Learning](papers/2604.15281-r3d-revisiting-3d-policy-learning.md) | GitHub公開：3Dポリシー学習の不安定性・過学習の根本原因（3D拡張なし・BN悪影響）を特定し安定化設計原則を提案 |
| [Keep It CALM: Kilometer-Level SLAM with Visual Geometry Foundation Models](papers/2604.14795-calm-kilometer-slam-visual-geometry.md) | IEEE TPAMI投稿・GitHub公開：VGFMの非線形幾何歪みをAssistant Eyeで補正しキャリブレーション不要の長距離SLAMを実現 |

---

## 2026-04-18 注目論文：4/16公開分（産業推薦・LLM評価・3DGS・ヒューマノイド中心）

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [SAGER: Self-Evolving User Policy Skills for Recommendation Agent](papers/2604.14972-sager-self-evolving-user-policy-skills-recommendation-agent.md) | LLM推薦エージェントの推論ロジック自体をユーザーごとに自己進化させる新パラダイム |
| [GenRec: Preference-Oriented Generative Framework for Large-Scale Recommendation](papers/2604.14878-genrec-preference-oriented-generative-recommendation.md) | 産業スケールのGenerative Retrievalを妨げる3課題（一貫性・エンコードコスト・嗜好整合）を解決 |
| [Don't Retrieve, Navigate: Corpus2Skill for QA and RAG](papers/2604.14572-corpus2skill-dont-retrieve-navigate.md) | コーパスを階層的スキルディレクトリに蒸留しエージェントがナビゲーション、RAGの受動的限界を超える |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [SpecGuard: Verification-Aware Speculative Decoding](papers/2604.15244-specguard-verification-aware-speculative-decoding.md) | ステップレベル検証でSpeculative Decodingの誤り伝播を防止、外部報酬モデル不要 |
| [K-Token Merging: Latent Space Compression for LLMs](papers/2604.15153-k-token-merging-latent-space-compression-llm.md) | トークン空間でなくlatent埋め込み空間でK個マージ、長文処理コストを大幅削減 |
| [APEX-MEM: Agentic Semi-Structured Memory with Temporal Reasoning](papers/2604.14362-apex-mem-agentic-semi-structured-memory.md) | プロパティグラフ＋時間的推論で長期会話メモリを実現、矛盾解決と時系列クエリに対応 |
| [Context Over Content: Exposing Evaluation Faking in LLM Judges](papers/2604.15224-context-over-content-evaluation-faking-llm-judge.md) | LLM-as-judgeに「判定が評価対象モデルの存続に影響」と伝えるだけで判定が歪むstakes signalingを発見 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [AdaSplash-2: Faster Differentiable Sparse Attention](papers/2604.15180-adasplash-2-faster-differentiable-sparse-attention.md) | ヒストグラムベース初期化でα-entmax sparse attentionをsoftmaxに迫る速度へ |
| [Stability and Generalization in Looped Transformers](papers/2604.15259-stability-generalization-looped-transformers.md) | test-time compute scalingの要であるLooped Transformerの安定性・汎化境界を理論的に解明 |
| [RL-STPA: System-Theoretic Hazard Analysis for Safety-Critical RL](papers/2604.15201-rl-stpa-safety-critical-reinforcement-learning.md) | 工業安全のSTPAをRLに適応、ブラックボックスRLエージェントの危険を体系的に特定 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [GlobalSplat: Efficient Feed-Forward 3DGS via Global Scene Tokens](papers/2604.15284-globalsplat-efficient-feed-forward-3dgs.md) | グローバルシーントークンで3DGSプリミティブを効率配置、速度×品質×コンパクト性を同時改善 |
| [LeapAlign: Post-Training Flow Matching Models at Any Step](papers/2604.15311-leapalign-post-training-flow-matching-alignment.md) | 2ステップ軌跡構築で任意生成ステップからフローマッチングモデルをアライメント |
| [R3D: Revisiting 3D Policy Learning](papers/2604.15281-r3d-revisiting-3d-policy-learning.md) | 3Dポリシー学習の不安定性・過学習の根本原因を特定し安定化設計原則を導出 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [Meituan Merchant Business Diagnosis via Dual-Process User Simulation](papers/2604.15190-meituan-merchant-business-diagnosis-dual-process.md) | 美団が産業展開するデュアルプロセスユーザーシミュレーション、オンライン実験代替として加盟店診断 |
| [CoopEval: LLM Agents in Social Dilemmas](papers/2604.15267-coopeval-benchmarking-cooperation-llm-agents-social-dilemmas.md) | 推論能力が高いLLMほど社会的ジレンマで裏切る傾向があることをベンチマークで実証 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [Switch: Learning Agile Skills Switching for Humanoid Robots](papers/2604.14834-switch-agile-skills-switching-humanoid-robots.md) | ヒューマノイドのスキル間遷移をDRLで明示的に学習、アジャイルな複合動作を実現 |
| [Abstract Sim2Real through Approximate Information States](papers/2604.15289-abstract-sim2real-approximate-information-states.md) | 高精度物理シミュレーター不要の情報理論的Sim2Real転移フレームワーク |

---

## 2026-04-16 注目論文：4/14公開分（SIGIR/ACL/ICLR/CVPR/ICRA中心）

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [Sparse Contrastive Learning for Content-Based Cold Item Recommendation](papers/2604.12990-sparse-contrastive-learning-cold-item-recommendation.md) | SIGIR 2026採択、コールドアイテム推薦を疎コントラスト学習で改善 |
| [AdversarialCoT: Single-Document Retrieval Poisoning for LLM Reasoning](papers/2604.12201-adversarialcot-single-document-retrieval-poisoning.md) | SIGIR 2026 short、単一文書汚染でRAG推論を崩す攻撃を提示 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [Toward Autonomous Long-Horizon Engineering for ML Research](papers/2604.13018-aiscientist-long-horizon-ml-research-engineering.md) | 長ホライズンML研究開発を自律化するAiScientist、コード公開 |
| [Rethinking On-Policy Distillation of Large Language Models: Phenomenology, Mechanism, and Recipe](papers/2604.13016-rethinking-on-policy-distillation-of-large-language-models.md) | THUNLP、OPDの現象論と実践レシピを整理してコード公開 |
| [Towards Excellent Comprehension of Public Policy for Large Language Models](papers/2604.12995-policyllm-public-policy-comprehension.md) | ACL 2026 Findings、公共政策読解に特化したPolicyBench/PolicyMoE |
| [EvoSpark: Endogenous Interactive Agent Societies for Unified Long-Horizon Narrative Evolution](papers/2604.12776-evospark-agent-societies-long-horizon-narrative-evolution.md) | ACL 2026 Main、エージェント社会で長編物語を進化生成 |
| [Generating Effective CoT Traces for Mitigating Causal Hallucination](papers/2604.12748-effective-cot-traces-mitigating-causal-hallucination.md) | ACL 2026、因果ハルシネーションを抑えるCoT trace生成 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [The Verification Tax: Fundamental Limits of AI Auditing in the Rare-Error Regime](papers/2604.12951-verification-tax-fundamental-limits-ai-auditing.md) | AI監査の“verification tax”を定式化、コード公開 |
| [SpecBound: Adaptive Bounded Self-Speculation with Layer-wise Confidence Calibration](papers/2604.12247-specbound-adaptive-bounded-self-speculation.md) | ACL 2026 Findings、較正付きself-speculationで効率化 |
| [LLM-Enhanced Log Anomaly Detection: A Comprehensive Benchmark of Large Language Models for Automated System Diagnostics](papers/2604.12218-llm-enhanced-log-anomaly-detection-benchmark.md) | ログ異常検知LLMベンチマークを公開 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [Lyra 2.0: Explorable Generative 3D Worlds](papers/2604.13036-lyra-2-explorable-generative-3d-worlds.md) | NVIDIA、動画生成から探索可能3D世界を構築するLyra 2.0 |
| [Don't Show Pixels, Show Cues: Unlocking Visual Tool Reasoning in Language Models via Perception Programs](papers/2604.12896-dont-show-pixels-show-cues-perception-programs.md) | CVPR 2026、Perception Programsで視覚ツール推論を強化 |
| [Chain-of-Models Pre-Training: Rethinking Training Acceleration of Vision Foundation Models](papers/2604.12391-chain-of-models-pre-training-vision-foundation-models.md) | CVPR 2026、Chain-of-ModelsでVFM事前学習を加速 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [ROSE: An Intent-Centered Evaluation Metric for NL2SQL](papers/2604.12988-rose-intent-centered-evaluation-metric-for-nl2sql.md) | ACL 2026 Main、NL2SQLを意図中心に測るROSE |
| [Latent Planning Emerges with Scale](papers/2604.12493-latent-planning-emerges-with-scale.md) | ICLR 2026、スケールでlatent planningが自然発現 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [GGD-SLAM: Monocular 3DGS SLAM Powered by Generalizable Motion Model for Dynamic Environments](papers/2604.12837-ggd-slam-generalizable-motion-model-dynamic-environments.md) | ICRA 2026、動的環境向け3DGS SLAMを改善 |
| [Unveiling the Surprising Efficacy of Navigation Understanding in End-to-End Autonomous Driving](papers/2604.12208-navigation-understanding-end-to-end-autonomous-driving.md) | ICRA 2026、E2E自動運転でnavigation understandingの効き目を実証 |


## 2026-04-14 注目論文：4/13新着なしのため4/10公開分から選定

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [Beyond Relevance](papers/2604.08920-beyond-relevance-utility-centric-retrieval-in-the-llm-era.md) | SIGIR 2026採択、検索目的をutility最適化へ再定義 |
| [BracketRank](papers/2604.08834-bracketrank-large-language-model-document-ranking-via-reasoning-based-competitive-elimination.md) | ACL 2026、推論型競争淘汰で順序感度を低減 |
| [IAT](papers/2604.08933-iat-instance-as-token-compression-for-historical-user-sequence-modeling-in-industrial-recommender-systems.md) | 産業推薦の長期履歴をInstance-as-Tokenで圧縮 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [RecaLLM](papers/2604.09494-recallm-addressing-the-lost-in-thought-phenomenon-with-explicit-in-context-retrieval.md) | long-contextのlost-in-thoughtを明示的retrievalで抑制（GitHub） |
| [Task-Aware LLM Routing](papers/2604.09377-task-aware-llm-routing-with-multi-level-task-profile-guided-data-synthesis-for-cold-start-scenarios.md) | ACL 2026、タスクプロファイルで冷スタートルーティング |
| [EthicMind](papers/2604.09265-ethicmind-a-risk-aware-framework-for-ethical-emotional-alignment-in-multi-turn-dialogue.md) | ACL 2026、倫理×感情のリスク整合フレームワーク |
| [SPASM](papers/2604.09212-spasm-stable-persona-driven-agent-simulation-for-multi-turn-dialogue-generation.md) | ACL Findings、ペルソナ一貫性を保つ対話生成（GitHub） |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [SafeAdapt](papers/2604.09452-safeadapt-provably-safe-policy-updates-in-deep-reinforcement-learning.md) | 安全RLの保証付き方策更新（GitHub） |
| [U-Cast](papers/2604.09041-u-cast-a-surprisingly-simple-and-efficient-frontier-probabilistic-ai-weather-forecaster.md) | シンプル構成の確率的気象予測（GitHub） |
| [Value-Aware SeqComm](papers/2604.08944-multi-agent-decision-focused-learning-via-value-aware-sequential-communication.md) | ICML 2026投稿、価値指向通信で協調性能向上（GitHub） |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [Tango](papers/2604.09547-tango-taming-visual-signals-for-efficient-video-large-language-models.md) | Video LLMのトークン削減で高速化（GitHub） |
| [VL-Calibration](papers/2604.09529-vl-calibration-decoupled-confidence-calibration-for-large-vision-language-models-reasoning.md) | ACL 2026、視覚/推論信頼度の分離で幻覚抑制（GitHub） |
| [Envisioning the Future](papers/2604.09527-envisioning-the-future-one-step-at-a-time.md) | CVPR 2026、疎軌跡拡散で多様な未来予測 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [E3-TIR](papers/2604.09455-e3-tir-enhanced-experience-exploitation-for-tool-integrated-reasoning.md) | ACL 2026、ツール統合推論の経験活用RL |
| [SPPO](papers/2604.08865-sppo-sequence-level-ppo-for-long-horizon-reasoning-tasks.md) | ACL 2026、sequence-level PPOで長文推論を安定化 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [Adaptor](papers/2604.09462-adaptor-advancing-assistive-teleoperation-with-few-shot-learning-and-cross-operator-generalization.md) | ICRA 2026、少数ショットで操作者適応 |
| [AssemLM](papers/2604.08983-assemlm-spatial-reasoning-multimodal-large-language-models-for-robotic-assembly.md) | 組立向け空間推論VLM（Project page） |

## 2026-04-13 注目論文：4/12新着なしのため4/9公開分から選定

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [Walmart Sponsored Search Retrieval](papers/2604.07930-unified-supervision-for-walmarts-sponsored-search-retrieval-via-joint-semantic-relevance-and-behavioral-engagement-modeling.md) | Walmartスポンサー検索で意味的関連性重視の統合監督、ABでNDCG改善 | 
| [Trace-Level GUI-Agent Evaluation](papers/2604.07929-same-outcomes-different-journeys-a-trace-level-framework-for-comparing-human-and-gui-agent-behavior-in-production-search-systems.md) | 本番検索で人間とGUIエージェントの行動乖離をトレース評価 | 

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [PIArena](papers/2604.08499-piarena-a-platform-for-prompt-injection-evaluation.md) | プロンプトインジェクション評価基盤、動的攻撃で防御限界を可視化 | 
| [TRB](papers/2604.07816-tool-retrieval-bridge-aligning-vague-instructions-with-retriever-preferences-via-bridge-model.md) | 曖昧指示を橋渡し変換してツール検索NDCGを大幅改善 | 
| [The Art of (Mis)alignment](papers/2604.07754-the-art-of-mis-alignment-how-fine-tuning-methods-effectively-misalign-and-realign-llms-in-post-training.md) | SFT/PFTのmisalignment/realignment差を体系比較 | 

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [ResComp](papers/2604.07955-rethinking-residual-errors-in-compensation-based-llm-quantization.md) | 補償型量子化の残差再定義でGPTQ/GPTAQ性能を改善 | 
| [Aerospace FL Quantization](papers/2604.08474-quantization-impact-on-the-accuracy-and-communication-efficiency-trade-off-in-federated-learning-for-aerospace-predictive-maintenance.md) | INT4で精度維持し通信量8x削減、非IID評価の重要性 | 
| [Weather-GS](papers/2604.07928-generative-3d-gaussian-splatting-for-arbitrary-resolutionatmospheric-downscaling-and-forecasting.md) | 3D Gaussian splattingで任意解像度の気象予測/ダウンスケール | 

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [BLaDA](papers/2604.08410-blada-bridging-language-to-functional-dexterous-actions-within-3dgs-fields.md) | 言語→機能領域→把持を結ぶ可解釈なゼロショット操作 | 
| [SyncBreaker](papers/2604.08405-syncbreaker-stage-aware-multimodal-adversarial-attacks-on-audio-driven-talking-head-generation.md) | 音声×画像摂動でtalking-head生成を強力に妨害 | 
| [SciFigDetect](papers/2604.08211-scifigdetect-a-benchmark-for-ai-generated-scientific-figure-detection.md) | AI生成科学図表検出ベンチで既存検出器の弱さを示す | 

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [Encrypted Traffic Reasoning Benchmark](papers/2604.08140-multimodal-reasoning-with-llm-for-encrypted-traffic-interpretation-a-benchmark.md) | 暗号化トラフィック解釈のBGTDベンチとmmTrafficを提案 | 

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [Karma MAPF](papers/2604.07970-karma-mechanisms-for-decentralised-cooperative-multi-agent-path-finding.md) | 分散MAPFでKarma交渉を使い公平性と効率を両立 | 

## 2026-04-12 注目論文：SIGIR/ACL/CVPR/自動運転ベンチ — （4/11新着なしのため4/9公開分から選定）

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [ACGM](papers/2604.07863-task-adaptive-retrieval-over-agentic-multi-modal-web-histories-via-learned-graph-memory.md) | エージェント履歴をグラフ記憶で検索、SIGIR採択、GitHub | 
| [ReRec](papers/2604.07851-rerec-reasoning-augmented-llm-based-recommendation-assistant-via-reinforcement-fine-tuning.md) | RFTで推論強化推薦、ACL 2026、GitHub | 
| [KnowSA_CKP](papers/2604.07825-filling-the-gaps-selective-knowledge-augmentation-for-llm-recommenders.md) | 選択的知識注入でLLM推薦の効率改善、SIGIR 2026 | 

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [SeLaR](papers/2604.08299-selective-latent-reasoning-in-large-language-models.md) | 低信頼ステップのみ潜在推論、ACL 2026 | 
| [DMLE](papers/2604.08284-distributed-multi-layer-editing-for-rule-level-knowledge-in-large-language-models.md) | ルール知識を分散編集、RuleEdit拡張、GitHub | 
| [RRC Steganography](papers/2604.08052-efficient-provably-secure-linguistic-steganography-via-range-coding.md) | Range codingで高効率ステガノグラフィ、ACL 2026、GitHub | 

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [DMax](papers/2604.08302-aggressive-parallel-decoding-for-dllms.md) | 拡散LM並列デコードを自己精錬、TPS改善、GitHub | 
| [brainCodec](papers/2604.08537-meta-learning-in-context-enables-training-free-cross-subject-brain-decoding.md) | fMRIクロスサブジェクトをtraining-free推定、CVPR 2026、GitHub | 
| [GenCircuit](papers/2604.08192-measuring-generalization-in-vision-transformers-through-inner-workings.md) | 回路ベース汎化指標、CVPR 2026 Highlight、GitHub | 

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [NUMINA](papers/2604.08546-aligning-textual-numerals-and-visual-instances-in-text-to-video-diffusion-models.md) | T2Vの数指定を修正するtraining-free手法、CVPR 2026、GitHub | 
| [ETCH-X](papers/2604.08548-robustify-expressive-body-fitting-to-clothed-humans-with-composable-datasets.md) | 衣服付き3D人体フィッティングをrobust化、GitHub | 
| [ParseBench](papers/2604.08538-parsebench-a-document-parsing-benchmark-for-ai-agents.md) | エージェント向け文書解析ベンチ、HF+GitHub | 

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [SUPERNOVA](papers/2604.08477-supernova-eliciting-general-reasoning-in-llms-with-reinforcement-learning-on-natural-instructions.md) | 自然指示からRLVRデータ設計で汎用推論改善、GitHub | 
| [Clinical World Model](papers/2604.08226-grounding-clinical-ai-competency-in-human-cognition-through-the-clinical-world-model-and-skill-mix-framework.md) | 臨床AI能力をSkill-Mix座標で定義、GitHub | 

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [Fail2Drive](papers/2604.08535-fail2drive-benchmarking-closed-loop-driving-generalization.md) | 分布シフトpaired-routeベンチで自動運転汎化を測定、GitHub | 
| [RoboAgent](papers/2604.07774-chaining-basic-capabilities-for-embodied-task-planning.md) | 能力チェーン型計画、CVPR 2026、GitHub | 

## 2026-04-10 注目論文：マルチモーダル推論検索HIVE/BRIDGE/MARVEL／推論データ選別ASLEC／AlignPrune／EVGeoQA／Genie Sim PanoRecon

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [HIVE](papers/2604.07220-hive-query-hypothesize-verify-an-llm-framework-for-multimodal-reasoning-intensiv.md) | HIVEが仮説生成→検証の反復推論でMM-BRIGHTのマルチモーダル検索精度を改善（GitHub） |
| [BRIDGE](papers/2604.07201-bridge-multimodal-to-text-retrieval-via-reinforcement-learned-query-alignment.md) | BRIDGEがRLでクエリアラインメントを学習し画像＋テキスト検索を安定化（GitHub） |
| [MARVEL](papers/2604.07079-marvel-multimodal-adaptive-reasoning-intensive-expand-rerank-and-retrieval.md) | MARVELが拡張・推論検索・再ランクを統合した推論強化検索パイプライン（GitHub） |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [ClickGuard](papers/2604.07272-clickguard-a-trustworthy-adaptive-fusion-framework-for-clickbait-detection.md) | ClickGuardがBERT＋構造特徴の適応融合でクリックベイト検知を強化（GitHub） |
| [Efficient Learned Data Compression](papers/2604.07239-efficient-learned-data-compression-via-dual-stream-feature-decoupling.md) | FADEがDual-Stream分離で学習型圧縮の遅延を抑制（GitHub） |
| [ChunQiuTR](papers/2604.06997-chunqiutr-time-keyed-temporal-retrieval-in-classical-chinese-annals.md) | ChunQiuTRが在位月表現の時間整合を扱う古典中国史料検索を提案（GitHub） |
| [Step Length Confounding](papers/2604.06834-on-the-step-length-confounding-in-llm-reasoning-data-selection.md) | ASLECがCoT長さバイアスを補正し推論データ選別を改善（GitHub） |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [How to sketch a learning algorithm](papers/2604.07328-how-to-sketch-a-learning-algorithm.md) | データ削除影響を高速近似する学習アルゴリズムのスケッチ法（GitHub） |
| [ConceptTracer](papers/2604.07019-concepttracer-interactive-analysis-of-concept-saliency-and-selectivity-in-neural.md) | ConceptTracerが概念サリエンシーを対話可視化する解析ツール（GitHub） |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [AlignPrune](papers/2604.07306-beyond-loss-values-robust-dynamic-pruning-via-loss-trajectory-alignment.md) | AlignPruneが損失軌跡でノイズに強い動的プルーニングを実現（GitHub） |
| [CAAP](papers/2604.06987-caap-capture-aware-adversarial-patch-attacks-on-palmprint-recognition-models.md) | CAAPが掌紋認証向けの撮像考慮パッチ攻撃を評価（GitHub） |
| [CloudMamba](papers/2604.06844-cloudmamba-an-uncertainty-guided-dual-scale-mamba-network-for-cloud-detection-in.md) | CloudMambaが不確実性誘導の二段Mambaで雲検出を改善（GitHub） |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [EVGeoQA](papers/2604.07070-evgeoqa-benchmarking-llms-on-dynamic-multi-objective-geo-spatial-exploration.md) | EVGeoQAが動的制約下の地理探索を測るLLMベンチマーク（GitHub） |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [Genie Sim PanoRecon](papers/2604.07105-genie-sim-panorecon-fast-immersive-scene-generation-from-single-view-panorama.md) | Genie Sim PanoReconが単一パノラマから高速3D生成を可能に（GitHub） |

## 2026-04-09 注目論文：ICLR 2026 OralのIn-Place TTT／ACL 2026 4本（RAG改写偏り・LLM集団社会力学）／CVPR Findings PoM／ICRA 2026 デバリングMPC

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [Masking or Mitigating?](papers/2604.06097-masking-or-mitigating-deconstructing-the-impact-of-query-rewriting-on-retriever-) | **ACL 2026**、クエリ改写がRAG検索偏りに与える影響を体系化 |
| [Data, Not Model](papers/2604.06163-data-not-model-explaining-bias-toward-llm-texts-in-neural-retrievers) | LLM文書優遇の原因はデータ監督にあると示し、埋め込み補正で軽減 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [Paper Circle](papers/2604.06170-paper-circle-an-open-source-multi-agent-research-discovery-and-analysis-framewor) | **ACL 2026 Oral**、論文探索→知識グラフ化のマルチエージェント基盤、GitHub |
| [The Model Agreed, But Didn't Learn](papers/2604.05995-the-model-agreed-but-didnt-learn-diagnosing-surface-compliance-in-large-language) | **ACL Findings**、知識編集のsurface compliance問題を診断、GitHub |
| [Structure Snowballing](papers/2604.06066-from-hallucination-to-structure-snowballing-the-alignment-tax-of-constrained-dec) | 構造化反省が逆にフォーマット罠を誘発する「alignment tax」、GitHub |
| [Social Dynamics in LLM Collectives](papers/2604.06091-social-dynamics-as-critical-vulnerabilities-that-undermine-objective-decision-ma) | **ACL 2026**、LLM集団の同調/権威/レトリック脆弱性を検証 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [In-Place Test-Time Training](papers/2604.06169-in-place-test-time-training) | **ICLR 2026 Oral**、MLP投影をfast weights化するTTT、GitHub |
| [Target Policy Optimization](papers/2604.06159-target-policy-optimization) | 目標分布qに合わせるRLVR更新で疎報酬に強化、GitHub |
| [Consistent World Models](papers/2604.06155-toward-consistent-world-models-with-multi-token-prediction-and-latent-semantic-e) | **ACL 2026**、LSE-MTPで構造的幻覚を抑制 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [PoM](papers/2604.06129-pom-a-linear-time-replacement-for-attention-with-the-polynomial-mixer) | **CVPR Findings 2026**、線形時間のAttention置換、GitHub |
| [Graph-PiT](papers/2604.06074-graph-pit-enhancing-structural-coherence-in-part-based-image-synthesis-via-graph) | **ICME 2026**、部品関係グラフで構造整合な画像生成、GitHub |
| [Extending ZACH-ViT](papers/2604.06099-extending-zach-vit-to-robust-medical-imaging-corruption-and-adversarial-stress-t) | **CVPR 2026 WS**、低データ医用画像の腐食/敵対耐性評価 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [Claw-Eval](papers/2604.06132-claw-eval-toward-trustworthy-evaluation-of-autonomous-agents) | 300タスクの軌跡評価ベンチで安全/頑健性を可視化 |
| [Epistemic Blinding](papers/2604.06013-epistemic-blinding-an-inference-time-protocol-for-auditing-prior-contamination-i) | LLMの事前知識混入を測る匿名化プロトコル、GitHub |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [Learning-Guided Force-Feedback MPC](papers/2604.06133-learning-guided-force-feedback-model-predictive-control-with-obstacle-avoidance-) | **ICRA 2026**、拡散priors＋力フィードバックMPCで産業デバリング |

## 2026-04-08 注目論文：SIGIR 2026 2本／ACL 2026 2本／CVPR 2026 3本／エージェントプロトコルANX OSS／低コスト産業用bin picking

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [Beyond Hard Negatives](papers/2604.04734-score-distribution-kd) | **SIGIR 2026 Main**、KDでスコア分布を保つ層別サンプリングを提案 |
| [FAVE](papers/2604.04427-fave) | **SIGIR 2026採択**、拡散推薦を1-step生成にして桁違い高速化 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [LiveFact](papers/2604.04815-livefact) | **ACL 2026 Main**、時間変化を扱う動的ファクトチェックベンチ |
| [Beyond the Final Actor](papers/2604.04932-dual-roles-detector) | **ACL 2026採択**、生成者/編集者の二重役割を区別する検知 |
| [PassiveQA](papers/2604.04565-passiveqa) | 不完全質問に「答える/確認/保留」3アクション、GitHub公開 |
| [TriAttention](papers/2604.04921-triattention) | 三角関数KV圧縮で長文推論のメモリ問題を軽減、GitHub |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [Prompt Selection Necessary?](papers/2604.04420-prompt-selection-ocl) | **CVPR Findings 2026**、単一プロンプトでも競合に近い性能、GitHub |
| [Cog-DRIFT](papers/2604.04767-cog-drift) | 難問を学習可能に再構成してRLVRを改善、GitHub |
| [Sampling Parallelism](papers/2604.04736-sampling-parallelism) | 実運用UQ向けにベイズ学習のサンプリングを並列化 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [PointTPA](papers/2604.04933-pointtpa) | **CVPR 2026**、点群理解の推論時パラメータ適応、GitHub |
| [Delta Tokens](papers/2604.04913-delta-tokens) | **CVPR 2026**、世界モデルの生成を軽量化、コード/重み公開 |
| [AvatarPointillist](papers/2604.04787-avatarpointillist) | **CVPR 2026**、単一画像から4D Gaussianアバター生成、PJページ |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [ANX Protocol](papers/2604.04820-anx-protocol) | エージェント連携をプロトコルファーストで設計、OSS公開 |
| [SuperLocalMemory v3.3](papers/2604.04514-superlocalmemory-v33) | LLM非依存のローカル記憶基盤、GitHub公開 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [Pickalo](papers/2604.04690-pickalo) | 低コスト機材で産業用bin pickingを実運用想定で実現 |

## 2026-04-07 注目論文：昨日分の新着なし（直近 2026-04-03 公開分）— Prompt Compression／MBGR本番デプロイ／LogicPoison／RCL／VOSR／Chart-RL／DreamTIP

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [Prompt Compression in the Wild](papers/2604.02985-prompt-compression) | **ECIR 2026**、圧縮の損益分岐を大規模測定、最大18%高速化 |
| [MBGR](papers/2604.02684-mbgr) | **美団本番デプロイ**のマルチ事業生成推薦、BID+MBP+LDR |
| [GTC](papers/2604.03014-gtc) | ユーザー条件拡散+Total CorrelationでMMR改善、NDCG@5最大+28.3%、GitHub |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [Memorization Signature](papers/2604.03199-memorization-signature) | LT-MIAで記憶シグネチャを学習、Mamba/RWKVへ転移、GitHub |
| [LogicPoison](papers/2604.02954-logicpoison) | GraphRAGの論理構造を毒化する攻撃、ステルス性高、GitHub |
| [RAG Impracticality Benchmark](papers/2604.02640-rag-impracticality) | 企業RAG向け4軸診断ベンチ、**AAAI WS**採択 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [RCL](papers/2604.03189-rcl) | 文脈最適化を統一枠組み化、最適化プリミティブで改善、GitHub |
| [Hierarchical Planning](papers/2604.03208-hierarchical-planning) | 潜在世界モデルを階層化し長期計画、実機70%成功 |
| [Random vs APL](papers/2604.02766-random-vs-apl) | online DPOのActive選択はRandomに勝てず、能力崩壊を指摘、GitHub |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [VOSR](papers/2604.03225-vosr) | Vision-only SRでT2I不要、学習コスト1/10、**CVPR 2026**、GitHub |
| [SD-FSMIS](papers/2604.03134-sd-fsmis) | Stable DiffusionをFew-shot医用セグに適応、**CVPR 2026** |
| [GenSmoke-GS](papers/2604.03039-gensmoke-gs) | 煙劣化NVSで**NTIRE 3DRR優勝**、GitHub |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [Chart-RL](papers/2604.03157-chart-rl) | ChartQAをRL最適化、精度向上&遅延31s→9s、**KDD 2026** |
| [InfoSeeker](papers/2604.02971-infoseeker) | 階層並列エージェントで情報統合、3–5x高速、GitHub |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [Offroad-Nav Stack](papers/2604.03096-offroad-nav) | LiDAR/単眼両対応のオフロード自律走行スタック、GitHub |
| [DreamTIP](papers/2604.02911-dreamtip) | タスク不変特性で四足ロボ転移、**ICRA 2026**採択 |

---

## 2026-04-06 注目論文：週末で新着なし（直近 2026-04-02 公開分）— MAVRSサーベイ／MoE解釈／SPAR高解像度セグ／CORAL自律進化

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [EU20 QA](papers/2604.01957-eu20-qa) | EU20翻訳ベンチを三段階で自動QA、品質指標と修正版を公開 |
| [MAVRS Survey](papers/2604.02211-mavrs-survey) | 動画推薦のマルチエージェント化を体系化した最新サーベイ |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [VISTA](papers/2604.02217-vista) | バックプロパゲ不要のトークン重要度可視化、3行列で寄与分解、OSS |
| [MoE Expert Interpretability](papers/2604.02178-moe-expert-interpretability) | MoEはexpert単位で単義性が高いことを示し、解釈手法を提供 |
| [Stability Steering](papers/2604.02113-stability-steering) | 推論ステアリングの不安定境界を除去しMATH-500で+5.0向上 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [SKILL0](papers/2604.02268-skill0) | スキル文書を内在化するIn-Context RL、ゼロショット化を実現 |
| [DDCD](papers/2604.02250-ddcd) | 拡散デノイズ目的で因果DAG学習を安定化、k-hop制約で高速化 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [SPAR](papers/2604.02252-spar) | 単発Any-Resolution ViTで高解像度セグ、+10.5 mIoU、GitHub |
| [UAV-Track VLA](papers/2604.02241-uav-track-vla) | UAV追跡の89万フレームベンチ＋VLA改良、実時間性能向上 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [CORAL](papers/2604.01658-coral) | 自律マルチエージェント進化でSOTA、改善速度3–10倍 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [UniDriveVLA](papers/2604.02190-unidrivevla) | 認識/推論/計画をMoTで分離し自動運転VLAでSOTA |

---

## 2026-03-28 注目論文：WWW 2026 MCLMR因果推薦＆CVPR 2026 DMW個人化自動運転＆KlingAI ShotStreamリアルタイム動画＆S2D2 拡散LLM 4.7x高速化＆WriteBack-RAGで知識ベース学習

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [MCLMR](papers/2603.25126-mclmr) | **WWW 2026採択**、因果グラフ+MoEでマルチ行動推薦、GitHub公開 |
| [AuthorityBench](papers/2603.25092-authoritybench) | RAGの情報**権威性認識**を評価するベンチマーク、権威フィルタリングで精度向上、ACL 2026投稿 |
| [ColBERT-Att](papers/2603.25248-colbert-att) | Late Interaction＋アテンション統合、MS-MARCO/BEIR/LoTTEでrecall改善 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [S2D2](papers/2603.25702-s2d2) | 拡散LLMの**Training-free自己投機デコーディング**、最大4.7x高速化、GitHub公開 |
| [LLM Self-Improvement Survey](papers/2603.25681-llm-self-improvement) | LLM自己改善の**統一フレームワーク**、4プロセス+自律評価層でライフサイクル整理 |
| [NLAH](papers/2603.25723-nlah) | エージェントハーネスを**自然言語で記述・実行**、under review |
| [Narrative Coherence](papers/2603.25537-narrative-coherence) | VLMと人間の物語一貫性を比較、系統的な差異を発見、GitHub公開 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [Neural Scaling for Weather](papers/2603.25687-neural-scaling-weather) | **ICLR FM4Sci Workshop**、気象予測のスケーリング則、IsoFLOP曲線で計算最適化 |
| [On-Policy Distillation Fixes](papers/2603.25562-on-policy-distillation) | OPDの3つの失敗モードを特定、truncated reverse-KLで改善 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [ShotStream](papers/2603.25746-shotstream) | **KlingAI Research**、ストリーミング動画生成で**16 FPSリアルタイム**、GitHub公開 |
| [LGTM](papers/2603.25745-lgtm) | **4K Gaussian Splatting**をフィードフォワードで実現、少プリミティブで高品質 |
| [MuRF](papers/2603.25744-murf) | Vision Foundation Modelの**マルチ解像度融合**、DINOv2/SigLIP2で有効、訓練不要 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [WriteBack-RAG](papers/2603.25737-writeback-rag) | 知識ベースを**学習可能コンポーネント**化、蒸留で+2.14%精度向上、任意のRAGに適用可 |
| [WildASR](papers/2603.25727-wildasr) | 4言語ASRベンチマーク、環境劣化・人口統計・言語多様性で評価、**幻覚リスク**を指摘 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [Drive My Way](papers/2603.25740-drive-my-way) | **CVPR 2026**、個人の運転習慣に適応するVLA、ユーザー埋め込み＋言語指示 |
| [SoftMimicGen](papers/2603.25725-softmimicgen) | 変形可能物体操作のデータ自動生成、4ロボット形態（単腕・双腕・ヒューマノイド・手術）対応 |

---

## 2026-03-27 注目論文：OneSearch-V2産業生成検索＆Claudini自律攻撃発見＆MARCHマルチエージェントRAG検証＆PP-OCRv5 5Mで巨大VLM超え＆AI-Supervisor研究自動化

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [OneSearch-V2](papers/2603.24422) | **産業規模デプロイ**、生成検索フレームワーク、潜在推論+自己蒸留で複雑クエリ対応 |
| [RAG Policy QA](papers/2603.24580) | **検索改善≠回答改善**、AIガバナンスドメインでRAGの限界を実証 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [MARCH](papers/2603.24579) | **マルチエージェント強化学習**でRAGハルシネーション検証、確認バイアス問題を解決 |
| [Self-Distillation Degradation](papers/2603.24472) | Self-distillationが推論能力を**劣化させる**原因を特定、epistemic verbalの抑制 |
| [RAG Policy QA](papers/2603.24580) | ColBERTベースRAGの**ドメイン特化評価**、法的言語の課題を分析 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [Claudini](papers/2603.24511) | **Claude Codeでautoresearch**、30+手法を超える敵対的攻撃アルゴリズムを自律発見 |
| [UI-Voyager](papers/2603.24533) | 失敗から学ぶGUIエージェント、**RFT**でデータ・モデル共進化 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [PP-OCRv5](papers/2603.24373) | **5Mパラメータ**で十億級VLM超え、軽量OCRの極致 |
| [LensWalk](papers/2603.24558) | **エージェント型動画理解**、推論進化に応じた能動的証拠収集 |
| [OmniWeaving](papers/2603.24458) | 統一動画生成モデル、**自由形式構成+推論駆動** |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [AI-Supervisor](papers/2603.24402) | **AutoProf**、持続的研究世界モデルでAI研究監督を自動化 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [Chameleon](papers/2603.24576) | **エピソード記憶**で長horizonロボット操作、細粒度知覚キューを保持 |
| [3D-Mix for VLA](papers/2603.24393) | VLAモデルに**3D情報統合**、プラグアンドプレイモジュール |

---

## 2026-03-26 注目論文：KARMA Taobao本番デプロイLLM検索＆VISOR CVPR採択視覚効率化＆ReVal Off-Policy RL＆VTAM触覚ロボ＆Bilevel Autoresearch自己最適化

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [KARMA](papers/2603.22779) | **Taobao本番デプロイ**、LLMのKnowledge-Action Gap解決、+0.5% Item Click |
| [GEM-Rec](papers/2603.22231) | TIGER拡張、**広告入札を生成推薦に統合**、Allocation Monotonicity保証 |
| [AgenticRec](papers/2603.21613) | ランキング指向推薦エージェント、**List-Wise GRPO**で軌跡全体を最適化 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [ReVal](papers/2603.23355) | **Off-Policy Value-Based RL** for LLM、GRPOより高速収束、AIME24+2.7% |
| [SortedRL](papers/2603.23414) | LLM向けRL高速化、**長さ認識スケジューリング**でbubble ratio 50%削減 |
| [SpecEyes](papers/2603.23483) | エージェント型MLLM**投機的高速化**、1.1-3.35x speedup、コード公開 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [ReVal](papers/2603.23355) | **Bellman-updateベース**価値学習、replay bufferでサンプル効率化 |
| [SortedRL](papers/2603.23414) | rolloutボトルネック解決、**同一データ量で+3.9%〜+18.4%性能向上** |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [VISOR](papers/2603.23495) | **CVPR 2026採択**、視覚トークン削減せず**インタラクションのスパース化**で効率化 |
| [OccAny](papers/2603.23502) | **CVPR 2026採択**、制約なし都市3D占有予測、コード公開 |
| [UniGRPO](papers/2603.23500) | 推論駆動型画像生成、テキスト+画像の**統一RLフレームワーク** |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [Bilevel Autoresearch](papers/2603.23420) | **meta-autoresearch**、外側ループが内側を最適化、5x改善 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [VTAM](papers/2603.23481) | **Video-Tactile-Action Model**、触覚統合で接触リッチ操作90%成功率 |
| [ABot-PhysWorld](papers/2603.23376) | 14B DiT、**物理整合性ワールドモデル**、Veo 3.1/Sora v2 Pro超え |

---

## 2026-03-25 注目論文：GEM-Rec広告統合生成推薦＆DoRA高ランク適応メモリ効率化＆UniDex 50K軌跡8手形態＆UNITE LDM統一学習＆ThinkJEPA V-JEPA2+VLM＆MARCUS心臓診断マルチモーダル

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [GEM-Rec](papers/2603.22231) | TIGER拡張、**広告入札を生成推薦に統合**、オーガニック＆広告の二重市場を単一モデルで処理 |
| [PreferRec](papers/2603.22073) | 多目的リランキング、**パレート最適選好**を意図レベルで学習・転移 |
| [LSR for Code](papers/2603.22008) | コード検索への**疎検索適用**の課題分析、サブワード断片化・意味ギャップを系統的に調査 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [TiCo](papers/2603.22267) | 音声対話モデルの**時間制御**post-training、「30秒以内で答えて」に対応 |
| [MemDLM](papers/2603.22241) | 拡散言語モデルの**訓練-推論ギャップ解消**、二層最適化でノイズ除去軌跡を訓練に埋め込み |
| [Gumbel Distillation](papers/2603.22216) | 並列テキスト生成の蒸留、**Gumbel-Maxトリック**で同時分布を学習 |
| [AR vs. MDLM](papers/2603.22075) | 自己回帰vsマスク拡散LMの**制御実験**、同一条件（50Mトークン/H100）で公平比較 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [Scaling DoRA](papers/2603.22276) | 高ランクDoRAの**メモリ問題解決**、512MB→大幅削減のfused kernels実装 |
| [Confidence-Based Decoding](papers/2603.22248) | 拡散LMデコーディングの**理論的保証**、信頼度ベース手法の効率を証明 |
| [Chimera](papers/2603.22206) | マルチエージェントLLMサービング、**異種モデル混在**でレイテンシ-性能トレードオフ最適化 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [WorldCache](papers/2603.22286) | ビデオワールドモデル高速化、**コンテンツ認識キャッシュ**でDiTの冗長計算削減 |
| [ThinkJEPA](papers/2603.22281) | **V-JEPA2 + VLM統合**、長期セマンティクス予測を推論で強化 |
| [UNITE](papers/2603.22283) | LDM**統一学習**、トークナイザーと拡散モデルをend-to-endで同時訓練 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [MARCUS](papers/2603.22179) | **ECG/心エコー/CMR統合**の循環器診断エージェント、マルチモーダル心臓検査解釈 |
| [GSEM](papers/2603.22096) | 臨床推論の**グラフベース自己進化メモリ**、経験の関係構造を明示的にモデル化 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [UniDex](papers/2603.22264) | 器用操作基盤スイート、**50K+軌跡・8手形態**、エゴセントリック人間動画から学習 |
| [DexDrummer](papers/2603.22263) | ドラム演奏で器用性テスト、**インハンド・接触リッチ・長期**の3課題を統合 |

---

## 2026-03-24 注目論文：Taobao AIGQ本番デプロイ＆JD.com GenFacet CTR+42%＆VideoSeek CVPR採択＆LumosX ICLR採択＆CRISP ICRA採択＆PIXAR CVPR Findings採択

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [AIGQ (Alibaba)](papers/2603.19710) | **Taobao本番デプロイ**、初のエンドツーエンド生成クエリ推薦、IL-SFT＆IL-GRPO |
| [GenFacet (JD.com)](papers/2603.19665) | **JD.com本番デプロイ**、生成ファセット検索、CTR**+42%**・UCVR**+2%** |
| [All-Mem](papers/2603.19595) | エージェント長期記憶、トポロジー進化でLOCOMO/LONGMEMEVAL改善 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [Semantic Token Clustering](papers/2603.20161) | **EACL 2026採択**、単一生成でLLM不確実性定量化、補助モデル不要 |
| [Measuring CoT Faithfulness](papers/2603.20172) | CoT忠実性は分類器依存、12モデル10K+トレースで系統的差異を実証 |
| [Breaking Capability Ceiling](papers/2603.19987) | LLM post-trainingの構造的限界、**マルコフ状態再導入**で突破 |
| [Dual Path Attribution](papers/2603.19742) | SwiGLU Transformer向け高効率アトリビューション、**O(1)時間複雑性** |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [SCRL](papers/2603.19880) | テスト時RLの負例擬似ラベリング、コンセンサス弱い場面でロバスト、**コード公開** |
| [Var-JEPA](papers/2603.20111) | JEPAの変分定式化、単一ELBO最適化、予測的・生成的SSLを橋渡し |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [VideoSeek](papers/2603.20185) | **CVPR 2026採択**、GPT-5ベース長時間ビデオエージェント、93%フレーム削減 |
| [LumosX](papers/2603.20192) | **ICLR 2026採択**、複数被写体パーソナライズド動画生成、**コード公開** |
| [PIXAR](papers/2603.20193) | **CVPR 2026 Findings採択**、VLM画像改ざん検出の新分類法・ベンチマーク |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [Dynamic Belief Graphs](papers/2603.20170) | Theory of Mind + LLM、動的信念グラフで災害避難行動予測 |
| [Transformer Plan Verification](papers/2603.19954) | C*-RASP導入、Transformerのプラン検証能力を理論的分析 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [CRISP](papers/2603.20164) | **ICRA 2026採択**、VLM「内なる批評家」でロボット社会的行動を自己改善 |
| [IndoorR2X](papers/2603.20182) | IoT+マルチロボット協調、LLM駆動タスク計画のベンチマーク（CMU） |

---

## 2026-03-22 注目論文：NVIDIA Nemotron-Cascade 2 IMO金メダル＆F2LLM-v2 MTEB 11部門1位＆SOL-ExecBench GPUカーネル最適化＆VEGA-3D ビデオ事前分布3D理解＆VLA内部メカニズム解明

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [Total Recall QA](papers/2603.18516) | TREC着想の深層リサーチエージェント評価、**完全想起型QAタスク**でデータ汚染対策 |
| [HypeMed](papers/2603.18459) | **TOIS採択**、ハイパーグラフで薬剤推薦、DDI削減と精度向上を両立 |
| [Negative Sampling Survey](papers/2603.18005) | **EACL Findings採択**、Dense IR負例サンプリング35論文統合サーベイ |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [Nemotron-Cascade 2 (NVIDIA)](papers/2603.19220) | 30B MoE/3B活性化で**IMO金メダル・IOI・ICPC世界決勝**レベル、モデル＆データ公開 |
| [F2LLM-v2](papers/2603.19223) | **MTEB 11ベンチマーク1位**、200言語対応、80M〜14Bの8サイズ展開、全コード公開 |
| [DaPT](papers/2603.19097) | **ICASSP 2026採択**、多言語マルチホップQAのデュアルパスRAG、MuSiQue EM**+18.3%** |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [SOL-ExecBench (NVIDIA)](papers/2603.19173) | **Blackwell GPU**向け235カーネル最適化問題、ハードウェア限界ベンチマーク |
| [Ranking Feedback Online Learning](papers/2603.19221) | 数値フィードバック不要のオンライン学習、**LLMルーティング**応用を実証 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [VEGA-3D](papers/2603.19235) | ビデオ拡散モデルの暗黙的3D事前分布活用、**コード公開**、空間推論・実体操作でSOTA |
| [Matryoshka Gaussian Splatting](papers/2603.19234) | 3DGSの**連続LoD**実現、フル解像度品質維持、アーキテクチャ変更不要 |
| [DriveTok](papers/2603.19219) | 自動運転向け3Dトークナイザー、マルチビュー統一表現、**コード公開** |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [OS-Themis](papers/2603.19191) | マルチエージェント批評家でGUI報酬設計、AndroidWorld RL**+10.3%**改善 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [VLA Mechanistic Study](papers/2603.19233) | **ICLR Workshop採択**、6モデル394K+エピソード分析、視覚経路の支配性を解明 |
| [OmniVTA](papers/2603.19201) | **21,000軌跡・86タスク**の大規模視覚触覚データセット、60Hzリフレキシブ制御 |

---

## 2026-03-21 注目論文：Spotify GLIDEポッドキャスト発見＆NVIDIA Nemotron-Cascade 2 IMO金メダル＆F2LLM-v2 MTEB 11部門1位＆CubiD/EffectErase CVPR採択＆OmniViTac大規模触覚データセット

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [GLIDE (Spotify)](papers/2603.17540) | **Spotify本番デプロイ**、Semantic IDベース生成推薦、非習慣的視聴**+5.4%**、新番組発見**+14.3%** |
| [NEO (Spotify)](papers/2603.17533) | 検索・推薦・推論を**単一LLM**で統合、1000万+アイテムでタスク特化ベースライン超え |
| [Interplay](papers/2603.18573) | **ECIR 2026採択**、参照不要シミュレーションで対話型推薦訓練データ生成 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [Nemotron-Cascade 2 (NVIDIA)](papers/2603.19220) | 30B MoE/3B活性化で**IMO金メダル・IOI・ICPC世界決勝**レベル、モデル＆データ公開 |
| [F2LLM-v2](papers/2603.19223) | **MTEB 11ベンチマーク1位**、200言語対応、80M〜14Bの8サイズ展開、全コード公開 |
| [DaPT](papers/2603.19097) | **ICASSP 2026採択**、多言語マルチホップQAのデュアルパスRAG、MuSiQue EM+18.3% |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [CubiD](papers/2603.19232) | **CVPR 2026採択**、初の高次元離散生成モデル、ImageNet-256でSOTA、コード公開 |
| [EffectErase](papers/2603.19224) | **CVPR 2026採択**、60Kビデオペアでオブジェクト＆エフェクト除去、相互学習 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [OS-Themis](papers/2603.19191) | マルチエージェント批評家でGUI報酬設計、AndroidWorld RL**+10.3%**改善 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [OmniViTac](papers/2603.19201) | **21,000軌跡・86タスク**の大規模視覚触覚データセット、60Hzリフレキシブ制御 |
| [FASTER](papers/2603.19199) | VLAリアルタイム化、Horizon-Aware Scheduleで反応10倍高速化、**卓球タスク実証** |

---

## 2026-03-20 注目論文：Spotify GLIDE本番デプロイ（新番組発見+14%）＆NEO統合検索推薦＆ARAM RAG拡散＆動機付け推論検出＆PIER海上ルーティング燃料浪費9分の1

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [GLIDE (Spotify)](papers/2026-03-20-glide-spotify-podcast) | **Spotify本番デプロイ**、数百万ユーザーA/Bテストで非習慣的視聴**+5.4%**、新番組発見**+14.3%** |
| [NEO (Spotify)](papers/2026-03-20-neo-unified-lm-search-rec) | 検索・推薦・推論を**単一言語ステアラブルモデル**で統合、1000万アイテム以上で検証 |
| [OPERA](papers/2026-03-20-opera-retrieval-pruning) | 検索モデル適応のデータ剪定、**NDCG+1.9%**を**50%未満の訓練時間**で達成 |
| [CRE-T1](papers/2026-03-20-cre-t1-reasoning-retrieval) | 対照学習超え**生成型検索**、GRPOで動的推論、BRIGHTで大型対照学習モデル超え |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [ARAM](papers/2026-03-20-aram-rag-diffusion) | 拡散言語モデル向けRAG、**SNRベース適応ガイダンス**で検索コンフリクト解決 |
| [MoE Knowledge Localization](papers/2026-03-20-moe-knowledge-localization) | 多言語不整合でMoE知識局在化、**20/6000エキスパート無効化で40%正答不能** |
| [NL2SQL Robustness](papers/2026-03-20-nl2sql-robustness) | GPT-5.2/Claude-Opus-4.6等評価、表面ノイズvs言語変動の脆弱性分析 |
| [Anonymous-by-Construction](papers/2026-03-20-anonymous-by-construction) | オンプレミスLLMでPII匿名化、**Presidio/Google DLP超え**、Q&Aエージェント対応 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [MHPO](papers/2026-03-20-mhpo-stable-rl) | GRPO安定化、**ハザード認識ポリシー最適化**でモード崩壊・ポリシー侵食を同時緩和 |
| [AAT](papers/2026-03-20-aat-continual-learning) | 構造的抽象化で継続学習、**リプレイバッファ完全不要**でER同等以上 |
| [Motivated Reasoning Detection](papers/2026-03-20-motivated-reasoning-detection) | LLMの動機付け推論を内部活性化から検出、**CoT生成前でも予測可能** |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [DesertFormer](papers/2026-03-20-desertformer-terrain-segmentation) | 砂漠地形セグメンテーション、DeepLabV3比**+24.2% mIoU**、GitHub公開 |
| [Pixel Counterfactual](papers/2026-03-20-pixel-counterfactual-medical) | **ISBI-2026口頭**、反事実×密対照学習で医療画像**~94% DSC** |
| [Flash Fingerprint](papers/2026-03-20-fingerprint-spoof-flash) | **IWBF 2026**、フラッシュペア撮像で非接触指紋スプーフ検出 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [PIER](papers/2026-03-20-pier-maritime-routing) | 物理情報オフラインRLで海上ルーティング、壊滅的燃料浪費を**9分の1に削減** |
| [Cascade-Aware Routing](papers/2026-03-20-cascade-multiagent-routing) | マルチエージェント幾何学認識、**133パラメータで勝率+36.8pp** |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [KineVLA](papers/2026-03-20-kinevla-robot-manipulation) | 運動学認識VLA、方向・軌跡・姿勢を言語に密エンコード、LIBERO+実機検証 |
| [EVA](papers/2026-03-20-eva-video-world-model) | ビデオワールドモデルの実行可能性ギャップをRL解消、逆動力学報酬で制約適合 |

---

## 2026-03-19 注目論文：CVPR 2026 3本（EchoSafe安全性・ATV-Pruning LVLM剪定・Parallel-ICL）＆MiroThinker検証型エージェント＆Golden Ticket実機60%改善

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [RecBundle](papers/2026-03-19-recbundle-geometric-recsys) | ファイバーバンドル理論で推薦システムを幾何学的に分析、情報繭問題への新アプローチ |
| [Answer Bubbles](papers/2026-03-19-answer-bubbles-search) | GPT vs Google 11K実クエリ比較、生成検索の**ソースバイアス**とヘッジング60%減を定量化 |
| [CRAG Open-Source](papers/2026-03-19-crag-opensource-reproduction) | CRAGの完全オープンソース再現＋SHAP説明可能性分析、**固有表現アライメント依存**を発見 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [MiroThinker](papers/2026-03-19-mirothinker-research-agent) | 検証機構統合のリサーチエージェント、ローカル/グローバル検証で信頼性確保、**オープンソース公開** |
| [SRLM](papers/2026-03-19-srlm-long-context) | 自己反省型プログラム探索で長文脈処理、RLMを**最大+22%**改善 |
| [Efficient Reasoning on Edge](papers/2026-03-19-efficient-reasoning-edge) | **Qualcomm AI Research**、LoRA＋RL バジェット強制でモバイル推論実現、実機デモ公開 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [EHR Tokenization](papers/2026-03-19-ehr-tokenization) | 医療EHR基盤モデルのトークン化調査、Joint encoding＋Positional時間で**73/74タスク勝利・39.5%FLOPs削減** |
| [CGC](papers/2026-03-19-capability-guided-compression) | SAE由来capability densityでLLM圧縮、既存指標と**直交する新信号**を発見 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [EchoSafe](papers/2026-03-19-echosafe-mllm-safety) | **CVPR 2026**、自己反省メモリでMLLMのコンテキスト安全性を進化的に強化 |
| [ATV-Pruning](papers/2026-03-19-atv-pruning-lvlm) | **CVPR 2026**、テキスト・視覚の非対称性を活用したLVLM剪定、コード公開 |
| [Parallel-ICL](papers/2026-03-19-parallel-icl-vlm) | **CVPR 2026 Findings**、デモを並列処理してMM-ICL高速化、精度維持でレイテンシ改善 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [Memory Store Routing](papers/2026-03-19-cost-sensitive-memory-routing) | **ICLR 2026 Workshop**、メモリストア選択的ルーティングでコスト削減＋精度向上 |
| [AsgardBench](papers/2026-03-19-asgard-bench-vlm) | インタラクティブプランニング評価ベンチ、VLMの視覚グラウンディング弱点を特定 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [Golden Ticket](papers/2026-03-19-golden-ticket-diffusion) | 単一ノイズベクトル最適化で拡散ポリシー改善、実機で**60%改善**、訓練不要 |
| [SimDist](papers/2026-03-19-simdist-sim2real) | シミュレーション蒸留でワールドモデル事前学習、短期システム同定で高速Sim2Real適応 |

---

## 2026-03-18 注目論文：MoDA 深層注意＆Code-A1 敵対共進化＆DOMINO 動的マニピュレーション＆OpenSeeker 検索エージェント完全公開

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [Graph-RAG Reasoning Bottleneck](papers/2026-03-18-graphrag-reasoning-bottleneck) | 検索は当たるが推論が落ちる問題を定量化、SPARQL CoT＋グラフ圧縮で**最大+14pp**、小型モデルで大型超え |
| [C2RAG](papers/2026-03-18-c2rag-robust-graphrag) | KGノイズ/欠損に強い制約チェック型GraphRAG、EM+3.4/F1+3.9 |
| [FinTRACE](papers/2026-03-18-fintrace-transaction-retrieval) | 金融トランザクション検索ファーストでゼロショットMCC **0.19→0.38** |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [MoDA](papers/2026-03-18-moda-attention) | 深層LLMの信号劣化を深度アテンションで解決、FlashAttention級効率、GitHub公開 |
| [Code-A1](papers/2026-03-18-code-a1-adversarial) | Code/Test LLMの敵対共進化、自己共謀を回避、GitHub公開 |
| [Moral Indifference](papers/2026-03-18-moral-indifference-llm) | LLMの道徳的無関心を表現レベルで修正、Flamesで**75% win** |
| [OrgForge](papers/2026-03-18-orgforge-multiagent) | RAG評価用の一貫性付き合成企業コーパス、マルチエージェント生成 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [HorizonMath](papers/2026-03-18-horizonmath-benchmark) | 未解決問題100+の数学発見ベンチ、GPT 5.4 Proが既知最良を改善候補 |
| [SmartSearch](papers/2026-03-18-smartsearch-memory) | 構造化不要、ランキング重視で会話メモリ検索SOTA |
| [xLSTM Distillation](papers/2026-03-18-xlstm-distillation) | Transformer→xLSTM蒸留で性能維持/超え、効率化に有望 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [DOMINO](papers/2026-03-18-domino-dynamic-manipulation) | 動的マニピュレーション用110K軌跡データ＋PUMA、成功率+6.3%、GitHub公開 |
| [DeepVision-VLA](papers/2026-03-18-deepvision-vla) | VLAの深層視覚感度低下を補正、実機+7.5% |
| [GlyphPrinter](papers/2026-03-18-glyphprinter-cvpr2026) | **CVPR 2026**、領域DPOでグリフ精度改善 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [OpenSeeker](papers/2026-03-18-openseeker-search-agent) | 検索エージェントのモデル＋データ完全公開、11.7KでSOTA級 |
| [Counterfactual Metrics](papers/2026-03-18-counterfactual-metrics-xai2026) | **XAI 2026**、反事実指標が人間評価と弱相関を実証 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [PRIMO R1](papers/2026-03-18-primo-r1-process-reasoning) | 7Bで72B級を超えるプロセス監視、RoboFail 67% | 
| [EAAE](papers/2026-03-18-eaae-uav-exploration) | UAV探索でエネルギー最適化、消費削減 |

---

## 2026-03-17 注目論文：ICLR2026 ReBalance推論バランス化＆NanoVDR 32x蒸留＆EISAM LRS ロングテール解決＆TERMINATOR CoT 55%削減＆VLA CoT脆弱性発見

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [NanoVDR](papers/2026-03-17-nanovdr-distillation) | 2B VLM→70M Text Encoder蒸留、**32xパラメータ削減**・50x CPUレイテンシ削減、教師品質95.1%維持 |
| [EISAM](papers/2026-03-17-eisam-longtail-lrs) | LLM推薦のロングテール問題初体系化、**アイテム単位SAM**で理論保証付き改善 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [ReBalance](papers/2026-03-17-rebalance-iclr2026) | **ICLR 2026**: 推論のoverthinking/underthinking解決、信頼度ベース動的制御、**訓練不要** |
| [TERMINATOR](papers/2026-03-17-terminator-cot-early-exit) | CoT最適早期終了学習、**14-55%トークン削減**でSOTA、AIME2025/MATH-500対応 |
| [RL for Diffusion LLMs](papers/2026-03-17-rl-diffusion-llm) | 拡散言語モデルRL、エントロピーガイドステップ選択、コーディング・論理推論でSOTA |
| [Aligning from Interactions](papers/2026-03-17-aligning-user-interactions) | WildChatから自己蒸留、明示的フィードバック不要でアラインメント・パーソナライズ |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [NeuroLoRA](papers/2026-03-17-neurolora-moe-peft) | 神経調節に着想のMoE-LoRA、コンテキスト依存ルーティング、継続学習能力向上 |
| [TERMINATOR](papers/2026-03-17-terminator-cot-early-exit) | LRM早期終了戦略、最適推論長データセット構築、4ベンチマークでSOTA |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [VQQA](papers/2026-03-17-vqqa-video-quality) | マルチエージェント動画品質評価、VLM critiquesでT2V-CompBench **+11.57%**、I2V対応 |
| [Show Don't Tell](papers/2026-03-17-show-dont-tell-robot) | 人間デモから新規物体検出学習、言語プロンプト不要、**実ロボット検証** |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [ReBalance](papers/2026-03-17-rebalance-iclr2026) | **ICLR 2026**: 0.5B〜32Bモデル×9ベンチ、plug-and-playで推論効率化 |
| [Structured Distillation](papers/2026-03-17-structured-distillation-agent-memory) | エージェントメモリ**11x圧縮**、検索品質96%維持、214K評価ペア、GitHub公開 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [VLA CoT Vulnerabilities](papers/2026-03-17-vla-cot-vulnerabilities) | **VLA推論トレースの脆弱性発見**: オブジェクト名置換で**-45pp**、入力検証では防げない新脅威 |
| [Q-DIG](papers/2026-03-17-qdig-vla-redteaming) | VLAのQuality Diversity red-teaming、多様な失敗モード発見、ファインチューニングで改善 |

---

## 2026-03-16 注目論文：CVPR2026 RC-NF/Shape-of-You＆OneRec-V2 FP8で49%レイテンシ削減＆OpenSanctions LLMマッチング98.95% F1＆MDER-DR RAG 66%改善＆Stanford PhD Robot Reliability＆会話税でLLM診断劣化発見

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [OpenSanctions LLM](papers/2026-03-16-opensanctions-llm) | 755Kペア国際制裁エンティティマッチング、**GPT-4o 98.95% F1**、GitHub公開 |
| [OneRec-V2 FP8](papers/2026-03-16-onerec-v2-fp8) | 📊 **実運用A/Bテスト**: FP8量子化で推薦**49%レイテンシ削減**・92%スループット向上 |
| [FedShare](papers/2026-03-16-fedshare) | 連合推薦＋アンラーニング、プライバシー制御とパフォーマンスの柔軟なトレードオフ |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [MDER-DR](papers/2026-03-16-mder-dr) | マルチホップRAG、KGベースQAで標準RAG比**66%改善**、GitHub公開 |
| [REOPOLD](papers/2026-03-16-reopold) | オンポリシー蒸留緩和、7Bが32B教師と同等視覚推論（**3.32x高速**） |
| [ARACH](papers/2026-03-16-arach) | **学習不要**推論時プラグイン、アテンション再配分でLLM強化 |
| [Conversation Tax](papers/2026-03-16-conversation-tax) | マルチターン会話で診断推論劣化、17 LLM・3臨床データで実証 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [Continual VLA RL](papers/2026-03-16-continual-vla-rl) | **UT Austin**: LoRA+Sequential FTでVLAの継続学習が意外とうまくいく、GitHub公開 |
| [HAPO](papers/2026-03-16-hapo) | スパース報酬でのRLVR、後知恵アンカーで安定化、教師信号を自然にアニーリング |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [RC-NF](papers/2026-03-16-rc-nf) | **CVPR 2026**: VLA異常検出、pi0にプラグ可能、**100ms未満**で介入 |
| [Shape-of-You](papers/2026-03-16-shape-of-you) | **CVPR 2026**: Fused Gromov-Wassersteinでセマンティック対応、SPair-71k SOTA |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [FinRule-Bench](papers/2026-03-16-finrule-bench) | 財務諸表ルールベース推論ベンチ、マルチ違反診断で急激に性能低下 |
| [GPT4o-Receipt](papers/2026-03-16-gpt4o-receipt) | AI生成領収書検出、人間は視覚アーティファクト得意だが算術エラーはLLMが上 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [Stanford Robot Reliability](papers/2026-03-16-stanford-robot-reliability) | **Stanford PhD**: 展開時信頼性の3メカニズム、ランタイム監視・解釈可能性・長期タスク |
| [RoboClaw](papers/2026-03-16-roboclaw) | VLMエージェント的フレームワーク、長期タスク**25%改善**・人間労力**53.7%削減** |

---

## 2026-03-15 注目論文：MDER-DRでマルチホップRAG 66%改善＆ACL2026 QAQで合成データ品質フィルタリング＆CVPR2026 BiGain/EVATok/AutoGaze＆MIT Neural Thickets＆Stanford HandelBotピアノ演奏ロボ

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [MDER-DR](papers/2026-03-15-mder-dr) | マルチホップRAG、KGベースQAで標準RAG比**66%改善**、GitHub公開 |
| [RAGPerf](papers/2026-03-15-ragperf) | **RAGベンチマーク**: embedding/indexing/retrieval/reranking/generation全コンポーネント対応、GitHub公開 |
| [TriRec](papers/2026-03-15-trirec) | LLMエージェント三者（ユーザー・アイテム・プラットフォーム）推薦、公平性と精度の両立 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [QAQ](papers/2026-03-15-qaq) | **ACL 2026投稿中**: 双方向セマンティック一貫性で合成コードデータのノイズ・幻覚検出 |
| [Linking Perception](papers/2026-03-15-linking-perception) | **CVPR 2026**: MLLMの信頼度キャリブレーション、CDRLで「知らないときに知らない」を学習 |
| [TopoBench](papers/2026-03-15-topobench) | **ICLR 2026 WS**: トポロジカル推論ベンチ、フロンティアモデルでも困難問題**25%未満** |
| [IndexCache](papers/2026-03-15-indexcache) | DeepSeek Sparse Attentionの層間インデックス再利用で効率化 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [BiGain](papers/2026-03-15-bigain) | **CVPR 2026**: 周波数分離でトークン圧縮、生成品質と分類精度の両立、GitHub公開 |
| [Spatial-TTT](papers/2026-03-15-spatial-ttt) | Test-Time Trainingで無制限長動画からストリーミング空間知能 |
| [Neural Thickets](papers/2026-03-15-neural-thickets) | **MIT (Phillip Isola)**: 大規模事前学習モデルでは重み近傍にタスク専門家が密集 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [EVATok](papers/2026-03-15-evatok) | **CVPR 2026**: 適応長動画トークン化、コンテンツ複雑度に応じたトークン割当 |
| [AutoGaze](papers/2026-03-15-autogaze) | **CVPR 2026**: 自己回帰的パッチ選択で長時間高解像度動画理解を高速化 |
| [GRADE](papers/2026-03-15-grade) | 学術分野の専門知識を要する画像編集ベンチ、10ドメイン520サンプル、HuggingFace公開 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [Neural Thickets](papers/2026-03-15-neural-thickets) | **MIT**: 事前学習の新解釈—タスク専門家のランダム探索可能性とモデルマージの理論的裏付け |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [Ψ₀ Psi-Zero](papers/2026-03-15-psi-zero) | **オープン基盤モデル**: ヒューマノイド全身ロコマニピュレーション、人間-ロボ動作の分離学習 |
| [SaPaVe](papers/2026-03-15-sapave) | **CVPR 2026**: VLAモデルでのアクティブ知覚と操作の統合、カメラ・操作アクション分離 |
| [HandelBot](papers/2026-03-15-handelbot) | **Stanford**: 二腕ロボットによる**ミリ精度ピアノ演奏**、高速sim-to-real適応 |

---

## 2026-03-13 注目論文：OneRec-V2でFP8量子化推薦＆IndexCacheでDeepSeek Sparse Attention高速化＆CVPR2026 EVATok/AutoGaze動画理解＆Ψ₀ヒューマノイド基盤モデル

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [OneRec-V2 FP8](papers/2026-03-13-onerec-v2-fp8-quantization) | 📊 **実運用A/B test**: FP8量子化で推薦システム**49%レイテンシ削減**・92%スループット向上 |
| [OpenSanctions Pairs](papers/2026-03-13-opensanctions-pairs-entity-matching) | 755K対エンティティマッチング、GPT-4o **98.95% F1**、GitHub公開 |
| [FedShare](papers/2026-03-13-fedshare-federated-recommendation-unlearning) | 連合推薦＋unlearning対応、パーソナライズされたデータ共有とコントラスティブ忘却 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [IndexCache](papers/2026-03-13-indexcache-sparse-attention-acceleration) | **Tsinghua/GLM-5**: DeepSeek Sparse Attention**75%計算削減**、1.82x prefill高速化 |
| [BTZSC](papers/2026-03-13-btzsc-zero-shot-classification-benchmark) | **ICLR 2026**: ゼロショット分類ベンチ、Qwen3-Reranker-8Bが**F1=0.72で新SOTA** |
| [SciMDR](papers/2026-03-13-scimdr-scientific-multimodal-reasoning) | 科学論文マルチモーダル推論、**300K QAペア**+明示的推論チェーン |
| [MADQA](papers/2026-03-13-madqa-document-agentic-qa) | **HuggingFace共著**: エージェントの戦略的推論 vs 試行錯誤を評価、2250問800PDF |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [AI Agent Security](papers/2026-03-13-ai-agent-security-perplexity) | **Perplexity**: エージェントセキュリティ包括分析、間接プロンプトインジェクション等 |
| [EBFT](papers/2026-03-13-ebft-energy-based-fine-tuning) | シーケンスレベル特徴マッチングで微調整、RLVRと同等・SFT超え |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [EVATok](papers/2026-03-13-evatok-video-adaptive-tokenization) | **CVPR 2026**: 適応長動画トークン化、**24.4%トークン削減**でUCF-101 SOTA |
| [AutoGaze](papers/2026-03-13-autogaze-video-understanding) | **CVPR 2026 / NVIDIA/Berkeley**: 視覚トークン**4-100x削減**、1Kフレーム4K動画対応 |
| [VST](papers/2026-03-13-vst-video-streaming-thinking) | Thinking-while-watching、Video-R1比**15.7x高速**でStreamingBench 79.5% |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [Reasoning LLM Judges](papers/2026-03-13-reasoning-llm-judges) | 推論審判で訓練したポリシーが**敵対的出力**で他審判を欺く現象を発見 |
| [TopoBench](papers/2026-03-13-topobench-topological-reasoning) | **ICLR 2026 WS**: トポロジカル推論、フロンティアモデルでも困難インスタンス**25%未満** |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [Ψ₀ Psi-Zero](papers/2026-03-13-psi-zero-humanoid-foundation-model) | **Stanford / オープンソース**: 800h人間動画+30h実ロボで**+40%成功率**、基盤モデル公開 |
| [HumDex](papers/2026-03-13-humdex-humanoid-teleoperation) | IMUテレオペ+学習リターゲティング、**完全再現可能**GitHub公開 |

---

## 2026-03-12 注目論文：TriRecで三者エージェント推薦＆GLM-OCR 0.9BでOCR産業向け＆ICLR2026 LiTo表面ライトフィールド＆CVPR2026色忠実度＆ICRA2026拡散ポリシー改善

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [TriRec](papers/2026-03-12-trirec-tri-party-llm-agent-recommendation) | ユーザー・アイテム・プラットフォーム**三者最適化**の初LLMエージェント推薦、GitHub公開 |
| [Structured Linked Data RAG](papers/2026-03-12-structured-linked-data-rag) | Schema.org + Google ADKでRAG精度**+29.6%**、llms.txt形式エンティティページ |
| [Stage-wise News Rec](papers/2026-03-12-stage-wise-news-recommendation) | **WWW 2026**: ユーザー興味の段階的進化をLSTM+Self-attentionでモデル化 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [GLM-OCR](papers/2026-03-12-glm-ocr) | **Tsinghua (Jie Tang)**: 0.9B OCRモデル、Multi-Token Predictionでスループット大幅改善 |
| [LLM2Vec-Gen](papers/2026-03-12-llm2vec-gen) | **MTEB最先端**: LLM応答を表現する埋め込み、有害コンテンツ**43%削減**、解釈可能 |
| [Evaluation Illusion](papers/2026-03-12-evaluation-illusion-llm-judge) | 105K評価インスタンスでLLM-as-a-Judgeの**表面ヒューリスティック依存**を発見、RLAIF示唆 |
| [Multilingual Reasoning Gym](papers/2026-03-12-multilingual-reasoning-gym) | **14言語**で検証可能推論問題を手続き生成、RLVR対応、実装公開 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [LLVQ](papers/2026-03-12-llvq-leech-lattice-quantization) | **Leech格子**でLLM量子化、Quip#/QTIP/PVQ超えの**最先端**、コードブック不要 |
| [RAD](papers/2026-03-12-rad-safe-rlhf-stochastic-dominance) | **確率優位**でSafe RLHF、テールリスク制御、Spectral Risk Measures普遍保証 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [LiTo](papers/2026-03-12-lito-surface-light-field) | **ICLR 2026 / Apple**: 表面ライトフィールドトークン化、ジオメトリ+視点依存外観を統一3D表現 |
| [Color Fidelity](papers/2026-03-12-color-fidelity-t2i) | **CVPR 2026**: T2Iの「鮮やかすぎ」問題、130万画像データセット+訓練不要改善、GitHub公開 |
| [V2M-Zero](papers/2026-03-12-v2m-zero-video-to-music) | **ゼロペア**動画→音楽生成、時間同期**+21-52%**、モダリティ内特徴で達成 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [DxEvolve](papers/2026-03-12-dxevolve-self-evolving-diagnosis) | 自己進化型診断エージェント、MIMIC-CDM **90.4%**（臨床医88.8%）、**Ji-Rong Wen**共著 |
| [Trajectory Memory](papers/2026-03-12-trajectory-memory-self-improving-agent) | 軌跡から行動可能な学習を抽出、AppWorld複雑タスクで**+28.5pp**（149%相対改善） |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [PPGuide](papers/2026-03-12-ppguide-diffusion-policy) | **ICRA 2026**: 拡散ポリシーを推論時にパフォーマンス予測器で誘導、MILで自己ラベリング |
| [CCGE](papers/2026-03-12-ccge-dexterous-manipulation) | **接触カバレッジ探索**で汎用巧緻操作、両手/インハンドで検証、**実ロボット転移成功** |

---

## 2026-03-11 注目論文：RecThinkerでエージェント推薦＆Google「推論が知識想起を解放」＆MoE推論ペナルティ定量化＆Meissa4B医療エージェント＆PlayWorldでロボット自己遊び学習

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [RecThinker](papers/2026-03-11-recthinker-agentic-tool-reasoning-recommendation) | **Analyze-Plan-Act**パラダイムで推薦エージェント、ツール拡張で情報ギャップを能動的に埋める |
| [TREC 2025 RAG Track](papers/2026-03-11-trec-2025-rag-track-overview) | **TREC公式**: マルチセンテンスナラティブクエリでRAG評価、MS MARCO V2.1コーパス、150+提出 |
| [RF-Mem](papers/2026-03-11-rf-mem-recollection-familiarity-memory-retrieval) | 認知科学の**二重プロセス**をLLMパーソナライズに応用、Familiarity/Recollection適応検索 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [Thinking to Recall](papers/2026-03-11-thinking-to-recall-reasoning-parametric-knowledge) | **Google**: 推論がパラメトリック知識想起を解放、計算バッファ＋事実プライミングの2メカニズム |
| [Model Merging Survey](papers/2026-03-11-model-merging-llm-survey) | LLM時代のモデルマージ包括的サーベイ、**FUSEタクソノミー**で設計空間を体系化 |
| [ALARM](papers/2026-03-11-alarm-audio-language-alignment-reasoning) | **4Bで最高性能**: Self-rephrasingでRLMと互換、MMAU-speech/MMSU最高 |
| [Chow-Liu Chain-of-Agents](papers/2026-03-11-chow-liu-ordering-chain-of-agents) | **Microsoft**: 情報理論でチャンク順序最適化、長文コンテキストの情報損失削減 |
| [ConFu](papers/2026-03-11-confu-speculative-sampling-future) | 将来予測でスペキュラティブデコーディング改善、EAGLE-3比**8-11%向上** |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [HCAPO](papers/2026-03-11-hcapo-hindsight-credit-assignment-llm-agents) | **ByteDance共著**: 後知恵クレジット割り当てでLLMエージェントRL、WebShop+7.7%/ALFWorld+13.8% |
| [Latent-DARM](papers/2026-03-11-latent-darm-discrete-diffusion-autoregressive) | DDLMとARMを潜在空間で橋渡し、AIME2024で0%→14%、トークン**2.2%で**最先端に迫る |
| [qs Inequality](papers/2026-03-11-qs-inequality-moe-inference-penalty) | MoE推論の**二重ペナルティ**定量化、DeepSeek-V3で密モデルが4.5xスループット優位 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [Granulon](papers/2026-03-11-granulon-pixel-level-mllm-encoders) | DINOv3に適応的粒度拡張、精度**30%↑**・ハルシネーション**20%↓** |
| [VisionCreator-R1](papers/2026-03-11-visioncreator-r1-reflection-visual-generation) | リフレクション付き視覚生成エージェント、RPCOでGemini2.5Pro超え |
| [RubiCap](papers/2026-03-11-rubicap-rubric-guided-rl-captioning) | ルーブリック駆動RLで密キャプション、**CapArena最高勝率**、人間専門家超え |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [Meissa](papers/2026-03-11-meissa-medical-agentic-intelligence) | **4Bパラメータ**医療MM-LLMエージェント、オフラインで22xレイテンシ削減、GitHub公開 |
| [Social-R1](papers/2026-03-11-social-r1-human-like-social-reasoning) | **Microsoft Research Asia**: ToMBench-Hardで社会的推論、4Bで大規模モデル超え |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [Scale-Plan](papers/2026-03-11-scale-plan-multi-robot-task-planning) | **Honda**: LLM+PDDLハイブリッドでマルチロボット計画、MAT2-THORベンチマーク導入 |
| [PlayWorld](papers/2026-03-11-playworld-robot-world-models-autonomous-play) | **Princeton**: ロボット自己遊びからワールドモデル学習、実世界で**65%成功率向上** |

---

## 2026-03-10 注目論文：ICLR2026教師なしRLVR＆VRecで検証可能LLM推薦＆CVPR2026協調3D会話合成＆CoRL2025 VFMでロングテール3D検出＆RecPilotで推薦がレポート化

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [VRec](papers/2026-03-10-vrec-verifiable-reasoning-llm-recommendation) | LLM推薦の**reason-verify-recommend**パラダイム、検証器で推論劣化を防止、**GitHub公開** |
| [RecPilot](papers/2026-03-10-recpilot-deep-research-recommender) | 推薦を「リストからレポートへ」転換、マルチエージェントで**自律探索・統合** |
| [ERASE](papers/2026-03-10-erase-unlearning-benchmark-recsys) | 推薦のMachine Unlearning初の大規模ベンチマーク、**GDPR対応**、600GB以上アーティファクト公開 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [CODA](papers/2026-03-10-coda-difficulty-aware-compute-allocation) | 難易度認識コンピュート割り当て、簡単タスクで**60%+トークン削減**しつつ精度維持 |
| [SmartThinker](papers/2026-03-10-smartthinker-cot-length-calibration) | CoT長をプログレッシブにキャリブレート、**52.5%圧縮で精度向上**、AIME25で+16.6%、GitHub公開 |
| [SPD-RAG](papers/2026-03-10-spd-rag-subagent-per-document) | ドキュメント毎にサブエージェント配置、LOONGで**58.1達成**（通常RAG 33.0）、APIコスト38% |
| [UIS-Digger](papers/2026-03-10-uis-digger-unindexed-information-seeking) | **ICLR 2026**: 非インデックス情報検索、~30BモデルがO3/GPT-4.1超え、デュアルモードブラウジング |
| [EvoScientist](papers/2026-03-10-evoscientist-multi-agent-ai-scientist) | 永続メモリ+自己進化でAIサイエンティスト、過去失敗から学習、7つのSOTA超え |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [Unsupervised RLVR](papers/2026-03-10-unsupervised-rlvr-scaling-llm) | **ICLR 2026**: Webデータのみで教師なしRLVR、**AIME24で7%向上**、アノテーション不要 |
| [ACT](papers/2026-03-10-agentic-critical-training-llm-rl) | Agentic Critical Training、RLエージェントに**クリティカル分析**を訓練、テストタイム適応 |
| [PostTrainBench](papers/2026-03-10-posttrainbench-llm-post-training-automation) | ポストトレーニング自動化ベンチ、GPT-5.1で**24.6%のみ成功**、Opus 4.6は22.0% |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [Talk Together](papers/2026-03-10-talking-together-3d-conversations) | **CVPR 2026**: 複数人同期3D会話合成、**27,000クリップ**データセット、TalkDiff生成モデル |
| [CARE-Edit](papers/2026-03-10-care-edit-expert-routing-image-editing) | **CVPR 2026**: 条件認識MoEルーティングで異質な画像編集を統一、特化+汎用の両立 |
| [FOMO-3D](papers/2026-03-10-fomo-3d-vision-foundation-3d-detection) | **CoRL 2025/Waabi**: VFM特徴→LiDAR 3D検出、ロングテールで**6倍AP向上**、ゼロショット対応 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [OfficeQA Pro](papers/2026-03-10-officeqa-pro-enterprise-grounded-reasoning) | **Databricks**: エンタープライズグラウンディングベンチ、Claude Opus/GPT-5.4でも引用精度が課題 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [Interactive World Simulator](papers/2026-03-10-interactive-world-simulator-robot-policy) | ワールドシミュレータの統一ベンチマーク、**3レベルのインタラクティブ性**評価 |
| [MetaWorld-X](papers/2026-03-10-metaworld-x-humanoid-world-model) | VLMオーケストレーション型エキスパートでヒューマノイドloco-manipulation、階層的ワールドモデリング |

---

## 2026-03-09 注目論文：ReflexiCoderがGPT-5.1超え＆SWE-benchで行動木が73.6%達成＆会話型ショッピングRL＆DreamCADの100万キャプション＆CoT制御可能性分析

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [ChatShopBuddy](papers/2026-03-09-chatshopbuddy-conversational-shopping-rl) | 会話型ショッピングエージェントのRL最適化、**階層報酬モデリング**で安定性向上 |
| [MLLMRec-R1](papers/2026-03-09-mlllmrec-r1-grpo-multimodal-recommendation) | マルチモーダル逐次推薦向けGRPO、**視覚トークン支配問題を解決**、GitHub公開 |
| [R4T](papers/2026-03-09-r4t-rl-diffusion-fan-out-retrieval) | **Google**: RLで拡散検索器を訓練、セットレベル検索で**桁違いのレイテンシ削減** |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [ReflexiCoder](papers/2026-03-09-reflexicoder-self-reflection-code-generation) | 自己反省・自己修正をRL内部化、**8BモデルでGPT-5.1超え**、HumanEval 94.51% |
| [MAPO](papers/2026-03-09-mapo-multi-turn-dialogue-rl) | マルチターン対話のRL最適化、**Mixed Advantage Estimator**、EMPA+43.2向上 |
| [MASFactory](papers/2026-03-09-masfactory-llm-multi-agent-orchestration) | マルチエージェント設計を**Vibe Graphing**で自動化、GitHub・動画公開 |
| [CodeScout](papers/2026-03-09-codescout-software-agent-problem-enhancement) | 問題文の自動強化でSWE-bench**+20%解決率向上**、事前探索でエージェント改善 |
| [CRIMSON](papers/2026-03-09-crimson-radiology-report-evaluation) | 放射線レポートの臨床的評価メトリクス、**MedGemmaファインチューンモデル公開** |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [Traversal-as-Policy](papers/2026-03-09-traversal-as-policy-gated-behavior-trees) | 行動木で安全なLLMエージェント、SWE-bench**73.6%**達成、違反率2.8%→0.2% |
| [EvoESAP](papers/2026-03-09-evoesap-moe-expert-pruning) | MoEの非均一エキスパートプルーニング、MATH-500で**+19.6%**、既存手法と互換 |
| [SGPP](papers/2026-03-09-sgpp-rectified-flow-editing) | Rectified Flowの統一幾何学フレームワーク、**RF-inversionを一般化**、理論的保証あり |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [DreamCAD](papers/2026-03-09-dreamcad-multimodal-cad-generation) | 微分可能パラメトリック表面でCAD生成、**CADCap-1M**（GPT-5生成）データセット公開 |
| [Thinking with Spatial Code](papers/2026-03-09-thinking-spatial-code-3d-reasoning) | 3D空間推論、明示的空間コードで**VSI-BenchでSOTA**、GitHub公開 |
| [MultiHaystack](papers/2026-03-09-multihaystack-multimodal-retrieval-benchmark) | **46K件**のマルチモーダル検索ベンチマーク、GPT-5すら80.86%→51.4%に低下 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [CoT Controllability](papers/2026-03-09-cot-controllability-reasoning-models) | 推論モデルのCoT制御可能性分析、**Claude 4.5でCoT制御2.7%のみ**、安全性示唆 |
| [DeepFact](papers/2026-03-09-deepfact-factuality-benchmark-agents) | 深層調査レポートの事実性ベンチマーク、**AtS手法で専門家精度60.8%→90.9%** |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [RACAS](papers/2026-03-09-racas-robot-agnostic-agentic-control) | **単一エージェントシステム**で多様なロボット制御、地上・リム・水中で検証 |
| [OpenHEART](papers/2026-03-09-openheart-articulated-object-manipulation) | 脚ロボットで異種関節オブジェクト操作、**SAFE特徴抽出**でクロスドメイン汎化 |

---

## 2026-03-08 注目論文：ICLR2026/CVPR2026採択多数＆DeepSeek-R1推論分析＆GraphRAGのk-core改善＆VLA解釈可能性＆スマホでロボット改善

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [Core-GraphRAG](papers/2026-03-08-core-graphrag-kcore-hierarchies) | **Leidenの非再現性を証明**、k-core分解で決定論的階層、トークン削減＆包括性向上 |
| [TIPS](papers/2026-03-08-tips-debiasing-sequential-recommendation) | 逐次推薦のバイアス補正、**Time-aware IPS**、プラグイン方式で既存モデル改善 |
| [Reranking Scaling Laws](papers/2026-03-08-scaling-laws-reranking) | リランカーのスケーリング則初研究、**400Mで1B性能予測可能**、産業応用に示唆 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [Reasoning Theater](papers/2026-03-08-reasoning-theater-cot-analysis) | **DeepSeek-R1 671B/GPT分析**: パフォーマティブCoT検出、プローブでMMLU**80%トークン削減** |
| [POET-X](papers/2026-03-08-poetx-memory-efficient-llm-training) | 直交変換でメモリ効率化、**単一H100で10億パラメータ事前訓練**（AdamWはOOM） |
| [Censored LLMs](papers/2026-03-08-censored-llms-knowledge-elicitation) | Qwen3検閲モデルで誠実性引き出し評価、**DeepSeek R1に転移可能**、コード公開 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [SurvHTE-Bench](papers/2026-03-08-survhte-bench-survival-hte) | **ICLR 2026**: 生存分析HTE推定初ベンチマーク、合成・半合成・実データで評価 |
| [LWAIL](papers/2026-03-08-lwail-wasserstein-imitation) | **ICLR 2026**: 動力学認識潜在空間でワッサースタインIL、少数エピソードで高性能 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [FaceCam](papers/2026-03-08-facecam-portrait-video-control) | **CVPR 2026**: ポートレート動画カメラ制御、スケール認識条件付け |
| [CalibAtt](papers/2026-03-08-calibatt-video-generation-acceleration) | 動画生成の高速化、キャリブレートスパースアテンション、**最大1.58倍高速化** |
| [CompACT](papers/2026-03-08-compact-tokenizer-world-model) | **CVPR 2026**: ワールドモデル用**8トークン**圧縮、桁違いの高速プランニング |
| [MM-Lifelong](papers/2026-03-08-mm-lifelong-multimodal-understanding) | **NVIDIA共著**: 181時間の生涯理解データセット、ReMAエージェント提案 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [Attention Sinks Anatomy](papers/2026-03-08-attention-sinks-massive-activations) | Massive Activations＆Attention Sinks分析、**Pre-norm構成がキー** |
| [Bias-Bounded LLM Judges](papers/2026-03-08-bias-bounded-llm-judges) | LLM-as-a-Judgeの**理論的バイアス保証**、61-99%相関維持、コード公開 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [RoboPocket](papers/2026-03-08-robopocket-phone-robot-improvement) | **スマホでロボット即時改善**: ARビジュアルフォーサイト、データ効率**2倍** |
| [Safe-SAGE](papers/2026-03-08-safe-sage-semantic-robot-safety) | セマンティクス認識安全制御、Poisson Safety Function、**四足歩行ロボで実証** |
| [VLA Features](papers/2026-03-08-vla-feature-observation-control) | **π₀.₅/OpenVLA**: 特徴可観測性・制御可能性分析、ファインチューニングなしで適応 |

---

## 2026-03-07 注目論文：ICLR2026/CVPR2026/ICRA2026採択＆MIT多数＆Meta/NVIDIA重要研究＆医療LLM＆安全性ベンチマーク

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [OmniRet](papers/2026-03-07-omniret-efficient-and-highfidelity) | **CVPR 2026 / MIT**: オムニモダリティ検索、AV・3D・マルチモーダル統一、**高忠実度合成強化** |
| [Model](papers/2026-03-07-model-editing-for-new) | **WWW 2026 / MIT**: 生成IR向け動的文書統合、LLMパラメータ変更不要 |
| [CAMMSR](papers/2026-03-07-cammsr-categoryguided-attentive-mixture) | **ICDE 2026**: マルチソースレコメンデーション、MoE×カテゴリ誘導、**実世界データで検証** |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [ThaiSafetyBench](papers/2026-03-07-thaisafetybench-assessing-language-model) | **ICLR 2026**: タイ文化特化LLM安全性評価、**8,000テストケース**、GPT-4oで54%精度 |
| [LBM](papers/2026-03-07-lbm-hierarchical-large-autobidding) | **MIT**: 大規模自動入札モデル、階層推論でLTV予測＆入札決定、**本番運用想定** |
| [Med-V1](papers/2026-03-07-medv1-small-language-models) | **NCBI/NLM**: 医療エンティティ抽出、**ゼロショット45言語対応**、24B→4Bパラメータで効率化 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [SurvHTE-Bench](papers/2026-03-07-survhtebench-a-benchmark-for) | **ICLR 2026 / Meta**: 異質因果効果推定ベンチマーク、**25データセット×50手法**包括評価 |
| [FairFinGAN](papers/2026-03-07-fairfingan-fairnessaware-synthetic-finan) | **KDD 2026 / MIT**: 公平性保証合成金融データ生成、**人種・性別バイアス軽減** |
| [SlideSparse](papers/2026-03-07-slidesparse-fast-and-flexible) | **NVIDIA**: (2N-2):2N構造的スパース性、**柔軟なN:M比率**、ハードウェア親和性高 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [FaceCam](papers/2026-03-07-facecam-portrait-video-camera) | **CVPR 2026 / MIT**: ポートレート動画カメラ制御、スケール認識条件付け、**顔クロップ・ボケ制御** |
| [MoRe](papers/2026-03-07-more-motionaware-feedforward-4d) | **CVPR 2026 / MIT**: モーション認識4D再構成、**フィードフォワード12fps**、Transformer |
| [CoIn3D](papers/2026-03-07-coin3d-revisiting-configurationinvariant) | **CVPR 2026 / Meta**: マルチカメラ3D物体検出、**カメラ構成不変**、再キャリブ不要 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [Survive at All Costs](papers/2026-03-07-survive-at-all-costs) | Survive at All Costs: Exploring LLM's Risky Behaviors under Survival Pressure... |
| [Judge Reliability Harness](papers/2026-03-07-judge-reliability-harness-stress) | **ICLR 2026**: LLMジャッジの信頼性ストレステスト、**デプロイ済みシステム診断** |
| [AI+HW 2035](papers/2026-03-07-aihw-2035-shaping-the) | **MIT**: 次の10年のAI×ハードウェア未来予測、**産業界向けロードマップ** |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [UltraDexGrasp](papers/2026-03-07-ultradexgrasp-learning-universal-dextero) | **ICRA 2026 / MIT**: ユニバーサル巧緻把持、**両手協調**、実世界転移成功 |
| [GaussTwin](papers/2026-03-07-gausstwin-unified-simulation-and) | **ICRA 2026 / MIT**: Gaussian Splatting×シミュレーション統合、**Sim2Real補正** |

## 2026-03-06 注目論文：Baidu MoUE新スケーリング次元＆Alibaba SkillNet 20万スキル＆DeepSeek-R1推論分析＆GraphRAGのLeiden限界証明＆RLHF浅さの理論解明

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🔧 SearchGym](papers/2026-03-06-searchgym) | RAGモジュラーインフラ、Compositional Config Algebraで再現性保証、**Top-100検索率70%**、コード公開 |
| [💰 FinRetrieval](papers/2026-03-06-finretrieval) | 金融検索ベンチマーク、Claude Opus API有り**90.8%** vs Web検索のみ**19.8%**、71ppギャップ |
| [📈 Reranking Scaling](papers/2026-03-06-reranking-scaling) | リランカーのスケーリング則初研究、400Mで1B性能予測可能、NDCG/MAPは信頼性あり |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🎭 Reasoning Theater](papers/2026-03-06-reasoning-theater) | **DeepSeek-R1 671B/GPT分析**: パフォーマティブCoT検出、プローブでMMLUトークン**80%削減** |
| [🔓 Censored LLMs](papers/2026-03-06-censored-llm) | Qwen3検閲モデルで誠実性引き出し評価、**DeepSeek R1に転移可能**、プロンプト・コード公開 |
| [🔬 RLHF Shallow](papers/2026-03-06-rlhf-shallow) | **RLHFアラインメントが浅い理由を理論証明**: 害地平線以降で勾配ゼロ、回復ペナルティ目的関数を導出 |
| [🔗 Core-GraphRAG](papers/2026-03-06-core-graphrag) | **Leidenの非再現性を数学的証明**、k-core分解で決定論的階層、トークン削減＆包括性向上 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [🔀 MoUE](papers/2026-03-06-moue) | **Baidu**: MoEの新次元「Virtual Width」、層間ユニバーサルエキスパート再利用、既存MoE変換で**+4.2%** |
| [💾 POET-X](papers/2026-03-06-poetx) | 直交変換でメモリ効率化LLM訓練、**単一H100で10億パラメータ事前訓練**（AdamWはOOM） |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [🛠️ SkillNet](papers/2026-03-06-skillnet) | **Alibaba/浙江大学**: 20万スキルのAIエージェントインフラ、平均報酬**+40%**、実行ステップ**-30%** |
| [🏥 Model Medicine](papers/2026-03-06-model-medicine) | AIモデルを生物学的に診断・治療、Neural MRI診断ツール、15サブ分野の学問分類を提案 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🧠 VPWEM](papers/2026-03-06-vpwem) | 作業記憶＋エピソード記憶visuomotorポリシー、VLA/拡散ポリシーを**20%以上**上回る、コード公開 |
| [📱 RoboPocket](papers/2026-03-06-robopocket) | **スマホでロボット即時改善**: AR Visual Foresight、データ効率**2倍**、分散収集対応 |

---

## 2026-03-05 注目論文：ICLR2026/CVPR2026/WWW2026/ICRA2026採択＆Google 3D再構成20x高速化＆ByteDance/Kuaishou本番運用＆Deep Researchエージェント検索

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🏭 SORT](papers/2026-03-05-sort) | **大規模Eコマース本番**: Transformer産業規模ランキング、**GMV +5.47%、注文数 +6.35%**、レイテンシ44%削減 |
| [📊 HAP](papers/2026-03-05-hap) | **WWW 2026 / ByteDance**: 異質サンプル勾配衝突解決、**Toutiao 9ヶ月運用**、産業データセット公開 |
| [⚡ SOLAR](papers/2026-03-05-solar) | **Kuaishou本番**: SVD-Attentionで計算量O(N²d)→O(Ndr)、万スケール行動シーケンス対応、**Video Views +0.68%** |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🔍 AgentIR](papers/2026-03-05-agentir) | **Deep Research向け**: 推論トレース×クエリ共同埋め込み、BrowseComp-Plusで**68%精度**（従来50%）、コード公開 |
| [🔤 ByteFlow](papers/2026-03-05-byteflow) | **ICLR 2026 / Amazon**: トークナイザー完全排除、圧縮駆動セグメンテーション、BPE Transformerを上回る |
| [🧠 Memex(RL)](papers/2026-03-05-memex) | 長期間LLMエージェント向けインデックス付きメモリ、要約のみ手法より低損失、理論保証付き |
| [✅ V₁](papers/2026-03-05-v1) | **UC Berkeley**: ペアワイズ自己検証でテストタイム推論効率化、コード生成Pass@1 **最大+10%** |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [🛡️ DMAST](papers/2026-03-05-dmast) | GRPOベースマルチモーダルWebエージェント安全学習、タスク完了効率**2倍**、OODリスク大幅軽減 |
| [🌊 Flow Matching for TD](papers/2026-03-05-flow-td) | TD学習にFlow Matching適用、分布RLでなく**テストタイム回復**が鍵、性能2倍・サンプル効率5倍 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🗺️ ZipMap](papers/2026-03-05-zipmap) | **Google DeepMind**: 線形時間3D再構成、700フレーム10秒未満、**VGGT 20倍以上高速** |
| [✏️ Pointer-CAD](papers/2026-03-05-pointer-cad) | **CVPR 2026**: LLMベースCAD生成でエンティティ選択実現、575Kモデルデータセット公開 |
| [🌐 EmbodiedSplat](papers/2026-03-05-embodiedsplat) | **CVPR 2026**: オンラインOpen-Vocabulary 3DGS、CLIP Codebookで効率的セマンティック理解 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [🏦 τ-Knowledge](papers/2026-03-05-tau-knowledge) | **Princeton**: 非構造化知識上エージェント評価、700文書ナビゲーション、フロンティアモデルでも**25.5%**の厳しい結果 |
| [⚙️ Agentics 2.0](papers/2026-03-05-agentics2) | **IBM**: 論理変換代数でエージェントワークフロー形式化、DiscoveryBench/ArcherでSOTA |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🏠 RoboCasa365](papers/2026-03-05-robocasa365) | **ICLR 2026**: 365タスク×2500環境、2200時間デモデータ、汎用ロボット研究の包括的ベンチマーク |
| [👕 GarmentPile++](papers/2026-03-05-garmentpile) | **ICRA 2026**: VLM×視覚アフォーダンスで衣類パイルから安全取り出し、SAM2+双腕協調 |

---

## 2026-03-04 注目論文：ICLR2026 Oral/CVPR2026/WWW2026採択＆Yann LeCunマルチモーダル＆Tri Dao 5x推論高速化＆Microsoft/Kuaishouエージェント安全性

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🔧 DOME](papers/2026-03-04-dome) | **WWW 2026 / Baidu**: 生成的検索のモデル編集、新規文書追加を再訓練なしで効率化、**訓練時間60%削減** |
| [🔄 S2CDR](papers/2026-03-04-s2cdr) | **WWW 2026**: 拡散モデル×クロスドメイン推薦、ノイズフリーSmoothing-Sharpeningアーキテクチャ、Training-freeでSOTA |
| [⚡ FlashEvaluator](papers/2026-03-04-flashevaluator) | **Kuaishou本番**: 評価器並列化でサブリニア計算量、**オンライン推薦システム稼働中**、実収益向上 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🛡️ MOSAIC](papers/2026-03-04-mosaic) | **Microsoft**: マルチステップツール使用の安全性、Plan-Check-Act/Refuseループ、有害行動**-50%**＆インジェクション耐性**+20%** |
| [🏥 ExpGuard](papers/2026-03-04-expguard) | **ICLR 2026**: 金融・医療・法律ドメイン向けLLMガードレール、WildGuard比**+8.9%/+15.3%**、データ・モデル公開 |
| [🔗 ACE-Merging](papers/2026-03-04-ace-merging) | **CVPR 2026**: データフリーモデルマージング、パラメータ差分から入力共分散推定可能を理論証明、GPT-2で**+4%** |
| [👁️ VC-STaR](papers/2026-03-04-vc-star) | **ICLR 2026 Oral**: VLM視覚推論の自己改善、視覚コントラストでハルシネーション軽減、55Kデータセット公開 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [🌵 Saguaro](papers/2026-03-04-saguaro) | **Tri Dao（FlashAttention作者）**: Speculative Decodingの投機と検証を並列化、**自己回帰比5倍高速** |
| [📊 Adam vs SGD](papers/2026-03-04-adam-sgd) | 「なぜAdamがSGDに勝てるか」の初の理論的分離、二次モーメント正規化が鍵、59ページの詳細解析 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🌐 Beyond LLM](papers/2026-03-04-beyond-llm) | **Yann LeCun / Meta AI**: ネイティブマルチモーダル設計空間、RAE（表現オートエンコーダ）＆MoEでスケーリング非対称性解決 |
| [🎨 CFG-Ctrl](papers/2026-03-04-cfg-ctrl) | **CVPR 2026**: CFGを制御理論で再解釈、SMC（スライディングモード制御）でStable Diffusion 3.5/Flux改善 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [🎯 Inherited Goal Drift](papers/2026-03-04-goal-drift) | **ICLR 2026 Workshop**: エージェントLMの目標ドリフト、**GPT-5.1含む最新モデルで評価**、弱エージェント軌跡からのドリフト継承問題 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🤖 ULTRA](papers/2026-03-04-ultra) | **UIUC**: ヒューマノイド全身歩行操作、物理駆動リターゲット＆マルチモーダル制御、**Unitree G1実機検証** |
| [🔪 How to Peel](papers/2026-03-04-peel) | **Berkeley (Abbeel/Malik) / ICLR 2026**: ナイフ剥き操作、嗜好ベースRL、50-200軌跡で**90%成功率**、異カテゴリ汎化 |

---

## 2026-03-03 注目論文：CVPR2026/ICLR2026/WWW2026/ICAPS2026採択＆Meta本番15世代反復改善＆Xiaohongshu/Kuaishouコールドスタート解決

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🌐 OmniRet](papers/2026-03-03-omniret) | **CVPR 2026**: 初の3モダリティ（テキスト・ビジョン・オーディオ）統合検索、Attention Sliced Wasserstein Poolingで高忠実度表現、**GitHub公開** |
| [🆕 IDProxy](papers/2026-03-03-idproxy) | **Xiaohongshu本番**: MLLMでアイテムコールドスタート解決、マルチモーダルProxy埋め込み生成、ID埋め込み空間にアラインメント |
| [📊 HPGR](papers/2026-03-03-hpgr) | **WWW 2026**: 生成型推薦の階層構造活用、セッションベースMIM事前学習、Preference-Guided Sparse Attention、**Huawei APPGallery本番検証** |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🔄 CharacterFlywheel](papers/2026-03-03-characterflywheel) | **Meta本番**: Instagram/WhatsApp/Messenger向けLLM反復改善、15世代でエンゲージメント**+19.4%**、指示追従**59.2%→84.8%** |
| [📏 LongRLVR](papers/2026-03-03-longrlvr) | **ICLR 2026**: 長コンテキストRLVR失敗原因を特定、**Verifiable Context Rewards**でコンテキストグラウンディング改善、**GitHub公開** |
| [🗄️ GenDB](papers/2026-03-03-gendb) | **Claude Code Agent**活用：クエリエンジンを「設計」ではなく「合成」、DuckDB/Umbra/ClickHouse等を上回る性能 |
| [🧠 AMemGym](papers/2026-03-03-amemgym) | **ICLR 2026**: 長期会話メモリ管理のインタラクティブベンチマーク、RAG/長コンテキストLLM/エージェント型メモリの性能ギャップ分析 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [🎯 ACR](papers/2026-03-03-acr-multimodal) | **CVPR 2026**: マルチモーダル故障検出のAdaptive Confidence Regularization、自動運転・医療診断向け、**GitHub公開** |
| [⚡ Multi-Head Low-Rank Attention](papers/2026-03-03-multi-head-low-rank) | **ICLR 2026**: 長コンテキストKVキャッシュボトルネック解決、MLAのTPシャーディング問題克服、**GitHub公開** |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🖼️ HiFi-Inpaint](papers/2026-03-03-hifi-inpaint) | **CVPR 2026**: 広告・EC向け高忠実度リファレンスInpainting、製品ディテール完全保持の人物×製品画像生成 |
| [✏️ Sketch2Colab](papers/2026-03-03-sketch2colab) | **CVPR 2026**: ストーリーボード2Dスケッチから一貫した3Dマルチヒューマンモーション生成、Controllable Flow Distillation |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [🎲 CB-MCTS](papers/2026-03-03-cb-mcts) | **ICAPS 2026**: 分散マルチエージェント計画向けBoltzmannベース探索、スパース/歪み報酬環境での堅牢性向上 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [📷 Fisheye Camera Study](papers/2026-03-03-fisheye-robot) | **CVPR 2026**: ロボットマニピュレーションにおけるフィッシュアイカメラ特性の初の包括的実証研究、広FoV vs 歪みのトレードオフ分析 |
| [📚 ACDC](papers/2026-03-03-acdc-robot) | **ICAPS 2026**: 目標条件付きRL向け適応的カリキュラム計画+動的コントラスト制御、人間の学習行動に着想、**GitHub公開** |

---

## 2026-03-02 注目論文：ICLR2026 Oral/ICLR2026/ECIR2026/CIKM2025採択＆Stanford-NVIDIA長動画生成＆産業検索システム実運用

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🧠 Beyond the Click](papers/2026-03-02-beyond-the-click) | **ECIR 2026**: 認知トレース推論、IFTベースマルチエージェント、ユーザーシミュレータ高度化 |
| [🔗 UXSim](papers/2026-03-02-uxsim) | **CIKM 2025**: ハイブリッドユーザー検索シミュレーション、従来シミュレータ+LLMエージェント統合 |
| [⚡ SA²CRQ](papers/2026-03-02-sarq) | **産業検索システム**: セマンティックID適応量子化、**コールドスタート検索改善**、エントロピーベースコード長動的割り当て |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🏆 LoRA-Pre](papers/2026-03-02-lora-pre) | **ICLR 2026 Oral**: 低ランクオプティマイザ、**ベースラインの1/8ランク**で同等以上、Llama-3.1-8B **+3.14pt**、**GitHub公開** |
| [🔒 Controllable Reasoning](papers/2026-03-02-controllable-reasoning) | 推論トレースのプライバシー保護、指示追従**+20.9pt**、プライバシー**+51.9%pt**、**GitHub公開** |
| [⚡ Preference Packing](papers/2026-03-02-preference-packing) | DPO効率化、訓練時間**37%以上削減**、バッチソート併用で**3.22倍高速化** |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [🚀 CUDA Agent](papers/2026-03-02-cuda-agent) | エージェント強化学習でCUDAカーネル生成、torch.compile比**100%高速**、**Claude Opus 4.5/Gemini 3 Pro比+40%** |
| [🎯 RewardUQ](papers/2026-03-02-rewarduq) | 報酬モデル不確実性定量化統一フレームワーク、**GitHub公開** |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🎬 UFO-4D](papers/2026-03-02-ufo-4d) | **ICLR 2026**: 2画像から4D再構成、Dynamic 3D Gaussian Splats、従来手法**3倍改善** |
| [🎥 Mode Seeking meets Mean Seeking](papers/2026-03-02-mmm-video) | **Stanford/NVIDIA**: 分スケール長動画生成、短動画品質継承+長期一貫性、Decoupled Diffusion Transformer |
| [📄 AgenticOCR](papers/2026-03-02-agenticocr) | クエリ駆動OCR、視覚RAG効率化、**エキスパートレベル**文書理解、**GitHub公開** |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [📊 DARE-bench](papers/2026-03-02-dare-bench) | **ICLR 2026**: データサイエンス指示追従ベンチマーク、6,300 Kaggleタスク、RL訓練で**8倍精度向上** |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🔧 SafeGen-LLM](papers/2026-03-02-safegen-llm) | 安全性汎化LLM、PDDL3+形式検証、新規安全制約への汎化、Info-DPO |
| [🔍 VLA Grounding診断](papers/2026-03-02-vla-grounding) | VLAポリシーの汎化限界分析、SmolVLA/π₀.₅評価、**操作スキルと言語グラウンディングの分離**発見 |

---

## 2026-03-01 注目論文：CVPR2026/ICLR2026/SIGMOD2026/TACL2026/ICRA2026採択＆YouTube本番948倍高速化＆Kuaishou4億ユーザーデプロイ

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [⚡ STATIC](papers/2602.22647-static) | **YouTube/Google**: Trie→CSR行列変換、**948倍高速化**、billion users本番デプロイ、**GitHub公開** |
| [📢 GR4AD](papers/2602.22732-gr4ad) | **Kuaishou**: 生成的広告推薦、**4億ユーザー本番**、広告収益**4.2%向上** |
| [📄 MoDora](papers/2602.23061-modora) | **SIGMOD 2026**: 半構造化文書LLM分析、CCTree階層表現、**61%精度改善**、**GitHub公開** |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🎯 SPARTA](papers/2602.23286-sparta) | **ICLR 2026**: マルチホップQAベンチマーク自動生成、SOTAモデル**30 F1低下**、**GitHub公開** |
| [🧠 Scale & Pragmatics](papers/2602.23351-scale-pragmatics) | **TACL 2026**: VLM推論欠如の報告バイアス原因、スケーリングでは解決しない |
| [🌀 Diffusion Stitching](papers/2602.22871-diffusion-stitching) | 拡散LM+報酬ガイドスティッチング、訓練不要**23.8%精度向上**・**1.8倍高速化**、**GitHub公開** |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [⚡ FlashOptim](papers/2602.23349-flashoptim) | **Databricks**: メモリ効率訓練、AdamW **16→7 bytes/param**、品質劣化なし、**GitHub公開** |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🎬 VGG-T³](papers/2602.23361-vgg-ttt) | **NVIDIA/CVPR 2026**: 3D再構成線形スケーリング、1000画像54秒、**11.6倍高速化** |
| [🌐 ThinkOmni](papers/2602.23306-thinkomni) | **ICLR 2026**: オムニモーダル推論、訓練不要LRM誘導デコーディング、MathVista **70.2** |
| [🔮 GeoWorld](papers/2602.23058-geoworld) | **CVPR 2026**: 双曲幾何ワールドモデル、4ステップ計画**2% SR改善** (V-JEPA 2比) |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [🧩 AgentDropoutV2](papers/2602.23258-agentdropoutv2) | MASテスト時プルーニング、再訓練不要、数学ベンチ**+6.3ポイント**、**GitHub公開** |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🔧 SPARR](papers/2602.23253-sparr) | **NVIDIA**: Sim+実世界残差ハイブリッド、アセンブリ成功率**+38.4%**、サイクルタイム**29.7%短縮** |
| [✋ Grasp/Slide/Roll](papers/2602.23206-grasp-slide-roll) | **ICRA 2026**: 触覚接触モード比較、**34%少ないインタラクション**で**55%精度改善** |

---

## 2026-02-28 注目論文：ICLR2026 Oral/KDD2026/SIGMOD2026/WWW2026/CVPR2026採択＆YouTube実運用＆自動運転200km実車テスト

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [⚡ STATIC](papers/2602.22647) | **YouTube/Google**: Trie→CSR行列変換、**948倍高速化**、billion users本番デプロイ、**GitHub公開** |
| [🔗 PSQE](papers/2602.22903) | **KDD 2026採択**: マルチモーダルエンティティアライメント擬似シード品質向上、プラグアンドプレイ |
| [📄 MoDora](papers/2602.23061) | **SIGMOD 2026**: 半構造化文書LLM分析、CCTree階層表現、**61%精度改善**、**GitHub公開** |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🧠 RAIN-Merging](papers/2602.22538) | **ICLR 2026 Oral**: LRM命令追従強化、ヌル空間射影+命令attention、thinking形式維持 |
| [🔍 Search-P1](papers/2602.22576) | Agentic RAG訓練、パス中心報酬形成、失敗サンプルからも学習、**+7.7精度** |
| [🌀 dLLM](papers/2602.22661) | 拡散言語モデル統一フレームワーク、LLaDA/Dream再現、**GitHub公開** |
| [📖 CiteLLM](papers/2602.23075) | **WWW 2026 Demo**: 科学文献発見エージェント、LaTeX内統合、ハルシネーションフリー |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [⚖️ CPAS + LAGR](papers/2602.22556) | LRM適応的思考、正しい長鎖推論維持、**トークン43%削減・精度+3.7** |
| [📊 TabDLM](papers/2602.22586) | テーブル+自由形式テキスト共同生成、数値-言語拡散、MDLM基盤 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🔬 Histopathology FM](papers/2602.22347) | 病理学基盤モデル臨床利用、ロバスト性損失、27,042 WSI検証、再訓練不要 |
| [🎯 pMoE](papers/2602.22938) | MoEプロンプトチューニング、多様エキスパート統合、47タスク評価、医療+一般 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [🌐 OmniGAIA](papers/2602.22897) | オムニモーダルエージェントベンチマーク、動画+音声+画像、OmniAtlas基盤エージェント |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🚗 HDP](papers/2602.22801) | **実車200kmテスト**: 拡散モデルE2E自動運転プランナー、6シナリオ、**10倍改善** |
| [✋ GraspLDP](papers/2602.22862) | **CVPR 2026採択**: 潜在拡散グラスプポリシー、自己教師あり、動的グラスプ |

---

## 2026-02-27 注目論文：CVPR2026/ICLR2026/EACL2026採択＆RAG情報理論分析＆VLA長期ホライズン操作

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🔬 Text Ranking in Deep Research](papers/2602.21456) | Deep Researchでのテキストランキング再評価、BrowseComp-Plus、5リトリーバー×3リランカー |
| [📊 MIGRASCOPE](papers/2602.21553) | RAGリトリーバー情報理論分析、相互情報量ベース、アンサンブル設計指針 |
| [🌳 TrieRec](papers/2602.21677) | Trie構造認識型生成推薦、位置エンコーディング2種、**平均8.83%改善** |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🌊 Field-Theoretic Memory](papers/2602.21220) | 場の理論でAIエージェントメモリ、LongMemEval +116% F1、**GitHub公開** |
| [📦 Latent Context Compilation](papers/2602.21221) | 長文脈→コンパクトメモリ蒸留、**16倍圧縮**、合成QA不要 |
| [⚡ Hidden State Speculative Decoding](papers/2602.21224) | ドラフトトークン再利用、隠れ状態自己回帰、**3.3倍高速化** |
| [✅ Distill and Align](papers/2602.21857) | **EACL 2026 Findings**: クレーム検証分解、GRPO最適化、71.75% F1 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [🛡️ Reliability Certification](papers/2602.21368) | AIエージェント信頼性認証、Conformal Calibration、**分布非依存保証** |
| [🎯 PF-DAG](papers/2602.21684) | **ICLR 2026**: アクション生成2段階分離、56タスクSOTA、実世界触覚操作 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [📈 DynamicGTR](papers/2602.21864) | **CVPR 2026**: VLMグラフQA、動的トポロジー表現選択、追加訓練なし転移 |

### 🤖 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🔗 LiLo-VLA](papers/2602.21531) | 長期ホライズン操作、オブジェクト中心VLA、Pi0.5比**41%改善**、実世界85% |
| [🔄 SC-VLA](papers/2602.21633) | 自己修正VLA、Sparse World Imagination、**16%少ないステップで9%高い成功率**、**GitHub公開** |

---

## 2026-02-26 注目論文：ICLR2026/NeurIPS2025 Spotlight/CVPR2026採択＆Microsoft/RMIT＆効率的推論・RAG・VLM解釈

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [🔬 DEEPSYNTH](papers/2602.21143) | **ICLR 2026採択**: 深層情報統合ベンチマーク、120タスク・7ドメイン・67カ国 |
| [🗣️ MIMIC](papers/2602.20517) | **NeurIPS 2025 Spotlight**: 内的言語で行動をガイド、Human-AI協調 |

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🏆 R2RAG](papers/2602.20735) | **NeurIPS 2025 MMU-RAG優勝**: 動的検索戦略適応RAG、RMIT |
| [📦 Multi-Vector Compression](papers/2602.21202) | マルチモーダル検索インデックス圧縮、Attention-Guided Clustering、GitHub公開 |
| [🎯 PRECTR-V2](papers/2602.20676) | 検索関連性・CTR統合フレームワーク、コールドスタート対応、LLM蒸留 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🔒 PI Parroting](papers/2602.20580) | **EACL 2026採択**: LLMの個人情報記憶リスク定量化、Pythia全スケール分析 |
| [⚡ Efficient Reasoning](papers/2602.20945) | 0.2M GPU時間の大規模研究、CoT効率化ガイドライン、Qwen3シリーズ検証 |
| [🎰 QueryBandits](papers/2602.20332) | Contextual banditでハルシネーション緩和、クローズドソースLLM対応 |
| [📝 SibylSense](papers/2602.20751) | **Microsoft Research**: 適応的ルーブリック学習、RL post-training報酬設計 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [🔢 MoBiQuant](papers/2602.20191) | Mixture-of-Bits量子化、弾性LLMデプロイメント、Duke/Panasonic |
| [🔄 LoDADA](papers/2602.21072) | 局所ダイナミクス適応オフラインRL、ソースデータ効率的再利用 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🔍 Circuit Tracing](papers/2602.20330) | **CVPR 2026 Findings採択**: VLM内部回路追跡、マルチモーダル推論解明 |
| [🎨 COMiT](papers/2602.20731) | コミュニケーション着想のトークン化、オブジェクト中心表現、プロジェクト公開 |
| [🌐 IPOW](papers/2602.20616) | 解釈可能オープンワールド物体検出、概念分解モデル |

### 🤖 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [💪 OptimusVLA](papers/2602.20200) | デュアルメモリVLA、LIBERO成功率98.6%、実ロボット2.9倍高速化 |
| [⚡ Squint](papers/2602.21203) | 15分Sim-to-Real訓練、単一RTX 3090、GitHub公開 |

---

## 2026-02-25 注目論文：CVPR2026複数採択＆ICLR/AAAI/EACL2026採択＆WWW2026推薦＆MIT/CMU/Penn著名研究者

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [⚖️ FairFS](papers/2602.20001) | **WWW 2026採択**: 推薦システムの深層特徴量選択バイアス解決、Huawei |
| [🎯 ManCAR](papers/2602.20093) | Sequential推薦の多段階潜在推論、**NDCG@10で46.88%改善**、GitHub公開 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [📚 NanoKnow](papers/2602.20122) | LLMが何を知っているか解明するベンチマーク、**Jimmy Lin (Waterloo)**、GitHub公開 |
| [🔍 ReAttn](papers/2602.19969) | **EACL 2026採択**: attention-based re-rankingの改善、Jian-Yun Nie |
| [🧠 RAG Internal](papers/2602.20091) | RAGにおける検索コンテキストの内部表現への影響分析、Sharon Li |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [📐 Behavior Learning](papers/2602.20152) | **ICLR 2026採択**: 行動科学発想の解釈可能ML、階層最適化構造学習、GitHub公開 |
| [🛡️ BarrierSteer](papers/2602.20102) | **MIT Daniela Rus**: 制御バリア関数でLLM安全性を推論時に強制 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🔄 tttLRM](papers/2602.20160) | **CVPR 2026採択**: Test-Time Trainingで長コンテキスト3D再構築 |
| [🌊 Flow3r](papers/2602.20157) | **CVPR 2026採択**: ファクタライズドフロー予測、**CMU Tulsiani**、800K動画訓練 |
| [🖼️ StructXLIP](papers/2602.20089) | **CVPR 2026採択**: エッジベースvision-languageアライメント、GitHub公開 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [🤝 Human-AI Ensemble](papers/2602.20104) | **AAAI 2026採択**: 適応的人間-AI協働、**Ming Yin (Purdue)**、補完/アライメント切替 |
| [🔬 ReSyn](papers/2602.20117) | 推論環境自動生成でRLVRスケーリング、**BBEHで27%改善** |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🎬 NovaPlan](papers/2602.20119) | ゼロショット長期視野操作、**CMU Kitani & Brown Konidaris**、閉ループVLM計画 |
| [🛡️ CORE](papers/2602.19983) | オープンワールド安全推論、**UPenn Vijay Kumar & Pappas**、VLM+CBF統合 |

---

## 2026-02-24 注目論文：ICLR2026複数採択＆EACL/ECIR/AAAI2026採択＆動画検索本番デプロイ＆ベイズ最適ICL理論

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🎬 WeWrite](papers/2602.17667) | 動画検索クエリリライティング、**大規模プラットフォーム本番A/Bテスト**、VV+1.07% |
| [📄 IRPAPERS](papers/2602.17687) | 科学論文の画像/テキスト検索ベンチマーク、マルチモーダル検索がSOTA、**コード公開** |
| [⚙️ SuiteEval](papers/2602.18107) | **ECIR 2026 Demo採択**: IR評価統一フレームワーク、BEIR/MS MARCO等対応 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🧠 Neural Synchrony](papers/2602.17815) | **ICLR 2026採択**: LLM間の神経同期、社会的パフォーマンスと強相関を発見 |
| [🔍 ELIA](papers/2602.18262) | **EACL 2026 Demo**: LLM内部分析を一般ユーザー向けに簡略化、**GitHub公開** |
| [⚖️ Vichara](papers/2602.18346) | **AAAI 2026 (AI & Law)**: インド司法向け控訴審予測、GPT-4oでF1=81.5 |
| [🔄 RVR](papers/2602.18425) | Retrieve-Verify-Retrieve、マルチアンサー検索でagentic search超え、+10%相対改善 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [📐 Bayesian ICL](papers/2602.17744) | **理論研究**: Selective SSMがベイズ最適予測器を実装、勾配降下からの統計的分離を証明 |
| [🏭 NIMMGen](papers/2602.18008) | LLMでメカニスティックデジタルツイン自動構築、3科学ドメインで検証 |
| [🔬 ADAPT](papers/2602.17867) | LLM特徴可視化、Gemma 2 SAE潜在表現で評価、**CNN手法のLLM拡張** |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [✋ CLUTCH](papers/2602.17770) | **ICLR 2026採択**: テキスト→手モーション生成、32K 3Dシーケンスデータセット公開 |
| [👁️ VLM Fine-Grained](papers/2602.17871) | VLMの細粒度知識能力分析、Vision Encoderが鍵、事前学習でLLM解凍が重要 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [⚠️ Epistemic Traps](papers/2602.17676) | AI安全性理論、Sycophancy/Hallucinationをモデル誤特定から説明、6モデルで検証 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🤝 Nested Training](papers/2602.17737) | I-POMDPで人間-AIチーム相互適応、Overcookedで汎化性能実証 |
| [🚲 HJ-RL Cyclist](papers/2602.18097) | **CMU**: Hamilton-Jacobi到達可能性+RL、自転車乗りとの安全相互作用 |

---

## 2026-02-23 注目論文：IEEE TKDE採択＆LREC2026複数採択＆Agentic Search新データセット＆Bloom Filter発見

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🔍 Agentic Search (ASQ)](papers/2602.17518) | エージェント検索行動の初体系的データセット、HotpotQA/MS MARCO対応 |
| [📊 Missing Modalities (IEEE TKDE)](papers/2602.17354) | **IEEE TKDE採択**: マルチモーダル推薦の欠損補完、訓練不要グラフベース手法 |
| [🎯 ILRec](papers/2602.17410) | LLM推薦の中間層ハードネガティブ、選好学習を大幅改善 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🤝 Web Agent Intervention](papers/2602.17588) | 人間介入4パターン特定、有用性**26.5%向上**、400軌跡データセット |
| [🏥 Small Medical LLMs (LREC 2026)](papers/2602.17475) | **LREC 2026採択**: 1.7Bが32Bを+9.2pt上回る、イタリア語医療データ公開 |
| [🛡️ Learning to Stay Safe](papers/2602.17546) | ファインチューニング時のLLM安全性維持、適応的正則化フレームワーク |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [⚖️ MARS Reward Modeling](papers/2602.17658) | RLHF向けマージン認識報酬モデリング、理論的保証付きデータ拡張 |
| [🔮 Bloom Filters in Attention](papers/2602.17526) | Transformerヘッドがメンバーシップテスト機能、**R²=1.0**で理論曲線一致、**GitHub公開** |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🌍 OpenEarthAgent](papers/2602.17665) | 地理空間エージェント統合FW、14K訓練インスタンス、NDVI/NBR分析対応 |
| [🔄 IntRec](papers/2602.17639) | 意図ベースインタラクティブ検索、LVIS +2.3AP、フィードバック1回で+7.9AP |
| [👁️ Human-level 3D](papers/2602.17650) | Multi-view学習で人間レベル3D知覚、ゼロショット達成、コード公開 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [🧮 AutoNumerics](papers/2602.17607) | 自然言語からPDEソルバー自動生成、マルチエージェントパイプライン |
| [📜 CLEF HIPE-2026 (ECIR)](papers/2602.17663) | **ECIR 2026 Lab**: 歴史テキストから人物-場所関係抽出、登録締切4/23 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🤖 GNN-MPC](papers/2602.17601) | 1000ノード100Hz制御、ソフトロボットでsub-cm精度、**ベースライン+63.6%** |
| [🚗 Deep-Flow](papers/2602.17586) | L4自動運転異常検出、Waymoデータ、AUC-ROC 0.766達成 |

---

## 2026-02-22 注目論文：ULTRA-HSTU数十億ユーザー本番＆Taobao LTV Billion-Scale＆ICLR2026 ODESteer＆MIT Berkeley CV

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🛒 Mine and Refine](papers/2026-02-21-mine-and-refine) | Eコマース検索の段階的関連性最適化、**本番A/Bテストで有意な改善** |
| [🚀 ULTRA-HSTU](papers/2026-02-21-ultra-hstu) | **数十億ユーザー本番デプロイ**、推薦Scaling Law、学習5倍・推論21倍高速 |
| [📺 Taobao LTV](papers/2026-02-21-taobao-ltv) | **Alibaba**: Billion-scale動画ランキング、Long-term Value予測、4-8%改善 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [✂️ Sink-Aware Pruning](papers/2026-02-21-sink-aware-pruning) | Diffusion LMのpruning、再学習不要、**GitHub公開** |
| [🚀 KLong](papers/2026-02-21-klong) | 極長ホライズンエージェント、**Kimi K2 Thinking (1T)を11%上回る** |
| [⚖️ ODESteer (ICLR 2026)](papers/2026-02-21-odesteer) | **ICLR 2026**: ODE理論でLLM Alignment、TruthfulQA +5.7% |
| [👥 Web Agent Intervention (CMU)](papers/2026-02-21-web-agent-intervention) | **CMU Neubig**: 人間介入モデル化、有用性26.5%向上 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [💧 Anytime Watermarking (Berkeley)](papers/2026-02-21-anytime-watermarking) | **Michael I. Jordan**: E-value-based検出、トークン13-15%削減 |
| [⏰ Reverso (MIT)](papers/2026-02-21-reverso) | **Yoon Kim**: 100倍小さいTS Foundation Model、zero-shot SOTA |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🤖 VLA Counterfactual](papers/2026-02-21-vla-counterfactual) | 初のVLA反事実ベンチマーク、実世界17.2%改善、**Website公開** |
| [👁️ Human-level 3D (Berkeley)](papers/2026-02-21-human-3d-perception) | **Jitendra Malik**: Multi-view学習で人間レベル3D知覚達成 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [🎮 AI Gamestore (MIT/Stanford)](papers/2026-02-21-ai-gamestore) | **Tenenbaum, Griffiths, Isola**: Human Gamesで汎用知能評価 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🤖 GNN-MPC (Stanford)](papers/2026-02-21-gnn-mpc) | **Marco Pavone**: 1000ノード100Hz制御、実ソフトロボット検証 |
| [🚗 Deep-Flow](papers/2026-02-21-deep-flow-av) | Waymoデータ、L4自動運転異常検出、安全性検証基盤 |

---

## 2026-02-21 注目論文：ICLR2026複数採択＆GUI-Owl-1.5（Alibaba）20+ベンチマークSOTA＆Eコマース検索本番A/Bテスト

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🧬 RankEvolve](papers/2602.16932) | AlphaEvolve手法で検索アルゴリズム自動発見、BM25を超える進化的探索、BEIR/BRIGHT評価 |
| [🌐 WebFAQ 2.0](papers/2602.17327) | **1.98億QAペア、108言語**、ハードネガティブ公開、**GitHub/HuggingFace公開** |
| [🛒 Mine and Refine](papers/2602.17654) | Eコマース検索の段階的関連性最適化、**本番A/Bテスト**で有意なビジネスインパクト |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [⚖️ References for Alignment (ICLR 2026)](papers/2602.16802) | **ICLR 2026採択**: 非検証可能ドメインへのRL拡張、参照ガイド型自己改善 |
| [👤 Persona2Web](papers/2602.17003) | **初のパーソナライズWebエージェントベンチマーク**、ユーザー履歴から曖昧性解決、GitHub公開 |
| [🔥 Arcee Trinity Large](papers/2602.17004) | **400B MoE、17兆トークン学習**、SMEBU新手法、ロススパイクなし、HuggingFace公開 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [🔐 Sign Lock-In](papers/2602.17063) | サブビット圧縮の理論的基盤、符号ビットボトルネックを形式化、実用的正則化手法 |
| [⚔️ M-Attack-V2](papers/2602.17645) | **GPT-5で100%、Claude-4.0で30%**成功率、フロンティアLVLM攻撃、GitHub公開 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [📡 Multimodal Gaussian Splatting](papers/2602.17124) | **RF+ビジョン融合**3DGS、悪天候・遮蔽に強い自動運転向け |
| [🔍 SpectralGCD (ICLR 2026)](papers/2602.17395) | **ICLR 2026採択**: 効率的マルチモーダルGCD、計算コスト大幅削減、GitHub公開 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [📱 GUI-Owl-1.5 (Alibaba)](papers/2602.16855) | **Alibaba**: 2B-235Bモデル群、**20+ベンチマークSOTA**、OSWorld 56.5、GitHub公開 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🤖 MALLVi](papers/2602.16898) | マルチエージェントLLM+VLMでクローズドループ制御、ゼロショット汎化、GitHub公開 |
| [🚗 Deep-Flow](papers/2602.17586) | **Waymoデータセット**でL4 AV異常検出、フローマッチングで安全性検証 |

---

## 2026-02-20 注目論文：WWW'26 Retrieval Collapse＆ICLR2026多数採択＆EgoScale人間→ロボットスケーリング則

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [⚠️ Retrieval Collapse (WWW '26)](papers/2602.16136-retrieval-collapse-www26) | **WWW '26採択**: AI生成コンテンツでWeb検索崩壊、67%汚染→80%+露出汚染 |
| [🔗 FeDecider (WWW '26)](papers/2602.16034-fedecider-www26) | **WWW '26採択**: LLM×Federated CDR、UIUC Hanghang Tong、プライバシー保護クロスドメイン推薦 |
| [🚀 MFLI](papers/2602.16124-mfli-retrieval) | ANNサーチ不要の新パラダイム、**数十億ユーザー本番稼働**、コールドコンテンツ+57%向上 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🌐 Align Once (ICLR 2026)](papers/2602.16660-align-once-iclr26) | **ICLR 2026採択**: 単一更新で多言語LLM安全アライメント、リソース効率的 |
| [🤝 Team of Thoughts](papers/2602.16485-team-of-thoughts) | 異種マルチエージェント協調、**AIME24で96.67%**、LiveCodeBench 72.53% |
| [🔍 ColBERT-Zero](papers/2602.16609-colbert-zero) | 公開データのみでColBERT SOTA達成、GTE-ModernColBERT超え、**コード公開** |
| [⚖️ Calibrate-Then-Act](papers/2602.16699-calibrate-then-act) | LLMエージェントのコスト-不確実性トレードオフ最適化、UT Austin Greg Durrett |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [🏆 Neural Collapse Optimizer (ICLR 2026)](papers/2602.16642-neural-collapse-optimizer-iclr26) | **ICLR 2026採択**: NCはオプティマイザー依存と証明、AdamW decoupled WDでは発生不可能 |
| [📊 Agent Reliability (Princeton)](papers/2602.16666-agent-reliability-princeton) | **Arvind Narayanan**: 能力向上≠信頼性向上、4次元12指標で評価フレームワーク提案 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🎯 Category Splitting (ICLR 2026)](papers/2602.16545-category-splitting-iclr26) | **ICLR 2026採択**: ゼロショットで分類器を細分化、追加データ不要 |
| [👁️ SAW-Bench](papers/2602.16682-saw-bench-situated-awareness) | 実世界エゴ視点ベンチマーク、**Stanford Jiajun Wu**、最良MFMでも人間と37.66%ギャップ |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [📊 Agent Reliability (Princeton)](papers/2602.16666-agent-reliability-princeton) | **Arvind Narayanan**: AIエージェント信頼性の科学、14モデル評価で能力≠信頼性を実証 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [📈 EgoScale](papers/2602.16710-egoscale-dexterous) | **20,854時間**人間動画でVLA訓練、対数線形スケーリング則発見、22DoFハンド54%向上 |
| [🤖 HERO](papers/2602.16705-hero-humanoid) | ヒューマノイドOpen-vocabularyロコマニピュレーション、EE誤差3.2x削減、実環境で多様な物体操作 |

---

## 2026-02-19 注目論文：清華GLM-5 Agentic Engineering＆Berkeley Humanoid Parkour＆ICLR2026リテンション最適化

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🔄 RSIR](papers/2602.15659-rsir) | 自己改善推薦フレームワーク、外部データ不要で累積改善、**GitHub公開** |
| [🎬 Funny Scene Extraction (AAAI 2026)](papers/2602.15381-funny-scene-extraction) | **AAAI 2026採択**: 映画からユーモアシーン自動抽出、AP +18.3%、87%精度 |
| [📄 IDC Chunking](papers/2602.14784-intent-driven-chunking) | Intent駆動動的チャンキング、Top-1検索5-67%向上、**GitHub公開** |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🚀 GLM-5 (清華)](papers/2602.15763-glm5) | **清華大学**: Agentic Engineering、非同期RLインフラ、実世界コーディングSOTA、**GitHub公開** |
| [⚡ STAPO](papers/2602.15620-stapo) | LLM RL安定化、Spurious Tokens（0.01%）を特定しマスク、GRPO比+7.13% |
| [📊 SquRL Text-to-SQL](papers/2602.15564-dynamic-text2sql) | 動的ワークフロー構築RL、静的手法を一貫して上回る、**GitHub公開** |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [🏃 Humanoid Parkour (Berkeley)](papers/2602.15827-humanoid-parkour) | **Pieter Abbeel, C. Karen Liu**: Motion matchingでパルクール、1.25m障害物登攀、Unitree G1実機 |
| [🏆 MRet Retention (ICLR 2026)](papers/2602.15752-retention-matching) | **ICLR 2026採択**: マッチングでリテンション最大化、従来のマッチ数/公平性最適化を超越 |
| [🏆 FGE Reachability (MIT, ICLR 2026)](papers/2602.15817-fge-reachability) | **MIT Chuchu Fan, ICLR 2026**: 安全RL、実行可能性未知でもロバスト、カバレッジ+50% |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🏆 R3 Multimodal (Microsoft, ICLR 2026)](papers/2602.15772-r3-multimodal) | **Microsoft Han Hu, ICLR 2026**: 理解vs生成のジレンマ解消、Reason-Reflect-Refine、**GitHub公開** |
| [🎨 LoRWeB (NVIDIA)](papers/2602.15727-lorweb) | **NVIDIA Rinon Gal**: LoRA基底で視覚アナロジー、推論時動的合成、汎化大幅向上 |
| [✏️ VideoSketcher (MIT)](papers/2602.15819-videosketcher) | **MIT Torralba**: Video diffusionで順次スケッチ生成、7つの手描きスケッチから学習 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [🧠 RCE Reasoning](papers/2602.15725-rce-reasoning) | 推論中に表現幾何学を動的変更、ARC-AGI-2で12-18pt向上、GPQA/BBHで8-14pt向上 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🤖 Dex4D (CMU)](papers/2602.15828-dex4d) | **CMU Fragkiadaki/Tulsiani**: タスク非依存巧緻操作、Sim-to-Realゼロショット転移 |

---

## 2026-02-18 注目論文：ByteDance抖音MixFormer本番＆MIT PhyScensis ICLR2026＆Google BPP実世界+70%

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🏭 MixFormer (ByteDance)](papers/2026-02-17/mixformer-bytedance) | **抖音/Douyin Lite**: Transformer統合アーキ、Dense+Sequence Co-Scaling、**本番A/Bテスト実施** |
| [⚡ IDC Chunking](papers/2026-02-17/idc-chunking) | Intent駆動動的チャンキング、RAG検索精度5-67%向上、チャンク数40-60%削減、**GitHub公開** |
| [🏢 DeepMTL2R (Amazon)](papers/2026-02-17/deepmtl2r-amazon) | **Amazon Science**: MTLランキングライブラリ、21種SOTAアルゴリズム、**GitHub公開** |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🔬 BFS-PO](papers/2026-02-17/bfs-po-lrm) | LRM Overthinking解消、Best-First Search RL、**精度向上+回答短縮の両立** |
| [📊 Scaling Diffusion LLM](papers/2026-02-17/scaling-diffusion-llm) | 離散拡散LMの初スケーリング則、Masked diffusion神話を覆す、GSM8Kで自己回帰超え、**GitHub公開** |
| [🧠 Pep Cold-Start (Microsoft)](papers/2026-02-17/pep-cold-start) | **Microsoft Research**: Training-free嗜好推論、80.8%アライメント（RL 68.5%）、3-5倍少ない対話 |
| [📈 LLM4TSF](papers/2026-02-17/llm4tsf) | 「LLMは時系列に効かない」を覆す80億観測実証、クロスドメイン汎化で大効果、**GitHub公開** |
| [🔓 Overthinking MCP Attack](papers/2026-02-17/overthinking-mcp) | エージェントセキュリティ脆弱性、悪意あるMCPツールで最大142倍トークン増幅 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [🏆 Canonical Diffusion (MIT)](papers/2026-02-17/canonical-diffusion) | **Tommi Jaakkola**: 分子生成で正準化アプローチ、GEOM-DRUGでSOTA |
| [📐 Discrete Diffusion Theory](papers/2026-02-17/discrete-diffusion-theory) | 離散拡散サンプリングのシャープな理論保証、低次元構造への適応的収束 |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🎬 EditCtrl](papers/2026-02-17/editctrl-video) | ビデオ編集10倍高速化、Local+Global制御分離、マルチリージョン編集 |
| [🔮 Sphere Encoder (Maryland)](papers/2026-02-17/sphere-encoder) | **Tom Goldstein**: シングルパス画像生成、5ステップ未満で拡散モデル品質 |
| [🏢 CAPA (NVIDIA)](papers/2026-02-17/capa-nvidia) | **NVIDIA**: テストタイム適応で深度補完、LoRA/VPTで3D基盤モデル活用 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [🏆 PhyScensis (MIT, ICLR 2026)](papers/2026-02-17/physcensis-iclr) | **ICLR 2026採択**: LLMエージェント×物理エンジン、複雑シーン自動配置 |
| [🏆 MAC-AMP (ICLR 2026)](papers/2026-02-17/mac-amp-iclr) | **ICLR 2026採択**: マルチエージェント抗菌ペプチド設計、閉ループ最適化 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🎯 BPP (Google/CMU)](papers/2026-02-17/bpp-google-imitation) | **Google DeepMind**: VLMキーフレーム選択、実世界で**成功率+70%** |
| [🤖 DM0 VLA](papers/2026-02-17/dm0-vla) | Embodied-Native VLAフレームワーク、RoboChallengeでSOTA、**GitHub公開** |

---

## 2026-02-17 注目論文：Kuaishou休眠ユーザー活性化+7.3%＆LinkedIn Feed-SR本番＆Berkeley VLA階層制御

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🏭 RoleGen (Kuaishou)](papers/2026-02-16/rolegen-kuaishou) | **快手Eコマース**: 休眠ユーザー活性化、LLMでFunctional Role推論、**注文+7.3%** |
| [🏭 Feed-SR (LinkedIn)](papers/2026-02-16/feed-sr-linkedin) | **LinkedIn**: Transformerベース逐次推薦、DCNv2置換、**滞在時間+2.10%** |
| [🏭 RGAlign-Rec (Shopee)](papers/2026-02-16/rgalign-rec-shopee) | **Shopee**: ゼロクエリ推薦、LLM+ランキング統合、CTR+0.98% |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🔬 SciAgentGym](papers/2026-02-16/sciagentgym) | 科学ツール使用ベンチマーク、1,780ドメイン特化ツール、GPT-5も長期で60%→31%低下 |
| [⚡ DiffuRank](papers/2026-02-16/diffurank) | 拡散LLMでリランキング、並列デコーディング可能、**GitHub公開** |
| [📊 SCOPE](papers/2026-02-16/scope-llm-judge) | LLM-as-Judgeに統計保証、Conformal Predictionでエラー率制御 |
| [🌡️ Introspective LLM](papers/2026-02-16/introspective-llm) | 隠れ状態から温度を動的学習、階層RLで探索-活用を最適化 |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [🔄 R-Diverse](papers/2026-02-16/r-diverse) | Self-Playの「多様性幻想」を解決、Memory-Augmented Penalty、**GitHub公開** |
| [🏆 TCMax (ICLR 2026)](papers/2026-02-16/tcmax-iclr) | **ICLR 2026採択**: Total Correlation最大化でモダリティ競合を解消、**GitHub公開** |
| [⚡ FlashSchNet](papers/2026-02-16/flashschnet) | IO-awareでGNN分子動力学を6.5倍高速化、古典力場超え精度、**GitHub公開** |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🏆 FEM (AAAI 2026)](papers/2026-02-16/fem-aaai) | **AAAI 2026採択**: 顔埋め込みからリアル画像を再構成、PPFR攻撃に成功 |
| [📍 LongStream](papers/2026-02-16/longstream) | キロメートル級長系列3D再構成、18 FPS、ゲージ分離でドリフト解消 |
| [🎬 CoPE-VideoLM](papers/2026-02-16/cope-videolm) | ビデオコーデックでVideoLM効率化、TTFT 86%削減、トークン93%削減 |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [🛡️ Reasoning Robustness (CMU)](papers/2026-02-16/reasoning-robustness) | 推論モデルの敵対攻撃ロバスト性、5失敗モード特定、CARG防御は失敗 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🎯 Steerable Policies (Berkeley)](papers/2026-02-16/steerable-policies-berkeley) | **Sergey Levine**: VLAを複数抽象度で制御、VLM事前知識を引き出す |
| [🏆 SafeFlowMPC (ICRA 2026)](papers/2026-02-16/safeflowmpc-icra) | **ICRA 2026採択**: Flow Matching+MPC、安全保証付きリアルタイム制御、**GitHub公開** |

---

## 2026-02-16 注目論文：LASER小紅書1億DAU運用＆LDA-1B北大×NVIDIAロボット基盤モデル＆ICLR2026教育的蒸留

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🏭 LASER (Xiaohongshu)](papers/2026-02-15/laser-xiaohongshu) | **小紅書(RedNote)**: 長系列推薦、1億DAUデプロイ、ADVV+2.36%、収益+2.08% |
| [🏆 EpicCBR (WSDM 2026)](papers/2026-02-15/epiccbr-wsdm) | **WSDM 2026採択**: コールドスタートバンドル推薦、最大387%改善 |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🏢 OPCD (Microsoft)](papers/2026-02-15/opcd-microsoft) | On-Policyコンテキスト蒸留、プロンプト内在化、クロスサイズ蒸留 |
| [🏆 IOA (ICLR 2026)](papers/2026-02-15/ioa-iclr) | **ICLR 2026採択**: 教育原理でLLM蒸留、教師性能の94.7%達成（1/10パラメータ） |
| [⚡ dVoting](papers/2026-02-15/dvoting-dllm) | Diffusion LLM高速投票、GSM8K +7.66%、**GitHub公開** |
| [📐 T3D](papers/2026-02-15/t3d-dllm) | 少ステップDiffusion LLM、軌跡自己蒸留、**GitHub公開** |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [🏫 Olmix (Stanford/AI2)](papers/2026-02-15/olmix-stanford) | LMデータ混合フレームワーク、74%計算削減で同等性能、下流+11.6% |
| [🧮 Categorical Flow Maps](papers/2026-02-15/categorical-flow-maps) | **Welling & Bronstein**: 少ステップ離散生成、画像/分子/テキストSOTA |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🎬 MonarchRT (CMU)](papers/2026-02-15/monarchrt-video) | **史上初**: RTX 5090で16FPSリアルタイム動画生成、95%スパース化 |
| [🧠 UniT (Meta/Stanford)](papers/2026-02-15/unit-meta) | マルチモーダルCoTテストタイムスケーリング、短軌跡→長推論汎化 |
| [🏆 AssetFormer (ICLR 2026)](papers/2026-02-15/assetformer-iclr) | **ICLR 2026採択**: モジュラー3D生成、UGC向け、**GitHub公開** |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [🛠️ CM2](papers/2026-02-15/cm2-tool-agent) | チェックリスト報酬でツールエージェントRL、τ-Bench +8pt、**GitHub公開** |
| [⚡ CATTS (Berkeley)](papers/2026-02-15/catts-berkeley) | Webエージェントテストタイムスケーリング、2.3倍トークン削減 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [✅ CoVer (Stanford)](papers/2026-02-15/cover-stanford) | **Finn & Pavone**: VLA検証、実世界+45%、テストタイムスケーリング |
| [🏫 LDA-1B (PKU/NVIDIA)](papers/2026-02-15/lda-1b-pku) | **北大×NVIDIA**: 1Bロボット基盤モデル、30k時間データ、π₀.₅比+48% |

---

## 2026-02-15 注目論文：Bilibili推薦本番運用＆MonarchRTリアルタイム動画生成＆VLA検証テストタイムスケーリング

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🏭 MLCC (Bilibili)](papers/mlcc-bilibili-rec-scaling-0215) | **Bilibili**: CTR/CVRスケーリング、パラメータ26倍削減、**deployed** |
| [🔍 AttentionRetriever](papers/attention-retriever-long-doc-0215) | Attention機構で長文書検索、context-aware埋め込み |
| [🎯 SAGEO Arena](papers/sageo-arena-benchmark-0215) | Search-Augmented GEO評価環境、SEO+GEO統合ベンチマーク |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [📚 OPCD](papers/opcd-context-distillation-0215) | On-Policy文脈蒸留、プロンプト知識をモデルに内在化 |
| [⚡ T3D](papers/t3d-few-step-diffusion-llm-0215) | 少ステップDiffusion LLM、軌跡自己蒸留、**GitHub公開** |
| [🎙️ Moonshine v2](papers/moonshine-v2-streaming-asr-0215) | ストリーミングASR、6倍大モデルと同等精度、エッジ向け |
| [🎲 dVoting](papers/dvoting-diffusion-llm-0215) | Diffusion LLM高速投票、GSM8K +7.66%、**GitHub公開** |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [🌍 Fun-DDPS](papers/fun-ddps-ccs-modeling-0215) | CO2貯留モデリング、25%観測で7.7%誤差、11倍改善 |
| [📈 FGNO](papers/fgno-ssl-timeseries-0215) | 時系列SSL、フローマッチング＋ニューラルオペレータ、AUROC +35% |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🎬 MonarchRT](papers/monarchrt-realtime-video-0215) | **RTX 5090で16FPSリアルタイム動画生成**、95%スパース化 |
| [🧠 UniT](papers/unit-multimodal-cot-tts-0215) | マルチモーダルCoTテストタイムスケーリング、短軌跡→長推論汎化 |
| [🔄 UniDFlow](papers/unidfow-multimodal-flow-0215) | 統一Discrete Flow-Matching、8ベンチマークSOTA |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [⚡ CATTS](papers/catts-webagent-tts-0215) | Webエージェントテストタイムスケーリング、2.3倍トークン削減 |
| [🛠️ CM2](papers/cm2-rl-tool-agent-0215) | チェックリスト報酬でツールエージェントRL、**GitHub公開** |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [✅ CoVer](papers/cover-vla-verification-0215) | VLA検証器、実世界+45%、テストタイムスケーリングでポリシー改善 |
| [🏠 AHAT](papers/ahat-household-planning-0215) | 家庭内長期ホライズンプランニング、PDDL＋LLM、曖昧指示対応 |

---

## 2026-02-14 注目論文：Meituan基盤モデル＆DiffusionRank＆MolmoSpaces大規模ロボットベンチマーク

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🏪 MTFM (Meituan)](papers/mtfm-meituan-recsys-0214) | **Meituan**: マルチシナリオ推薦基盤モデル、アライメント不要設計、**deployed** |
| [🎲 DiffusionRank](papers/diffusionrank-ltr-0214) | 拡散モデルでLTR、生成的アプローチで識別的手法を大幅に上回る |
| [🔬 Analytical Search](papers/analytical-search-0214) | 次世代検索パラダイム提案、分析的情報ニーズに対応した証拠ベースワークフロー |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🎯 MuRGAt](papers/murgat-multimodal-attribution-0214) | マルチモーダル事実レベル帰属ベンチマーク、MLLMの引用幻覚を発見、**GitHub公開** |
| [⚡ HybridRAG](papers/hybridrag-practical-framework-0214) | 事前Q&A生成RAG、低レイテンシ＋高品質、実用的チャットボット向け |
| [📐 Sparse Semantic Dimension](papers/sparse-semantic-dimension-0214) | LLM汎化の新理論、スパース性が容量を決定、**GitHub公開** |
| [🧭 Direction vs Magnitude](papers/direction-magnitude-transformer-0214) | Transformer表現の方向・大きさ分離、**ICML 2026投稿** |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [📊 Linear Representation Capacity](papers/linear-representation-capacity-0214) | 線形表現仮説の数学的フレームワーク、スーパーポジション仮説の理論的根拠 |
| [🔄 RL Rewriting Agent](papers/rl-rewriting-agent-sft-0214) | 分布ミスマッチ解消、破滅的忘却12.34%削減、**GitHub公開** |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🤖 ABot-M0](papers/abot-m0-manipulation-0214) | ロボット操作VLA基盤モデル、600万軌跡、Action Manifold Learning、**GitHub公開** |
| [🔍 Zooming without Zooming](papers/zooming-without-zooming-0214) | 領域蒸留できめ細かい知覚、ツール呼び出し不要、ZoomBench新規、**GitHub公開** |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [⚖️ Ground Truth Illusion](papers/ground-truth-illusion-0214) | データアノテーションの主観性、346論文サーベイ、多元的アノテーション提唱 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🏠 MolmoSpaces](papers/molmospaces-robot-benchmark-0214) | **Dieter Fox**: 23万環境、4,200万把持、sim-to-real R=0.96、完全オープン |
| [🧭 ABot-N0](papers/abot-n0-navigation-0214) | ナビゲーション5タスク統一、1,690万軌跡、7ベンチマークSOTA |

---

## 2026-02-12 注目論文：Taobao CTR Scaling＆ECIR'26 LLMバイアス＆AAAI'26 コールドスタート

### 📚 cs.IR（情報検索）

| 論文 | 一言 |
|------|------|
| [🎯 EST (Taobao)](papers/est-taobao-ctr-scaling-0212) | **Alibaba**: CTRスケーリング則、RPM+3.27%、CTR+1.22%、**deployed** |
| [🔍 Source Bias](papers/dense-retrieval-llm-bias-0212) | **ECIR 2026**: Dense RetrieverのLLMバイアスは訓練誘発、MS MARCOで発生 |
| [💎 S-GRec](papers/sgrec-semantic-generative-rec-0212) | LLM意味Judge＋A2PO最適化、GMV+1.19%、リアルタイム推論なし、**deployed** |

### 🗣️ cs.CL（自然言語処理・LLM）

| 論文 | 一言 |
|------|------|
| [🎙️ Hibiki-Zero](papers/hibiki-zero-s2s-translation-0212) | アラインメント不要S2S翻訳、GRPO強化学習、5言語SOTA、**GitHub公開** |
| [🍳 DataChef](papers/datachef-llm-data-recipe-0212) | データレシピ自動生成、AIME'25で66.7（Qwen3-1.7B超え） |
| [🔎 SoftMatcha 2](papers/softmatcha2-trillion-search-0212) | 1兆トークン0.3秒検索、ベンチマーク汚染検出、**GitHub・デモ公開** |

### 🧠 cs.LG（機械学習）

| 論文 | 一言 |
|------|------|
| [📊 pplx-embed](papers/pplx-embed-diffusion-0212) | **Perplexity AI**: Diffusion事前訓練埋め込み、ConTEB**新記録** |
| [❄️ MoToRec](papers/motorec-coldstart-aaai2026-0212) | **AAAI 2026**: スパースRQ-VAEでコールドスタート解決、3データセットSOTA |

### 👁️ cs.CV（コンピュータビジョン）

| 論文 | 一言 |
|------|------|
| [🎨 DiNa-LRM](papers/dina-lrm-diffusion-reward-0212) | Diffusionネイティブ報酬モデル、VLMの数分の1コストで同等性能、**GitHub公開** |
| [🏗️ LaSSM](papers/lassm-3d-instance-seg-0212) | **IEEE-TCSVT**: SSMで3Dセグメント、ScanNet++ V2**1位**、1/3 FLOPs、**GitHub公開** |

### 🤖 cs.AI（AI全般）

| 論文 | 一言 |
|------|------|
| [⚖️ FormalJudge](papers/formaljudge-neuro-symbolic-0212) | LLM-as-Judgeに形式検証、7Bが72B欺瞞を90%超検出、Dafny+Z3 |

### 🦾 cs.RO（ロボティクス）

| 論文 | 一言 |
|------|------|
| [🤖 YOR](papers/yor-mobile-manipulator-0212) | **Soumith Chintala (Meta)**: $10K未満モバイルマニピュレータ、オープンソース |
| [🎯 NF-HIQL](papers/nf-hiql-icra2026-0212) | **ICRA 2026**: Normalizing Flow階層RL、データ効率・汎化両立 |

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
