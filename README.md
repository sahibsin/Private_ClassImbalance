# DP-SGD vs PATE: Which Has Less Disparate Impact on Model Accuracy? (PPML @ ACM CCS'21)
![Made With python 3.8.2](https://img.shields.io/badge/Made%20with-Python%203.8.2-brightgreen)![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)![Pytorch](https://img.shields.io/badge/Made%20with-Pytorch-green.svg)

### Abstract
Recent advances in differentially private deep learning have demonstrated that application of differential privacy, specifically the DP-SGD algorithm, has a disparate impact on different sub-groups in the population, which leads to a significantly high drop-in model utility for sub-populations that are under-represented (minorities), compared to well-represented ones. In this work, we aim to compare PATE, another mechanism for training deep learning models using differential privacy, with DP-SGD in terms of fairness. We show that PATE does have a disparate impact too, however, it is much less severe than DP-SGD. We draw insights from this observation on what might be promising directions in achieving better fairness-privacy trade-offs.

### Paper
https://arxiv.org/abs/2106.12576

### Citation
Citation:
`@article{uniyal2021dp,
  title={DP-SGD vs PATE: Which Has Less Disparate Impact on Model Accuracy?},
  author={Uniyal, Archit and Naidu, Rakshit and Kotti, Sasikanth and Singh, Sahib and Kenfack, Patrik Joslin and Mireshghallah, Fatemehsadat and Trask, Andrew},
  journal={arXiv preprint arXiv:2106.12576},
  year={2021}
}`
