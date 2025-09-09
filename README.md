
# WS-ZSG  
[![Paper](https://img.shields.io/badge/Paper-PDF-blue)](https://dl.acm.org/doi/abs/10.1145/3664647.3680897)
[![OpenReview](https://img.shields.io/badge/OpenReview-PDF-orange)](https://openreview.net/pdf?id=dJstz3rQ2f)
[![Conference](https://img.shields.io/badge/Conference-ACM_Multimedia_2024-red)](https://2024.acmmm.org/)

> **Title**: Triple Alignment Strategies for Zero-shot Phrase Grounding under Weak Supervision  
> **Authors**: Pengyue Lin, Ruifan Li, Yuzhe Ji, Zhihan Yu, Fangxiang Feng, Zhanyu Ma, Xiaojie Wang  
> **Affiliation**: Beijing University of Posts and Telecommunications  
> **Conference**: ACM Multimedia 2024 (Full Paper, pp. 4312–4321)

## 📄 Abstract

Phrase grounding (PG) aims to localize objects referred to by noun phrases in an image. Recent works have explored either weakly supervised PG (without region-level annotations) or zero-shot PG (generalizing from seen to unseen categories). However, both settings have limitations in real-world applications due to scarce annotations and limited category coverage during training.

In this paper, we propose **WS-ZSG**, a novel framework for **Zero-shot Phrase Grounding under Weak Supervision**. Our approach is built upon three key alignment strategies:

1. **Region-Text Alignment (RTA)**: Leverages CLIP to establish region-level attribute associations between image regions and text descriptions.
2. **Domain Alignment (DomA)**: Minimizes the distributional gap between seen classes in training data and those from pre-training domains.
3. **Category Alignment (CatA)**: Integrates category semantics and region-category relationships to enhance generalization to unseen categories.

Extensive experiments demonstrate that our method outperforms existing zero-shot approaches and achieves competitive performance compared to fully and weakly supervised methods. The code and data will be made publicly available after the double-blind review phase.



## 📚 Citation

If you find this work helpful, please cite our paper:

```bibtex
@inproceedings{lin2024triple,
  title={Triple alignment strategies for zero-shot phrase grounding under weak supervision},
  author={Lin, Pengyue and Li, Ruifan and Ji, Yuzhe and Yu, Zhihan and Feng, Fangxiang and Ma, Zhanyu and Wang, Xiaojie},
  booktitle={Proceedings of the 32nd ACM International Conference on Multimedia},
  pages={4312--4321},
  year={2024}
}
```

## 📄 License

This project is released under the [MIT License](LICENSE).


