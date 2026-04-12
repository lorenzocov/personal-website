---
title: "Finding Red Balloons with Split Contracts: Robustness to Individuals'
  Selfishness"
authors: Manuel Cebrian, Lorenzo Coviello, Andrea Vattani, Panagiotis Voulgaris
venue: STOC 2012
year: 2012
link: https://dl.acm.org/doi/abs/10.1145/2213977.2214047
bibtex: >-
  @inproceedings{cebrian2012finding,
    title={Finding red balloons with split contracts: robustness to individuals' selfishness},
    author={Cebrian, Manuel and Coviello, Lorenzo and Vattani, Andrea and Voulgaris, Panagiotis},
    booktitle={Proceedings of the forty-fourth annual ACM symposium on Theory of computing},
    pages={775--788},
    year={2012}
  }
---
The present work deals with the problem of information acquisition in a strategic networked environment. To study this problem, Kleinberg and Raghavan (FOCS 2005) introduced the model of query incentive networks, where the root of a binomial branching process wishes to retrieve an information -- known by each node independently with probability 1/n -- by investing as little as possible. The authors considered fixed-payment contracts in which every node strategically chooses an amount to offer its children paid upon information retrieval to convince them to seek the information in their subtrees. Kleinberg and Raghavan discovered that the investment needed at the root exhibits an unexpected threshold behavior that depends on the branching parameter b. For b>2, the investment is linear in the expected distance to the closest information (logarithmic in n, the rarity of the information), while, for 1<b<2, it becomes exponential in the same distance (i.e., polynomial in n). Arcaute et al. (EC 2007) later observed the same threshold behavior for arbitrary Galton-Watson branching processes.
The DARPA Network Challenge --- retrieving the locations of ten balloons placed at undisclosed positions in the US --- has recently brought practical attention to the problems of social mobilization and information acquisition in a networked environment. The MIT Media Laboratory team won the challenge by acting as the root of a query incentive network that unfolded all over the world. However, rather than adopting a fixed-payment strategy, the team implemented a different incentive scheme based on 1/2-split contracts. Under such incentive scheme, a node u who does not possess the information can recruit a friend v through a contract stipulating that if the information is found in the subtree rooted at v, then v has to give half of her own reward back to u.
Motivated by its empirical success, we present a comprehensive theoretical study of this scheme in the game theoretical setting of query incentive networks. Our main result is that split contracts are robust --- as opposed to fixed-payment contracts--- to nodes' selfishness. Surprisingly, when nodes determine the splits to offer their children based on the contracts received from their recruiters, the threshold behavior observed in the previous work vanishes, and an investment linear in the expected distance to the closest information is sufficient to retrieve the information in any arbitrary Galton-Watson process with b>1. Finally, while previous analyses considered the parameters of the branching process as constants, we are able to characterize the rate of the investment in terms of the branching process and the desired probability of success. This allows us to show improvements even in other special cases.
