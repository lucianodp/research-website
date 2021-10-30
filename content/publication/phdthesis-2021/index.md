---
title: "New Algorithms and Optimizations for Human-in-the-Loop Model Development"
date: 2021-07-07
publishDate: 2021-10-12T04:31:12Z
authors: ["Luciano Di Palma"]
publication_types: ["8"]
abstract: ""
featured: false
publication: "*Institut Polytechnique de Paris*"
url_pdf: "https://hal.inria.fr/tel-03319743v2/document"
url_poster: "defense.pdf"
abstract: "
In this thesis, we propose a human-in-the-loop framework for efficient model development over large data sets. In this framework, we aim to apply active learning algorithms to select a small sequence of data instances for the user to label and derive an accurate model while, at the same time, offering interactive performance in presenting the next data instance for reviewing. However, existing active learning techniques often fail to provide satisfactory performance when built over large data sets. Not only such models often require hundreds of labeled data instances to reach high accuracy, but retrieving the next instance to label can be time-consuming, making it incompatible with the interactive nature of the human exploration process. To address these issues, we propose the following contributions:


	1. A new theoretical framework that allows for an efficient implementation of the Generalized Binary Search strategy over kernel classifiers. Compared to previous work, our framework offers both strong theoretical guarantees on performance and efficient implementation in time and space.


	2. An optimized VS algorithm called OptVS that uses the hit-and-run algorithm for sampling the version space. We also develop a range of sampling optimizations to improve both sample quality and running time. In practice, we observe that OptVS achieves similar or better performance than state-of-the-art version space algorithms while running under 1 second per iteration at all times.


	3. A new algorithm that leverages the factorization structure provided by the user to create subspaces and factorizes the version space accordingly to perform active learning in the subspaces. We also provide theoretical results on the optimality of our factorized VS algorithm and optimizations for dealing with categorical variables. Our evaluation results show that, for all user patterns considered, our factorized VS algorithm outperforms non-factorized active learners as well as DSM, another factorization-aware algorithm, often by a wide margin while maintaining interactive speed.


	4. Following the intuitive reasoning behind the user decision-making process, we develop a new human-inspired classification algorithm, called the Factorized Linear Model (FLM), that decomposes the user interest as a combination of low-dimensional convex objects, resulting in an accurate, efficient, and interpretable classifier. In practice, we observe that the FLM classifier achieves comparable or better performance than SVM and another interpretable model, VIPR, over the majority of user interest patterns while taking only a few minutes to train over a large data set of nearly one million points.


	5. A novel automatically factorized active learning strategy called the Swapping Algorithm. This technique initially employs OptVS to escape the slow convergence of initial iterations and then swaps to an FLM-based strategy to take advantage of its higher classification accuracy. Our evaluation shows that the Swapping Algorithm achieves similar or better performance than non-factorized active learners while approximating the explicitly factorized methods.
"
---
