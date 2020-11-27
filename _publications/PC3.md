---
title: "Predictive Coding for Locally-Linear Control"
collection: publications
permalink: /publications/PC3
venue: "The 37th International Conference on Machine Learning (ICML), 2020."
authors: 'Rui Shu*, <b>Tung Nguyen*</b>, Yinlam Chow, Tuan Pham, Khoat Than, Mohammad Ghavamzadeh, Stefano Ermon, Hung Bui'
url: "https://arxiv.org/pdf/2005.13239.pdf"
code: "https://github.com/VinAIResearch/PC3-pytorch"
blog: "https://tungnd1705.github.io/posts/PC3"
slide: "https://docs.google.com/presentation/d/1LXkvapjK5aFN-zumnjFTU2JnFYNPv0NVUVdvobY8oWo/edit?usp=sharing"
talk: "https://tungnd1705.github.io/talks/PC3"
---
<!-- [[Paper]](https://arxiv.org/pdf/2005.13239.pdf) [[Code]](https://github.com/VinAIResearch/PC3-pytorch)


## Abstract
High-dimensional observations and unknown dynamics are major challenges when applying optimal control to many real-world decision making tasks. The Learning Controllable Embedding (LCE) framework addresses these challenges by embedding the observations into a lower dimensional latent space, estimating the latent dynamics, and then performing control directly in the latent space. To ensure the learned latent dynamics are predictive of next-observations, all existing LCE approaches decode back into the observation space and explicitly perform next-observation prediction—a challenging high-dimensional task that furthermore introduces a large number of nuisance parameters (i.e., the decoder) which are discarded during control. In this paper, we propose a novel information-theoretic LCE approach and show theoretically that explicit next-observation prediction can be replaced with predictive coding. We then use predictive coding to develop a decoder-free LCE model whose latent dynamics are amenable to locally-linear control. Extensive experiments on benchmark tasks show that our model reliably learns a controllable latent space that leads to superior performance when compared with state-of-the-art LCE baselines. -->