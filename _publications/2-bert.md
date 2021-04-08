---
title: "On the sentence embeddings from pre-trained language models"
collection: publications
permalink: /publication/2020/11/2-bert
excerpt: 'Bohan Li, Hao Zhou, Junxian He, Mingxuan Wang, Yiming Yang, Lei Li'
date: 2020/11/2
venue: 'EMNLP'
paperurl: 'https://arxiv.org/abs/2011.05864'
---
**Abstract** <br>
Pre-trained contextual representations like BERT have achieved great success in natural language processing. However, the sentence embeddings from the pre-trained language models without fine-tuning have been found to poorly capture semantic meaning of sentences. In this paper, we argue that the semantic information in the BERT embeddings is not fully exploited. We first reveal the theoretical connection between the masked language model pre-training objective and the semantic similarity task theoretically, and then analyze the BERT sentence embeddings empirically. We find that BERT always induces a non-smooth anisotropic semantic space of sentences, which harms its performance of semantic similarity. To address this issue, we propose to transform the anisotropic sentence embedding distribution to a smooth and isotropic Gaussian distribution through normalizing flows that are learned with an unsupervised objective. Experimental results show that our proposed BERT-flow method obtains significant performance gains over the state-of-the-art sentence embeddings on a variety of semantic textual similarity tasks. The code is available at this https URL.
[[paper]](https://arxiv.org/abs/2009.09704) [[code]](https://github.com/dqqcasia/neurst)

Please cite as:
```bibtex
@article{li2020sentence,
  title={On the sentence embeddings from pre-trained language models},
  author={Li, Bohan and Zhou, Hao and He, Junxian and Wang, Mingxuan and Yang, Yiming and Li, Lei},
  journal={arXiv preprint arXiv:2011.05864},
  year={2020}
}
```