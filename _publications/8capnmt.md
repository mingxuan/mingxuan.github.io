---
title: "Towards linear time neural machine translation with capsule networks"
collection: publications
permalink: /publication/2020/11/1-caps
excerpt: 'Mingxuan Wang, Jun Xie, Zhixing Tan, Jinsong Su, Deyi Xiong, Lei Li'
date: 2018/11/1
venue: 'EMNLP'
paperurl: 'https://arxiv.org/abs/1811.00287'
---
**Abstract** <br>

In this study, we first investigate a novel capsule network with dynamic routing for linear time Neural Machine Translation (NMT), referred as\textsc {CapsNMT}.\textsc {CapsNMT} uses an aggregation mechanism to map the source sentence into a matrix with pre-determined size, and then applys a deep LSTM network to decode the target sequence from the source representation. Unlike the previous work\cite {sutskever2014sequence} to store the source sentence with a passive and bottom-up way, the dynamic routing policy encodes the source sentence with an iterative process to decide the credit attribution between nodes from lower and higher layers.\textsc {CapsNMT} has two core properties: it runs in time that is linear in the length of the sequences and provides a more flexible way to select, represent and aggregates the part-whole information of the source sentence. On WMT14 English-German task and a larger WMT14 English-French task,\textsc {CapsNMT} achieves comparable results with the state-of-the-art NMT systems. To the best of our knowledge, this is the first work that capsule networks have been empirically investigated for sequence to sequence problems.

Please cite as:
```bibtex
@article{wang2018towards,
  title={Towards linear time neural machine translation with capsule networks},
  author={Wang, Mingxuan and Xie, Jun and Tan, Zhixing and Su, Jinsong and Xiong, Deyi and Li, Lei},
  journal={arXiv preprint arXiv:1811.00287},
  year={2018}
}
```
