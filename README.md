
# WS-ZSG  
[![Paper][https://dl.acm.org/doi/abs/10.1145/3664647.3680897]] 
[![openreview][https://openreview.net/pdf?id=dJstz3rQ2f]]  
[![Conference](https://2024.acmmm.org/)]

> **Title**: Triple Alignment Strategies for Zero-shot Phrase Grounding under Weak Supervision
> **Authors**: Pnegyue Lin et al.  
> **Affiliation**: Beijing University of Posts and Telecommnuciations  
> **Conference**: ACMMM 2024 


Abstract:

Phrase grounding, i.e., PG aims to locate objects referred by noun phrases. Recently, PG under weak supervision (i.e., grounding without region-level annotations) and zero-shot PG (i.e., grounding from seen categories to unseen ones) are proposed, respectively. However, for real-world applications these two approaches are limited due to slight annotations and numerable categories during training. In this paper, we propose a framework of zero-shot PG under weak supervision. Specifically, our PG framework is built on triple alignment strategies. Firstly, we propose a region-text alignment (RTA) strategy to build region-level attribute associations via CLIP. Secondly, we propose  a domain alignment (DomA) strategy by minimizing the difference between distributions of seen classes in the training and those of the pre-training. Thirdly, we propose a category alignment (CatA) strategy by considering both category semantics and region-category relations. Extensive experiment results show that our proposed PG framework outperforms previous zero-shot  methods and achieves competitive performance  compared with existing weakly-supervised methods. The code and data will be publicly available at GitHub after double-blind phase. 
