---
title: Smooth activations and reproducibility in deep networks
authors: Gil I. Shamir, Dong Lin, Lorenzo Coviello
venue: arXiv
year: 2020
link: https://arxiv.org/abs/2010.09931
bibtex: |-
  @article{shamir2020smooth,
    title={Smooth activations and reproducibility in deep networks},
    author={Shamir, Gil I and Lin, Dong and Coviello, Lorenzo},
    journal={arXiv preprint arXiv:2010.09931},
    year={2020}
  }
---
Deep networks are gradually penetrating almost every domain in our lives due to their amazing success. However, with substantive performance accuracy improvements comes the price of \emph{irreproducibility}. Two identical models, trained on the exact same training dataset may exhibit large differences in predictions on individual examples even when average accuracy is similar, especially when trained on highly distributed parallel systems. The popular Rectified Linear Unit (ReLU) activation has been key to recent success of deep networks. We demonstrate, however, that ReLU is also a catalyzer to irreproducibility in deep networks. We show that not only can activations smoother than ReLU provide better accuracy, but they can also provide better accuracy-reproducibility tradeoffs. We propose a new family of activations; Smooth ReLU (\emph{SmeLU}), designed to give such better tradeoffs, while also keeping the mathematical expression simple, and thus implementation cheap. SmeLU is monotonic, mimics ReLU, while providing continuous gradients, yielding better reproducibility. We generalize SmeLU to give even more flexibility and then demonstrate that SmeLU and its generalized form are special cases of a more general methodology of REctified Smooth Continuous Unit (RESCU) activations. Empirical results demonstrate the superior accuracy-reproducibility tradeoffs with smooth activations, SmeLU in particular.
