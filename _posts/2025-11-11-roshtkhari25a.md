---
title: Iterative Monte Carlo Tree Search for Neural Architecture Search
openreview: GuwNztkceE
abstract: Recent work has shown Monte-Carlo Tree Search (MCTS) as an effective approach
  for Neural Architecture Search (NAS) in producing competitive architectures. However,
  the performance of the tree search is highly sensitive to the node visiting order.
  If the initial nodes are highly discriminative, good configurations can be efficiently
  found with minimal sampling. In contrast, non-discriminative initial nodes require
  exploring an exponential number of nodes before finding good solutions. In this
  paper, we present an iterative NAS approach to jointly train the recognition model
  with MCTS and learn the optimal node ordering of the tree. With our approach, the
  order of node visits in the tree is iteratively refined based on the estimated performance
  of the nodes on the validation set. With this approach, good architectures are more
  likely to naturally emerge at the beginning of the tree, improving the search process.
  Experiments on two classification benchmarks and a segmentation task show that the
  proposed method can improve the performance of MCTS, compared to state-of-the-art
  MCTS approaches for NAS.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: roshtkhari25a
month: 0
tex_title: Iterative Monte Carlo Tree Search for Neural Architecture Search
firstpage: 3/1
lastpage: 17
page: 3/1-17
order: 3
cycles: false
bibtex_author: Roshtkhari, Mehraveh Javan and Toews, Matthew and Pedersoli, Marco
author:
- given: Mehraveh Javan
  family: Roshtkhari
- given: Matthew
  family: Toews
- given: Marco
  family: Pedersoli
date: 2025-11-11
address:
container-title: Proceedings of the Fourth International Conference on Automated Machine
  Learning
volume: '293'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 11
  - 11
pdf: https://raw.githubusercontent.com/mlresearch/v293/main/assets/roshtkhari25a/roshtkhari25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
