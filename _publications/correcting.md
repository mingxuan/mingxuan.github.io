---
title: "Auto Correcting in the Process of Translation--Multi-task Learning Improves Dialogue Machine Translation"
collection: publications
permalink: /publication/auto-correct-nmt
excerpt: 'Tao Wang, Chengqi Zhao, *Mingxuan Wang*, Lei Li, Deyi Xiong'
date: 2021-03-20
venue: 'NAACL 2021'
---

**Abstract** <br>
Automatic translation of dialogue texts is a much needed demand in many real life scenarios. However, the currently existing neural machine translation delivers unsatisfying results. In this paper, we conduct a deep analysis of a dialogue corpus and summarize three major issues on dialogue translation, including pronoun dropping, punctuation dropping , and typos . In response to these challenges, we propose a joint learning method to identify omission and typo, and utilize context to translate dialogue utterances. To properly evaluate the performance, we propose a manually annotated dataset with 1,931 Chinese-English parallel utterances from 300 dialogues as a benchmark testbed for dialogue translation. Our experiments show that the proposed method improves translation quality by 3.2 BLEU over the baselines. It also elevates the recovery rate of omitted pronouns from 26.09% to 47.16%. We will publish the code and dataset publicly at this https URL.

[[paper]](https://arxiv.org/abs/2103.16189) [[code]](https://github.com/rgwt123/DialogueMT)

Please cite as:
```bibtex
@article{wang2021auto,
  title={Auto Correcting in the Process of Translation--Multi-task Learning Improves Dialogue Machine Translation},
  author={Wang, Tao and Zhao, Chengqi and Wang, Mingxuan and Li, Lei and Xiong, Deyi},
  journal={arXiv preprint arXiv:2103.16189},
  year={2021}
}
```
