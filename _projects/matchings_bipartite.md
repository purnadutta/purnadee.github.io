---
layout: project
title: Counting k-Matchings of Bipartite Graphs
description:
    We studied the use of message passing algorithms to compute the matching number, and to lower bound the number of matchings of a given size in bipartite graphs. The bounds are achieved asymptotically for a sequence of 2-lifts of the original graph. These graphical models can also be used to approximate the permanets and subpermanent sums of positive matrices. We also conducted basic experiments to check efficiency of MPA to approximate permanents of various ensembles of sparse matrices. This was one of the two projects I did during MSc thesis while interning at IISc, Bangalore.
importance: 1
category: research
# nourl: true
code: https://github.com/AtivJoshi/IISc/tree/main/approximating-permanent/experiment%202
# certi: https://github.com/AtivJoshi/Zippel/blob/master/IITGn_Certi.pdf
# report: https://github.com/AtivJoshi/IISc/blob/main/MSc-thesis-Ativ-Joshi.pdf
date: 01-08-2020
end_date: 01-06-2021
---

A parameterized distribution is defined on the set of all matchings, such that it asymptotically converges to a uniform distribution over maximum matchings. This distribution can be approximated using Bethe Approximation and Loopy Annealing Belief Propagation to extract the matching number. This method can also be used to compute the lower bound on the number of k-matchings of a bipartite graph. Furthermore, the bounds are tight for a sequence of random 2-lifts of the original graph. If the graph is weighted, then a similar approach can be used to get the lower bounds on permanent and sub-permanent sums. We conducted basic experiments to check efficiency of MPA to approximate permanents of various ensembles of sparse matrices.

I have been meaning to write a report about this. Meanwhile, you can find the collection of papers I read (which are digitally annotated in awful handwriting) [here](https://github.com/AtivJoshi/IISc/tree/main/approximating-permanent).