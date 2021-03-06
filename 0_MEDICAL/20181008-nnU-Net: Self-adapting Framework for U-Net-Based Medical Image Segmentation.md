[arxiv link](https://arxiv.org/abs/1809.10486)

Keyword

- Image Segmentation, Medical Segmentation Decathlon, Winning method, engineering technique

Overview

- Winning method for Medical Segmentation Decathlon challenge, hosted jointly with MICCAI 2018.
- Heuristic rule-based approach for adapting dataset to U-Net architecture
- Use 2D / 3D / ensemble. Performance varies among tasks (none is "the best")
- The term 'self-adapting' may be confusing, but it means the non-architectural parts (such as image size, stride, etc) are modified according to the dataset statistics.

Thoughts

- It is very important to carefully tune the dataset
- It is worth to note that U-Net is very insensitive to architectural changes (why?)
  - Is it because of the dataset? (small number of samples, large size)
  - What will be the best architecture, if we apply neural architecture search, starting from U-Net?
