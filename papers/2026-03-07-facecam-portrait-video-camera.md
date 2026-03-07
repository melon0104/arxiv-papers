# FaceCam: Portrait Video Camera Control via Scale-Aware Conditioning

**arXiv ID**: [2603.05506](https://arxiv.org/abs/2603.05506)

**カテゴリ**: cs.CV (コンピュータビジョン (CV))

**著者**: Weijie Lyu, Ming-Hsuan Yang, Zhixin Shu

**投稿日**: 2026-03-05

---

## 概要

We introduce FaceCam, a system that generates video under customizable camera trajectories for monocular human portrait video input. Recent camera control approaches based on large video-generation models have shown promising progress but often exhibit geometric distortions and visual artifacts on portrait videos due to scale-ambiguous camera representations or 3D reconstruction errors. To overcome these limitations, we propose a face-tailored scale-aware representation for camera transformations that provides deterministic conditioning without relying on 3D priors. We train a video generation model on both multi-view studio captures and in-the-wild monocular videos, and introduce two camera-control data generation strategies: synthetic camera motion and multi-shot stitching, to exploit stationary training cameras while generalizing to dynamic, continuous camera trajectories at inference time. Experiments on Ava-256 dataset and diverse in-the-wild videos demonstrate that FaceCam achieves superior performance in camera controllability, visual quality, identity and motion preservation.

---

## コメント

Accepted by CVPR 2026. Project page: https://weijielyu.github.io/FaceCam

---

**リンク**: https://arxiv.org/abs/2603.05506
