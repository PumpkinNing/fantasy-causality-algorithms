# fantasy-causality-algorithms

An index of algorithms in
- causal discovery
- causal representation learning
- causal domain generalization


 Table of Contents

- [Causal Discovery](#causal-discovery)
- [Causal Representation Learning](#causal-representation-learning)
- [Causal Domain Generalization](#causal-domain-generalization)

### Causal Discovery
|Name|Paper|Code|Methods|Dataset
|---|---|---|---|---|
|[NCC](https://arxiv.org/pdf/1605.08179v2.pdf)|Discovering Causal Signals in Images(CVPR2017)|[Tensorflow](https://github.com/kyrs/NCC-experiments)|build a classifier to find the causal direction between pairs of random variables|Synthetic data|
|[RL-BIC2](https://arxiv.org/pdf/1906.04477v4.pdf)|Causal Discovery with Reinforcement Learning(ICLR2020)|[Python](https://github.com/huawei-noah/trustworthyAI)|takes observable data as input and generates graph adjacency matrices that are used to compute rewards. The reward incorporates both the predefined score function and two penalty terms for enforcing acyclicity|---|
|[DCDI](https://arxiv.org/pdf/2007.01754v2.pdf)|Differentiable Causal Discovery from Interventional Data(NeurIPS2020)|[Pytorch](https://github.com/slachapelle/dcdi)| proposing a theoretically-grounded method based on neural networks that can leverage interventional data|---|
|[ENCO](https://arxiv.org/pdf/2107.10483v3.pdf)|Efficient Neural Causal Discovery without Acyclicity Constraints(ICLR2022)|[Tensorflow](https://github.com/anony192847385/iclr2022_paper657)|an efficient structure learning method for directed, acyclic causal graphs leveraging observational and interventional data|---|

### Causal Representation Learning
|Name|Paper|Code|Methods|Dataset
|---|---|---|---|---|
|[LCIT](https://arxiv.org/pdf/2209.01547v1.pdf)|Conditional Independence Testing via Latent Representation Learning(AAAI2017)|[Pytorch](https://github.com/baosws/lcit)|---|Synthetic data

### Causal Doamin Generalization
|Name|Paper|Code|Methods|Dataset
|---|---|---|---|---|
|[CIDDG](https://openaccess.thecvf.com/content_ECCV_2018/papers/Ya_Li_Deep_Domain_Generalization_ECCV_2018_paper.pdf)|Deep Domain Generalization via Conditional Invariant Adversarial Networks(ECCV2018)|---|---|MINST

