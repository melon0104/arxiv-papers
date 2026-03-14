# Linking Perception, Confidence and Accuracy in MLLMs

- **arXiv**: https://arxiv.org/abs/2603.12149
- **PDF**: https://arxiv.org/pdf/2603.12149
- **Categories**: cs.CV, cs.CL
- **Venue**: CVPR 2026 (Accepted)
- **Published**: 2026-03-12

## Authors
Yuetian Du, Yucheng Wang, Rongyu Zhang, Zhijie Xu, Boyu Yang, et al.

## Abstract
Recent advances in Multi-modal Large Language Models (MLLMs) have predominantly focused on enhancing visual perception to improve accuracy. However, a critical question remains unexplored: **Do models know when they do not know?**

Through a probing experiment, we reveal a **severe confidence miscalibration problem** in MLLMs.

## Confidence-Driven Reinforcement Learning (CDRL)
To address this, we propose **CDRL**, which:
- Uses **original-noise image pairs** for training
- Introduces a novel **confidence-based reward** to enhance perceptual sensitivity
- Robustly calibrates the model's confidence

## Key Benefits
Beyond training benefits, calibrated confidence enables:
- **Better uncertainty estimation** at inference time
- **Selective prediction**: Models can refuse to answer when uncertain
- **Improved trustworthiness** in safety-critical applications

## Results
- Improved calibration across multiple MLLM architectures
- Maintains or improves accuracy while gaining calibration
- Better out-of-distribution detection

## Why Notable
- **CVPR 2026 accepted**: Top computer vision venue
- **Addresses calibration in MLLMs**: Critical but understudied problem
- **Novel CDRL method**: Practical approach using RL for calibration
