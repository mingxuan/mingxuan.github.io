---
title: "LightSeq: A High Performance Inference Library for Sequence Processing and Generation"
collection: publications
permalink: /publication/2020/10/23-lightseq
excerpt: 'Xiaohui Wang, Ying Xiong, Yang Wei, Mingxuan Wang, Lei Li'
date: 2020/10/23
venue: 'NAACL'
paperurl: 'https://arxiv.org/abs/2010.13887'
---

**Abstract** <br>

Transformer and its variants have achieved great success in natural language processing. Since Transformer models are huge in size, serving these models is a challenge for real industrial applications. In this paper, we propose LightSeq, a highly efficient inference library for models in the Transformer family. LightSeq includes a series of GPU optimization techniques to both streamlining the computation of Transformer layers and reducing memory footprint. LightSeq supports models trained using PyTorch and Tensorflow. Experimental results on standard machine translation benchmarks show that LightSeq achieves up to 14x speedup compared with TensorFlow and 1.4x speedup compared with FasterTransformer, a concurrent CUDA implementation. The code has be released publicly in this https URL.

Please cite as:
```bibtex
@article{wang2020lightseq,
  title={LightSeq: A High Performance Inference Library for Sequence Processing and Generation},
  author={Wang, Xiaohui and Xiong, Ying and Wei, Yang and Wang, Mingxuan and Li, Lei},
  journal={arXiv preprint arXiv:2010.13887},
  year={2020}
}
```