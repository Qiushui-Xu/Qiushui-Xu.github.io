---
title: "Enhancing Cross-domain Pre-Trained Decision Transformers with Adaptive Attention"
collection: publications
category: manuscripts
permalink: /publication/Enhancing_Cross-domain_Pre-Trained_Decision_Transformers_with_Adaptive_Attention
excerpt: ''
date: 2024-9-11
venue: 'ArXiv preprint'
# slidesurl: 'https://arxiv.org/abs/2409.06985'
paperurl: 'https://arxiv.org/pdf/2409.06985'
# citation: 'Wenhao Zhao, Qiushui Xu, Linjie Xu, Lei Song, Jinyu Wang, Chunlai Zhou, Jiang Bian. (2024). &quot;Enhancing Cross-domain Pre-Trained Decision Transformers with Adaptive Attention.&quot; <i>ArXiv preprint</i>. 1(1).'
---
**Abstract**: Recently, the pre-training of decision transformers (DT) using a different domain, such as natural language text, has generated significant attention in offline reinforcement learning (Offline RL). Although this cross-domain pre-training approach achieves superior performance compared to training from scratch in environments required short-term planning ability, the mechanisms by which pre-training benefits the fine-tuning phase remain unclear. Furthermore, we point out that the cross-domain pre-training approach hinders the extraction of distant information in environments like PointMaze that require long-term planning ability, leading to performance that is much worse than training DT from scratch. This work first analyzes these issues and found that Markov Matrix, a component that exists in pre-trained attention heads, is the key to explain the significant performance disparity of pre-trained models in different planning abilities. Inspired by our analysis, we propose a general method GPT-DTMA, which equips a pre-trained DT with Mixture of Attention (MoA), to enable adaptive learning and accommodating diverse attention requirements during fine-tuning. Extensive experiments demonstrate that the effectiveness of GPT-DTMA: it achieves superior performance in short-term environments compared to baselines, and in long-term environments, it mitigates the negative impact caused by Markov Matrix, achieving results comparable to those of DT trained from scratch.

@misc{zhao2024enhancingcrossdomainpretraineddecision,  
      title={Enhancing Cross-domain Pre-Trained Decision Transformers with Adaptive Attention},   
      author={Wenhao Zhao and Qiushui Xu and Linjie Xu and Lei Song and Jinyu Wang and Chunlai Zhou and Jiang Bian},  
      year={2024},  
      eprint={2409.06985},  
      archivePrefix={arXiv},  
      primaryClass={cs.LG},  
      url={https://arxiv.org/abs/2409.06985},   
}