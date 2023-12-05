---
title: "Interpretability through Training Samples: Data Attribution for Diffusion Models"
Date: Nov, 2023
excerpt: "Data attribution methods help interpret how neural networks behave by linking the model behavior to their training data. We extend the first-order influence approximation, TracIn, to diffusion models by incorporating the denoising timestep dynamics. We demonstrate that this influence estimation may be biased due to dominating gradient norms. To this end, Diffusion-ReTrac with a renormalization technique is introduced, enabling notably more localized influence estimation and the targeted attribution of training samples.![image_tracing-1](https://github.com/txie1/txie1.github.io/assets/117710195/2400b929-fb16-48d2-9395-eef9326924b7)
"
collection: research
---

### Interpretability through Training Samples: Data Attribution for Diffusion Models
Tong Xie*, Haoyu Li*, Andrew Bai, Cho-jui Hsieh

Data attribution methods help interpret how neural networks behave by linking the model behavior to their training data. We extend the first-order influence approximation, TracIn, to diffusion models by incorporating the denoising timestep dynamics. We demonstrate that this influence estimation may be biased due to dominating gradient norms. To this end, Diffusion-ReTrac with a renormalization technique is introduced, enabling notably more localized influence estimation and the targeted attribution of training samples.

![image_tracing-1](https://github.com/txie1/txie1.github.io/assets/117710195/c7977afc-5273-4da5-8469-900a90ce9af8)
