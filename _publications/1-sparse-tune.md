---
title: "Finding Sparse Structure for Domain Specific Neural Machine Translation"
collection: publications
permalink: /publication/2020/12/1-sparse-tune
excerpt: 'Jianze Liang, Chengqi Zhao, Mingxuan Wang, Xipeng Qiu, Lei Li'
date: 2020/12/1
venue: 'AAAI'
paperurl: 'https://arxiv.org/abs/2012.10586'
---

***Abstract*** <br>
Fine-tuning is a major approach for domain adaptation in Neural Machine Translation (NMT). However, unconstrained fine-tuning requires very careful hyper-parameter tuning otherwise it is easy to fall into over-fitting on the target domain and degradation on the general domain. To mitigate it, we propose PRUNE-TUNE, a novel domain adaptation method via gradual pruning. It learns tiny domain-specific subnetworks for tuning. During adaptation to a new domain, we only tune its corresponding subnetwork. PRUNE-TUNE alleviates the over-fitting and the degradation problem without model modification. Additionally, with no overlapping between domain-specific subnetworks, PRUNE-TUNE is also capable of sequential multi-domain learning. Empirical experiment results show that PRUNE-TUNE outperforms several strong competitors in the target domain test set without the quality degradation of the general domain in both single and multiple domain settings.


Please cite as:
```bibtex
@article{gu2021pruning,
  title={Pruning-then-Expanding Model for Domain Adaptation of Neural Machine Translation},
  author={Gu, Shuhao and Feng, Yang and Xie, Wanying},
  journal={arXiv preprint arXiv:2103.13678},
  year={2021}
}
'''
