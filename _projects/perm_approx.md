---
layout: project
title: Approximating Permanents of Positive Matrices Using Probabilistic Graphical Models
description:
    The primary approach is to create a Markov Random Field whose partition function is the permanent of a square matrix. Then use Belief Propagation to compute Bethe Free Energy which approximates the permanent. We then try to generalize the algorithm to compute permanent of rectangular matrices. This internship at CMI was a part of my bachelor’s thesis.
importance: 1
category: research
# nourl: true
code: https://github.com/AtivJoshi/Perm-Approx
# certi: https://github.com/AtivJoshi/Zippel/blob/master/IITGn_Certi.pdf
report: https://github.com/AtivJoshi/Perm-Approx/blob/master/ICT-Rectangular_Matrix_Permanent_Approximation.pdf
date: 01-01-2019
end_date: 01-05-2019
---
The basic approach is to create a Pairwise Markov Random Field (PMRF) whose partition function is the permanent of a matrix. The partition function is approximated by minimizing the corresponding Bethe Free Energy of the PMRF. The Bethe Free Energy (BFE) is minimized using the Belief Propagation (BP) algorithm. Since BP does not necessarily converge for arbitrary graphs, I was surprised by the efficiency of BP in computing the Bethe approximation. We extended the algorithm to compute the permanent of rectangular matrices and produced some empirical results.