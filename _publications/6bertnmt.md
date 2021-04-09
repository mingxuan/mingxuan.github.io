---
title: "Towards Making the Most of BERT in Neural Machine Translation"
collection: publications
permalink: /publication/2020/bertnmt
excerpt: 'Jiacheng Yang Mingxuan Wang Hao Zhou, Chengqi Zhao, Weinan Zhang, Yong Yu, Lei Li'
date: 2020/7/2
venue: 'AAAI'
paperurl: 'https://ojs.aaai.org/index.php/AAAI/article/view/6479'
---
**Abstract** <br>
GPT-2 and BERT demonstrate the effectiveness of using pre-trained language models (LMs) on various natural language processing tasks. However, LM fine-tuning often suffers from catastrophic forgetting when applied to resource-rich tasks. In this work, we introduce a concerted training framework (CTnmt) that is the key to integrate the pre-trained LMs to neural machine translation (NMT). Our proposed CTnmt} consists of three techniques: a) asymptotic distillation to ensure that the NMT model can retain the previous pre-trained knowledge; b) a dynamic switching gate to avoid catastrophic forgetting of pre-trained knowledge; and c) a strategy to adjust the learning paces according to a scheduled policy. Our experiments in machine translation show CTnmt gains of up to 3 BLEU score on the WMT14 English-German language pair which even surpasses the previous state-of-the-art pre-training aided NMT by 1.4 BLEU score. While for the large WMT14 English-French task with 40 millions of sentence-pairs, our base model still significantly improves upon the state-of-the-art Transformer big model by more than 1 BLEU score.

Please cite as:
```bibtex
@inproceedings{yang2020towards,
  title={Towards making the most of bert in neural machine translation},
  author={Yang, Jiacheng and Wang, Mingxuan and Zhou, Hao and Zhao, Chengqi and Zhang, Weinan and Yu, Yong and Li, Lei},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={34},
  number={05},
  pages={9378--9385},
  year={2020}
}
```
