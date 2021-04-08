---
title: "Neural machine translation with decoding history enhanced attention"
collection: publications
permalink: /publication/2018/10/nmtenc
excerpt: 'Mingxuan Wang, Li Gong, Wenhuan Zhu, Jun Xie, Chao Bian'
date: 2018/8/5
venue: 'COLING'
paperurl: 'https://www.aclweb.org/anthology/C18-1124.pdf'
---
**Abstract** <br>

Neural machine translation with source-side attention have achieved remarkable performance. however, there has been little work exploring to attend to the target-side which can potentially enhance the memory capbility of NMT. We reformulate a Decoding History Enhanced Attention mechanism (DHEA) to render NMT model better at selecting both source-side and target-side information. DHA enables dynamic control of the ratios at which source and target contexts contribute to the generation of target words, offering a way to weakly induce structure relations among both source and target tokens. It also allows training errors to be directly back-propagated through short-cut connections and effectively alleviates the gradient vanishing problem. The empirical study on Chinese-English translation shows that our model with proper configuration can improve by 0: 9 BLEU upon Transformer and the best reported results in the dataset. On WMT14 English-German task and a larger WMT14 English-French task, our model achieves comparable results with the state-of-the-art.
Please cite as:
```bibtex
@inproceedings{wang2018neural,
  title={Neural machine translation with decoding history enhanced attention},
  author={Wang, Mingxuan and Xie, Jun and Tan, Zhixing and Su, Jinsong and Xiong, Deyi and Bian, Chao},
  booktitle={Proceedings of the 27th International Conference on Computational Linguistics},
  pages={1464--1473},
  year={2018}
}
```
