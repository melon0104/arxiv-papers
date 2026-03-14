# Neural Thickets: Diverse Task Experts Are Dense Around Pretrained Weights

- **arXiv**: https://arxiv.org/abs/2603.12228
- **PDF**: https://arxiv.org/pdf/2603.12228
- **GitHub**: https://github.com/sunrainyg/RandOpt
- **Categories**: cs.LG, cs.AI
- **Published**: 2026-03-12

## Authors
Yulu Gan, Phillip Isola (MIT CSAIL)

## Abstract
Pretraining produces a learned parameter vector that is typically treated as a **starting point** for further iterative adaptation. In this work, we instead view the outcome of pretraining as a **distribution over parameter vectors**, whose support already contains task-specific experts.

## Key Findings

### Small Models vs. Large Models
- **Small models**: Expert solutions occupy a negligible fraction of the volume, making their discovery reliant on structured optimization methods such as gradient descent
- **Large, well-pretrained models**: The **density of task-experts increases dramatically**, so that diverse experts can be found via simple random sampling in the local neighborhood

### Neural Thickets
We call this phenomenon **"Neural Thickets"** — regions around pretrained weights where task-expert solutions are densely packed.

## Implications
1. **Random search works**: For large pretrained models, random search in weight space can find task solutions
2. **Pretraining changes the loss landscape**: Creates dense regions of task-specific experts
3. **Model merging**: Explains why averaging models often works

## Experiments
- Demonstrates the phenomenon across model scales
- Shows correlation with model size and pretraining quality
- Provides theoretical analysis of the density increase

## Why Notable
- **MIT CSAIL**: Top AI research lab (Phillip Isola)
- **Novel perspective on pretraining**: Rethinks what pretrained weights represent
- **Practical implications**: Informs model merging and adaptation strategies
