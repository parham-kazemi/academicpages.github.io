---
title: "Dictionary Learning for Sparse Representation of Signals With Hidden Markov Model Dependency"
collection: publications
permalink: /publication/2021-paper-bss
#excerpt: 'The goal of dictionary learning algorithms is factorizing the matrix of training signals Y with K signals, into the dictionary matrix D and the coeficient matrix X which is a sparse matrix.'
date: 2021-09-27
venue: 'Digital Signal Processing'
paperurl: #'http://parham-kazemi.github.io/files/paper1.pdf'
citation: #'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Abstract
=====
The goal of dictionary learning algorithms is factorizing the matrix of training
signals Y with K signals, into the dictionary matrix D and the coeficient
matrix X which is a sparse matrix. The common approach among the algorithms
is minimizing the representation error subject to the sparseness of X
using alternation minimization method following 1) the sparsification and 2)
the dictionary update steps. In this approach, when D is fixed and X must be
estimated (the sparsification step), the minimization problem is divided to K
different sparse recovery problems because the training signals are assumed to be
independent. However, in some signals such as medical signals, this assumption
is not correct and the signals are not independent. Therefore, using the current
strategy does not lead to the correct estimation of the parameters. In this
study, we investigate the dictionary learning problem for sparse representation
when there is hidden Markov model (HMM) dependency among the training
signals. We propose an approach to improve the performance of the dictionary
learning algorithms in the mentioned scenario. The proposed approach is not an
independent dictionary learning algorithm. It is a general approach that we can
employ for existing dictionary learning algorithms to improve their performance
in learning from signals with HMM dependency. We confirm the eficiency of
the proposed approach using simulations, and also, present a real application in
medical signals for the considered scenario.

[Download paper here](http://parham-kazemi.github.io/files/paper1.pdf)

<!---
Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1).
--->
