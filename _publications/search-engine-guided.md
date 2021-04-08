---
title: "Search Engine Guided Neural Machine Translation"
collection: publications
permalink: /publication/search-engine-guided
excerpt: '**Jiatao Gu**, Yong Wang, Kyunghyun Cho and Victor O.K. Li'
date: 2018-01-20
venue: 'The Thirty-Second AAAI Conference on Artificial Intelligence (AAAI).'
---

![png](/images/search-engine.png)<br>
**Abstract** <br>
In this paper, we extend an attention-based neural machine translation (NMT) model by allowing it to access an entire training set of parallel sentence pairs even after training. The proposed approach consists of two stages. In the first stage –retrieval stage–, an off-the-shelf, black-box search engine is used to retrieve a small subset of sentence pairs from a training set given a source sentence. These pairs are further filtered based on a fuzzy matching score based on edit distance. In the second stage –translation stage–, a novel translation model, called search engine guided NMT (SEG-NMT), seamlessly uses both the source sentence and a set of retrieved sentence pairs to perform the translation. Empirical evaluation on three language pairs (En-Fr, En-De, and En-Es) shows that the proposed approach significantly outperforms the baseline approach and the improvement is more significant when more relevant sentence pairs were retrieved.

[paper] [code]

Please cite as:
```bibtex

```