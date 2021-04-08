---
title: "Imitation learning for non-autoregressive neural machine translation"
collection: publications
permalink: /publication/2019/6/5inat
excerpt: 'Bingzhen Wei, Mingxuan Wang, Hao Zhou, Junyang Lin, Jun Xie, Xu Sun'
date: 2019/6/5
venue: 'EMNLP'
paperurl: 'https://arxiv.org/abs/1906.02041'
---
**Abstract** <br>
Non-autoregressive translation models (NAT) have achieved impressive inference speedup. A potential issue of the existing NAT algorithms, however, is that the decoding is conducted in parallel, without directly considering previous context. In this paper, we propose an imitation learning framework for non-autoregressive machine translation, which still enjoys the fast translation speed but gives comparable translation performance compared to its auto-regressive counterpart. We conduct experiments on the IWSLT16, WMT14 and WMT16 datasets. Our proposed model achieves a significant speedup over the autoregressive models, while keeping the translation quality comparable to the autoregressive models. By sampling sentence length in parallel at inference time, we achieve the performance of 31.85 BLEU on WMT16 Ro  En and 30.68 BLEU on IWSLT16 En-De.

Please cite as:
```bibtex
@article{wei2019imitation,
  title={Imitation learning for non-autoregressive neural machine translation},
  author={Wei, Bingzhen and Wang, Mingxuan and Zhou, Hao and Lin, Junyang and Xie, Jun and Sun, Xu},
  journal={arXiv preprint arXiv:1906.02041},
  year={2019}
}
```
