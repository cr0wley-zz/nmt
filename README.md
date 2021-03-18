# Under the hood of Attention
- [Devjyoti Chakraborty](https://twitter.com/Cr0wley_zz)
- [Aritra Roy Gosthipaty](https://twitter.com/arig23498)

# Introduction

![Attention GIF](https://github.com/cr0wley-zz/nmt/tree/main/assets/att.gif?raw=true)

This repository houses the code for a five part series on **Attention** hosted by [Weights and Biases](https://wandb.ai/). The contents we will be covering are as follows:
- [Part I](https://wandb.ai/authors/under-attention/reports/Under-the-hood-of-attention--Vmlldzo1MzQwMTU): The intuition behind attention with Neural Machine Translation (NMT) in mind.
- [Part II](https://wandb.ai/authors/under-attention/reports/Neural-Machine-Translation-by-Jointly-Learning-to-Align-and-Translate--Vmlldzo1MzQwMTY): A review of Neural Machine Translation by Jointly Learning to Align and Translate by Bahadanu et. al.
- [Part III](https://wandb.ai/authors/under-attention/reports/Effective-Approaches-to-Attention-based-Neural-Machine-Translation--Vmlldzo1MzQwMjA): A review of Effective Approaches to Attention-based Neural Machine Translation by Luong et. al.
- [Part IV](https://wandb.ai/authors/under-attention/reports/Ablations-on-NMT-with-attention---Vmlldzo1MzQwMjQ): An ablation study to compare the different attention mechanisms for NMT.
- [Part V](https://wandb.ai/authors/under-attention/reports/Show-Attend-and-Tell--Vmlldzo1MzQwMjc): A review of Show, Attend and Tell: Neural Image Caption Generation with Visual Attention by Xu et. al.

# Directory

- **Bahdanau**
    - `baseline.ipynb`: Bahdanau baseline model, with bi-directional GRU and concat layers.
    - Ablations
        - `bidirectional_with_sum.ipynb`: Bahdanau model, with sum layers.
        - `unidirection.ipynb`: Bahdanau model, with unidirectional GRU.
- **Luong**
    - `baseline.ipynb`: Luong baseline model with global attention.
    - Ablations
        - `local_mono.ipynb`: Luong model with local monotonic attention.
        - `local_predictive.ipynb`: Luong model with local predictive attention.
