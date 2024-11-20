---
title: "A stochastic gda method with backtracking for solving nonconvex (strongly) concave minimax problems"
collection: publications
category: manuscripts
permalink: /publication/A_stochastic_gda_method_with_backtracking_for_solving_nonconvex_(strongly)_concave_minimax_problems
excerpt: ''
date: 2024-03-12
venue: 'ArXiv preprint'
paperurl: 'https://arxiv.org/pdf/2403.07806'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Abstract:

We propose a stochastic GDA (gradient descent ascent) method with backtracking (SGDA-B) to solve nonconvex-(strongly) concave (NCC) minimax problems , where  and  for  are closed, convex functions,  is -smooth and -strongly concave in  for some . We consider two scenarios: (i) the deterministic setting where we assume one can compute  exactly, and (ii) the stochastic setting where we have only access to  through an unbiased stochastic oracle with a finite variance. While most of the existing methods assume knowledge of the Lipschitz constant , SGDA-B is agnostic to . Moreover, SGDA-B can support random block-coordinate updates. In the deterministic setting, SGDA-B can compute an -stationary point within  and  gradient calls when  and , respectively, where . In the stochastic setting, for any  and , it can compute an -stationary point with high probability, which requires  and  stochastic oracle calls, with probability at least , when  and , respectively. To our knowledge, SGDA-B is the first GDA-type method with backtracking to solve NCC minimax problems and achieves the best complexity among the methods that are agnostic to . We also provide numerical results for SGDA-B on a distributionally robust learning problem illustrating the potential performance gains that can be achieved by SGDA-B.
