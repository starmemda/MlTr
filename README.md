# MlTr: Multi-label Classification with Transformer

This is official implement of ["MlTr: Multi-label Classification with Transformer"](https://arxiv.org/abs/2106.06195).

## Abstract

The task of multi-label image classification is to recognize all the object labels presented in an image. Though advancing for years, small objects, similar objects and objects with high conditional probability are still the main bottlenecks of previous convolutional neural network(CNN) based models, limited by convolutional kernels' representational capacity. Recent vision transformer networks utilize the self-attention mechanism to extract the feature of pixel granularity, which expresses richer local semantic information, while is insufficient for mining global spatial dependence. In this paper, we point out the three crucial problems that CNN-based methods encounter and explore the possibility of conducting specific transformer modules to settle them. We put forward a Multi-label Transformer architecture(MlTr) constructed with windows partitioning, in-window pixel attention, cross-window attention, particularly improving the performance of multi-label image classification tasks. The proposed MlTr shows state-of-the-art results on various prevalent multi-label datasets such as MS-COCO, Pascal-VOC, and NUS-WIDE with 88.5%, 95.8%, and 65.5% respectively.

## Pretrained model (Results on MS-COCO2014)
| name | resolution | map | params(M) | model | log |
| :---: | :---: | :---: | :---: | :---: | :---: |
| mltr-s | 224x224 | 81.9 | 33 | coming soon | coming soon |
| mltr-m | 384x384 | 86.8 | 62 | coming soon | coming soon |
| mltr-l | 384x384 | 88.5 | 108 | coming soon | coming soon |

## Citing artical
Pleadse cite this article as:
```
@misc{cheng2021mltr,
      title={MlTr: Multi-label Classification with Transformer}, 
      author={Xing Cheng and Hezheng Lin and Xiangyu Wu and Fan Yang and Dong Shen and Zhongyuan Wang and Nian Shi and Honglin Liu},
      year={2021},
      eprint={2106.06195},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
## Started

Please refer to [get_started](get_started.md).
