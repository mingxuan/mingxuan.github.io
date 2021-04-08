---
title: "Deep semantic role labeling with self-attention"
collection: publications
permalink: /publication/2018/4/srl
excerpt: 'Zhixing Tan, Mingxuan Wang, Jun Xie, Yidong Chen, Xiaodong Shi'
date: 2018/4/26
venue: 'AAAI'
paperurl: 'https://ojs.aaai.org/index.php/AAAI/article/view/11928'
---
**Abstract** <br>
Semantic Role Labeling (SRL) is believed to be a crucial step towards natural language understanding and has been widely studied. Recent years, end-to-end SRL with recurrent neural networks (RNN) has gained increasing attention. However, it remains a major challenge for RNNs to handle structural information and long range dependencies. In this paper, we present a simple and effective architecture for SRL which aims to address these problems. Our model is based on self-attention which can directly capture the relationships between two tokens regardless of their distance. Our single model achieves F1= 83.4 on the CoNLL-2005 shared task dataset and F1= 82.7 on the CoNLL-2012 shared task dataset, which outperforms the previous state-of-the-art results by 1.8 and 1.0 F1 score respectively. Besides, our model is computationally efficient, and the parsing speed is 50K tokens per second on a single Titan X GPU.
Please cite as:
```bibtex
@inproceedings{tan2018deep,
  title={Deep semantic role labeling with self-attention},
  author={Tan, Zhixing and Wang, Mingxuan and Xie, Jun and Chen, Yidong and Shi, Xiaodong},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={32},
  number={1},
  year={2018}
}
```
