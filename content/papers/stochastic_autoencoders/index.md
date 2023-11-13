---
title: "Augmentation-Augmented Stochastic Autoencoders" 
date: 2021-07-21
tags: ["stochastic-autoencoders", "VAEs"]
author: ["Ananya Harsh Jha", "William Falcon", "Teddy Koker", "Kyunghyun Cho"]
description: "This paper proposes a stochastic autoencoder for self-supervised learning." 
summary: "This paper proposes a stochastic autoencoder for self-supervised learning, whose latent space is shaped by data augmentation rather than via KL-divergence with a standard normal distribution." 
cover:
    image: "aasae.png"
    alt: "stochastic-autoencoder"
    relative: false
editPost:
    URL: "https://arxiv.org/pdf/2107.12329.pdf"
    Text: "arXiv"

---

##### Download

+ [Paper](aavae.pdf)
+ [Code and data](https://github.com/ananyahjha93/stochastic-autoencoders)

---

##### Abstract

Recent methods for self-supervised learning can be grouped into two paradigms: contrastive and non-contrastive approaches. Their success can largely be attributed to data augmentation pipelines which generate multiple views of a single input that preserve the underlying semantics. In this work, we introduce augmentation-augmented stochastic autoencoders (AASAE), yet another alternative to self-supervised learning, based on autoencoding. We derive AASAE starting from the conventional variational autoencoder (VAE), by replacing the KL divergence regularization, which is agnostic to the input domain, with data augmentations that explicitly encourage the internal representations to encode domain-specific invariances and equivariances. We empirically evaluate the proposed AASAE on image classification, similar to how recent contrastive and non-contrastive learning algorithms have been evaluated. Our experiments confirm the effectiveness of data augmentation as a replacement for KL divergence regularization. The AASAE outperforms the VAE by 30\% on CIFAR-10, 40\% on STL-10 and 45\% on Imagenet. On CIFAR-10 and STL-10, the results for AASAE are largely comparable to the state-of-the-art algorithms for self-supervised learning.

---

##### Figure 1: Augmentation-augmented stochastic autoencoder

![Stochastic Autoencoder](aasae.png)

---

##### Citation

```BibTeX
@inproceedings{Falcon2021AASAEAS,
  title={AASAE: Augmentation-Augmented Stochastic Autoencoders},
  author={William Falcon and A. Jha and Teddy Koker and Kyunghyun Cho},
  year={2021},
  url={https://api.semanticscholar.org/CorpusID:246634445}
}
```

<!-- ---

##### Related material

+ [Presentation slides](presentation2.pdf) -->

