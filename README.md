# Provably Confidential Language Modelling

> Provably Confidential Language Modelling  
>
> [Xuandong Zhao](https://xuandongzhao.github.io/), [Lei Li](https://sites.cs.ucsb.edu/~lilei/), [Yu-Xiang Wang](https://sites.cs.ucsb.edu/~yuxiangw/)
>
> NAACL 2022 (Oral)

### [Paper](https://arxiv.org/abs/2205.01863)

We propose **Confidentially Redacted Training (CRT)**, a method to train language generation models while protecting the confidential segments.  We borrow ideas from differential privacy and show that our method is able to provably prevent **unintended memorization** by randomizing parts of the training process. Moreover, we show that **redaction** with an approximately correct screening policy **amplifies the confidentiality guarantee**. 

A pseudo-code of the algorithm:
![](figure/alg.png)

An illustration of our proposed algorithm on a dataset with two data points:
![](figure/alg_fig.png)

#### Our code will be avaiable soon!

## Citation

Please cite our paper if you find CRT useful for your research:

```bibtex
@article{zhao2022provably,
  title={Provably Confidential Language Modelling},
  author={Zhao, Xuandong and Li, Lei and Wang, Yu-Xiang},
  journal={arXiv preprint arXiv:2205.01863},
  year={2022}
}
```

