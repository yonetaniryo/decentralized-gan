---
layout: default
title: home
---

# Decentralized Learning of Generative Adversarial Networks from Non-iid Data


[Ryo Yonetani](https://yonetaniryo.github.io/)&dagger;, Tomohiro Takahashi&Dagger;, [Atsushi Hashimoto](https://atsushihashimoto.github.io/cv/)&dagger;, [Yoshitaka Ushiku](https://yoshitakaushiku.net/)&dagger;

&dagger;[OMRON SINIC X](https://www.omron.com/sinicx/), &Dagger;OMRON



## Overview
This work addresses a new problem that learns generative adversarial networks (GANs) from multiple data collections that are each i) owned separately by different clients and ii) drawn from a non-identical distribution that comprises different classes. Given such non-iid data as input, we aim to learn a distribution involving all the classes input data can belong to, while keeping the data decentralized in each client storage. Our key contribution to this end is a new decentralized approach for learning GANs from non-iid data called Forgiver-First Update (F2U), which a) asks clients to train an individual discriminator with their own data and b) updates a generator to fool the most `forgiving' discriminators who deem generated samples as the most real. Our theoretical analysis proves that this updating strategy allows the decentralized GAN to achieve a generator's distribution with all the input classes as its global optimum based on f-divergence minimization. Moreover, we propose a relaxed version of F2U called Forgiver-First Aggregation (F2A) that performs well in practice, which adaptively aggregates the discriminators while emphasizing forgiving ones. Our empirical evaluations with image generation tasks demonstrated the effectiveness of our approach over state-of-the-art decentralized learning methods.


## Poster at [CVPR2019 Workshop on CV-COPS](https://cvcops19.cispa.saarland/) 

![/assets/YTHU-CVPRW2019_nologo.pdf](/assets/YTHU-CVPRW2019_nologo.png)
[pdf version](/assets/YTHU-CVPRW2019_nologo.pdf)

## Paper

[arXiv preprint](https://arxiv.org/abs/1905.09684)

```
@article{yonetani2019decentralized,
title={Decentralized Learning of Generative Adversarial Networks from Multi-Client Non-iid Data},
author={Yonetani, Ryo and Takahashi, Tomohiro and Hashimoto, Atsushi and Ushiku, Yoshitaka},
journal={arXiv preprint arXiv:1905.09684},
year={2019}
}
```
