---
title: "Memory-enhanced decoder for neural machine translation"
collection: publications
permalink: /publication/2016/6/mem
excerpt: 'Mingxuan Wang, Zhengdong Lu, Hang Li, Qun Liu'
date: 2016/6/7
venue: 'ACL'
paperurl: 'https://arxiv.org/abs/1606.02003'
---
**Abstract** <br>
We propose to enhance the RNN decoder in a neural machine translator (NMT) with external memory, as a natural but powerful extension to the state in the decoding RNN. This memory-enhanced RNN decoder is called\textsc {MemDec}. At each time during decoding,\textsc {MemDec} will read from this memory and write to this memory once, both with content-based addressing. Unlike the unbounded memory in previous work\cite {RNNsearch} to store the representation of source sentence, the memory in\textsc {MemDec} is a matrix with pre-determined size designed to better capture the information important for the decoding process at each time step. Our empirical study on Chinese-English translation shows that it can improve by  BLEU upon Groundhog and  BLEU upon on Moses, yielding the best performance achieved with the same training set.

Please cite as:
```bibtex
@article{wang2016memory,
  title={Memory-enhanced decoder for neural machine translation},
  author={Wang, Mingxuan and Lu, Zhengdong and Li, Hang and Liu, Qun},
  journal={arXiv preprint arXiv:1606.02003},
  year={2016}
}
```
