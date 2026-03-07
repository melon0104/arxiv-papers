# ThaiSafetyBench: Assessing Language Model Safety in Thai Cultural Contexts

**arXiv ID**: [2603.04992](https://arxiv.org/abs/2603.04992)

**カテゴリ**: cs.CL (自然言語処理 (NLP))

**著者**: Trapoom Ukarapol, Nut Chukamphaeng, Kunat Pipatanakul, Pakhapoom Sarapat

**投稿日**: 2026-03-05

---

## 概要

The safety evaluation of large language models (LLMs) remains largely centered on English, leaving non-English languages and culturally grounded risks underexplored. In this work, we investigate LLM safety in the context of the Thai language and culture and introduce ThaiSafetyBench, an open-source benchmark comprising 1,954 malicious prompts written in Thai. The dataset covers both general harmful prompts and attacks that are explicitly grounded in Thai cultural, social, and contextual nuances.   Using ThaiSafetyBench, we evaluate 24 LLMs, with GPT-4.1 and Gemini-2.5-Pro serving as LLM-as-a-judge evaluators. Our results show that closed-source models generally demonstrate stronger safety performance than open-source counterparts, raising important concerns regarding the robustness of openly available models. Moreover, we observe a consistently higher Attack Success Rate (ASR) for Thai-specific, culturally contextualized attacks compared to general Thai-language attacks, highlighting a critical vulnerability in current safety alignment methods.   To improve reproducibility and cost efficiency, we further fine-tune a DeBERTa-based harmful response classifier, which we name ThaiSafetyClassifier. The model achieves a weighted F1 score of 84.4%, matching GPT-4.1 judgments. We publicly release the fine-tuning weights and training scripts to support reproducibility. Finally, we introduce the ThaiSafetyBench leaderboard to provide continuously updated safety evaluations and encourage community participation.   - ThaiSafetyBench HuggingFace Dataset: https://huggingface.co/datasets/typhoon-ai/ThaiSafetyBench   - ThaiSafetyBench Github: https://github.com/trapoom555/ThaiSafetyBench   - ThaiSafetyClassifier HuggingFace Model: https://huggingface.co/typhoon-ai/ThaiSafetyClassifier   - ThaiSafetyBench Leaderboard: https://huggingface.co/spaces/typhoon-ai/ThaiSafetyBench-Leaderboard

---

## コメント

ICLR 2026 Workshop on Principled Design for Trustworthy AI

---

**リンク**: https://arxiv.org/abs/2603.04992
