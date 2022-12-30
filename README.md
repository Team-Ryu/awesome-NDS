# Awesome-NDS

---

## Overview

This repository covers the following:

- [Introduction](#introduction)
- [NAS Algorithm](#nas-algorithm)
  - [One-shot NAS](#One-shot-NAS)
- [Statistical Analysis of Datasets](#statistical-analysis-of-datasets)
  - [paper subcategory 1](#paper-subcategory-1)



## Introduction

![NDS](https://user-images.githubusercontent.com/90232305/209629502-37e63cf7-5a45-42db-93ea-55b11f8cb9fc.jpg)

Recently, as huge artificial neural networks have begun to gain popularity, the amount of data required for learning is also rapidly increasing. This repository is for the dataset search algorithm called **Neural Dataset Search** (**NDS**) to reduce the astronomical cost of processing, storing, and distributing large datasets and to evaluate and verify supermassive artificial neural networks with only a small dataset. 


## NAS Algorithm

NAS에도 DNAS, single-path NAS, One-shot NAS 등 다양한 기법이 존재하며, 그 중에서 가장 computational efficiency한 one-shot NAS를 기반으로 NDS를 설계하는 것이 적절할 것이라고 판단되었습니다. 



### One-shot NAS


- **SMASH**: "SMASH: One-Shot Model Architecture Search through HyperNetworks", Arxiv, 2017 [[paper](https://arxiv.org/abs/1708.05344)] [[code](https://github.com/ajbrock/SMASH/blob/master/train.py)]
- **Understanding and Simplifying One-Shot Architecture Search**: "Understanding and Simplifying One-Shot Architecture Search", ICML, 2018 [[paper](https://proceedings.mlr.press/v80/bender18a/bender18a.pdf)]
- **SGNAS**: "Searching by Generating: Flexible and Efficient One-Shot NAS with
Architecture Generator", CVPR, 2021 [[paper](https://arxiv.org/abs/2103.07289)] [[code](https://github.com/eric8607242/SGNAS)] [[summary](summary/example.md)]

- **ResNet**: "Deep Residual Learning for Image Recognition", CVPR, 2016 [[paper](https://arxiv.org/abs/1512.03385)] [[code](https://github.com/pytorch/vision/blob/main/torchvision/models/resnet.py)] [[summary](summary/example.md)]


### Performance Estimation Strategy

내용 : 훈련 초기에 서로 다른 network가 보이는 상대적인 성능이 종종 최적 성능에 대해서 의미있는 표시를 제공할 수 있음. (SMASH 에서 이를 활용)
- **Hyperband**: "Hyperband: Bandit-based configuration evaluation for hyperparameter optimization"


## Statistical Analysis of Datasets

Please describe this subcategory with easy words.



### Paper subcategory 1

Please describe this subcategory with easy words.


- **PaperNickName**: "paper title", publication, year [[paper](https://arxiv.org/abs/1512.03385)] [[code](https://github.com/pytorch/vision/blob/main/torchvision/models/resnet.py)] [[summary](summary/example.md)]
- **ResNet**: "Deep Residual Learning for Image Recognition", CVPR, 2016 [[paper](https://arxiv.org/abs/1512.03385)] [[code](https://github.com/pytorch/vision/blob/main/torchvision/models/resnet.py)] [[summary](summary/example.md)]
