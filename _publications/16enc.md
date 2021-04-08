---
title: "Encoding source language with convolutional neural network for machine translation"
collection: publications
permalink: /publication/2015/3/enc
excerpt: 'Fandong Meng, Zhengdong Lu, Mingxuan Wang, Hang Li, Wenbin Jiang, Qun Liu
date: 2015/3/6
venue: 'ACL'
paperurl: 'https://arxiv.org/abs/1503.01838'
---
**Abstract** <br>
The recently proposed neural network joint model (NNJM)(Devlin et al., 2014) augments the n-gram target language model with a heuristically chosen source context window, achieving state-of-the-art performance in SMT. In this paper, we give a more systematic treatment by summarizing the relevant source information through a convolutional architecture guided by the target information. With different guiding signals during decoding, our specifically designed convolution+ gating architectures can pinpoint the parts of a source sentence that are relevant to predicting a target word, and fuse them with the context of entire source sentence to form a unified representation. This representation, together with target language words, are fed to a deep neural network (DNN) to form a stronger NNJM. Experiments on two NIST Chinese-English translation tasks show that the proposed model can achieve significant improvements over the previous NNJM by up to+ 1.08 BLEU points on average

Please cite as:
```bibtex
@article{meng2015encoding,
  title={Encoding source language with convolutional neural network for machine translation},
  author={Meng, Fandong and Lu, Zhengdong and Wang, Mingxuan and Li, Hang and Jiang, Wenbin and Liu, Qun},
  journal={arXiv preprint arXiv:1503.01838},
  year={2015}
}
```
