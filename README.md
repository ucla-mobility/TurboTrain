# TurboTrain: Towards Efficient and Balanced Multi-Task Learning for Multi-Agent Perception and Prediction

[![paper](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/pdf/2508.04682)
[![supplement](https://img.shields.io/badge/Supplementary-Material-red)](https://arxiv.org/pdf/2508.04682)

[ICCV 2025] This is the official implementation of "TurboTrain: Towards Efficient and Balanced Multi-Task Learning for Multi-Agent Perception and Prediction", [Zewei Zhou*](https://zewei-zhou.github.io/), [Seth Z. Zhao*](https://sethzhao506.github.io/), [Tianhui Cai](https://www.tianhui-vicky.com/), [Zhiyu Huang](https://mczhi.github.io/), [Bolei Zhou](https://boleizhou.github.io/), [Jiaqi Ma](https://mobility-lab.seas.ucla.edu/about/)

![teaser](images/TurboTrain_framework.png)

TurboTrain is the first efficient and balanced multi-task learning paradigm, comprising task-agnostic self-supervised pretraining and multi-task balancing, which eliminates the need for manually designing and tuning complex multi-stage training pipelines, reducing training time, and improving performance.

## News
- **`2025/08`**: [TurboTrain](https://arxiv.org/pdf/2508.04682) paper release
- **`2025/06`**: [TurboTrain](https://arxiv.org/pdf/2508.04682) is accepted by [ICCV 2025](https://iccv.thecvf.com/)!

## Release Plan
- **`2025/08`**: ✅ [TurboTrain](https://arxiv.org/pdf/2508.04682) paper
- **`2025/10`**: Full Codebase Release.

## Acknowledgement
The codebase is built upon [V2XPnP](https://github.com/Zewei-Zhou/V2XPnP) in the OpenCDA ecosystem family.


## Citation
If you find this repository useful for your research, please consider giving us a star 🌟 and citing our paper.
 ```bibtex
@inproceedings{zhou2025turbotrain,
  title={TurboTrain: Towards efficient and balanced multi-task learning for multi-agent perception and prediction},
  author={Zhou, Zewei and Zhao, Seth Z and Cai, Tianhui and Huang, Zhiyu and Zhou, Bolei and Ma, Jiaqi},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  pages={4391--4402},
  year={2025}
}
```

Other useful citations:
 ```bibtex
@article{zhao2024coopre,
  title={CooPre: Cooperative Pretraining for V2X Cooperative Perception},
  author={Zhao, Seth Z and Xiang, Hao and Xu, Chenfeng and Xia, Xin and Zhou, Bolei and Ma, Jiaqi},
  journal={arXiv preprint arXiv:2408.11241},
  year={2024}
}

@inproceedings{zhou2025v2xpnp,
  title={V2xpnp: Vehicle-to-everything spatio-temporal fusion for multi-agent perception and prediction},
  author={Zhou, Zewei and Xiang, Hao and Zheng, Zhaoliang and Zhao, Seth Z and Lei, Mingyue and Zhang, Yun and Cai, Tianhui and Liu, Xinyi and Liu, Johnson and Bajji, Maheswari and others},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  pages={25399--25409},
  year={2025}
}

@article{xiang2024v2xreal,
  title={V2X-Real: a Largs-Scale Dataset for Vehicle-to-Everything Cooperative Perception},
  author={Xiang, Hao and Zheng, Zhaoliang and Xia, Xin and Xu, Runsheng and Gao, Letian and Zhou, Zewei and Han, Xu and Ji, Xinkai and Li, Mingxi and Meng, Zonglin and others},
  journal={arXiv preprint arXiv:2403.16034},
  year={2024}
}
```
