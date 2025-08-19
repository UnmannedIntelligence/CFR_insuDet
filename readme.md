# A Convolutional Feature Reuse-Based Insulator Defect Detection Method for High-Voltage Transmission Lines

### Repository Overview

This repository provides the experimental resources for our manuscript submitted to *IEEE SENSORS JOURNAL*. It contains source code, experimental data, and aerial inspection videos used for the insulator missing defect detection study.

⚠️ **Note:** At present, only experimental videos are available. The source code and datasets will be uploaded after the manuscript is accepted.





## Abstract

Unmanned aerial vehicles (UAVs) have become an important tool for inspecting high-voltage transmission lines, but detecting insulator defects from aerial images remains challenging due to complex backgrounds, small object sizes, and the demand for real-time processing.

In this study, we propose a deep learning-based detection method with the following key contributions:

- **Staged feature extraction**: A combination of multi-scale feature fusion and a deeper extraction network improves semantic representation while preserving small-object details.
- **Convolutional feature reuse**: Reduces model complexity and accelerates inference without compromising accuracy.
- **Two-layer fusion strategy**: Enhances feature extraction capability and strengthens robustness in complex aerial inspection scenarios.
- **Dataset contribution**: A new Glass Insulator Dataset (GID), containing 4,123 high-resolution UAV images, is constructed in this study as the primary benchmark for evaluation.

The proposed method is evaluated on both the Chinese Power Line Insulator Dataset (CPLID) and GID, achieving higher detection and localization accuracy compared with existing approaches, particularly for small-object detection. Furthermore, the model is deployed on an NVIDIA Jetson Xavier NX onboard a DJI M300 UAV and validated through outdoor flight tests on 330 kV overhead transmission lines. Results confirm not only the method’s effectiveness but also its practicality for real-world UAV-based inspection tasks.


## Citation

If you find this repository useful in your research, please cite our paper once it is published in *IEEE SENSORS JOURNAL*:

```text
@article{Sensors2025ZhangUAVInsuDet,
  author = {Yulong Zhang, Xianghong Xue, Lingxia Mu, Jing Xin, Yichi Yang, Youmin Zhang},
  title = {A Convolutional Feature Reuse-Based Insulator Defect Detection Method for High-Voltage Transmission Lines},
  journal = {IEEE Sensors Journal},
  year    = {2025},
  volume  = {...},
  number  = {...},
  pages   = {...},
  doi     = {...}
}
```

---

## Contact

For questions or collaborations, please contact:

**Yulong Zhang** · [yulong.zhang@stu.xaut.edu.cn](mailto:yulong.zhang@stu.xaut.edu.cn)
