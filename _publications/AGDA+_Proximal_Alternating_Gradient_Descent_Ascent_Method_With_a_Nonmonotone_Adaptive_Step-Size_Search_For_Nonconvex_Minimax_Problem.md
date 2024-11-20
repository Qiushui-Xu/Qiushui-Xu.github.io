---
title: "AGDA+: Proximal Alternating Gradient Descent Ascent Method With a Nonmonotone Adaptive Step-Size Search For Nonconvex Minimax Problems"
collection: publications
category: manuscripts
permalink: /publication/AGDA+_Proximal_Alternating_Gradient_Descent_Ascent_Method_With_a_Nonmonotone_Adaptive_Step-Size_Search_For_Nonconvex_Minimax_Problems
excerpt: ''
date: 2024-06-20
venue: 'ArXiv preprint'
paperurl: 'https://arxiv.org/pdf/2406.14371'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

We consider double-regularized nonconvex-strongly concave (NCSC) minimax problems of the form , where ,  are closed convex,  is -smooth in  and strongly concave in . We propose a proximal alternating gradient descent ascent method AGDA+ that can adaptively choose nonmonotone primal-dual stepsizes to compute an approximate stationary point for  without requiring the knowledge of the global Lipschitz constant . Using a nonmonotone step-size search (backtracking) scheme, AGDA+ stands out by its ability to exploit the local Lipschitz structure and eliminates the need for precise tuning of hyper-parameters. AGDA+ achieves the optimal iteration complexity of  and it is the first step-size search method for NCSC minimax problems that require only  calls to  per backtracking iteration. The numerical experiments demonstrate its robustness and efficiency.