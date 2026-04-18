---
title: "Anti-distillation: Improving reproducibility of deep networks"
authors: Gil I. Shamir, Lorenzo Coviello
venue: arXiv
year: 2020
link: https://arxiv.org/abs/2010.09923
bibtex: |-
  @article{shamir2020anti,
    title={Anti-distillation: Improving reproducibility of deep networks},
    author={Shamir, Gil I and Coviello, Lorenzo},
    journal={arXiv preprint arXiv:2010.09923},
    year={2020}
  }
---
Deep networks have been revolutionary in improving performance of machine learning and artificial intelligence systems. Their high prediction accuracy, however, comes at a price of \emph{model irreproducibility\/} in very high levels that do not occur with classical linear models. Two models, even if they are supposedly identical, with identical architecture and identical trained parameter sets, and that are trained on the same set of training examples, while possibly providing identical average prediction accuracies, may predict very differently on individual, previously unseen, examples. \emph{Prediction differences\/} may be as large as the order of magnitude of the predictions themselves. Ensembles have been shown to somewhat mitigate this behavior, but without an extra push, may not be utilizing their full potential. In this work, a novel approach, \emph{Anti-Distillation\/}, is proposed to address irreproducibility in deep networks, where ensemble models are used to generate predictions. Anti-Distillation forces ensemble components away from one another by techniques like de-correlating their outputs over mini-batches of examples, forcing them to become even more different and more diverse. Doing so enhances the benefit of ensembles, making the final predictions more reproducible. Empirical results demonstrate substantial prediction difference reductions achieved by Anti-Distillation on benchmark and real datasets.
