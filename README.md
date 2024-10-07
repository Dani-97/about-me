# About me

- I have been working in Deep Learning and Machine Learning applied to imaging data (chest X-rays and eye fundus imaging) and also to tabular data.

- The pathological scenarios that I have worked with were COVID-19, tuberculosis and lung nodules. When I worked with eye fundus images, I did not work with any specific pathology.

- Regarding the imaging data that I used, it was chest X-ray and retinography.

- I have performed image classification, segmentation and landmark detection.

- I have worked with the self-supervised paradigm of Context Encoding.
  
- A great part of my works are aimed to adapt image generation algorithms in the field of medical imaging. Particularly, I used different types of GANs and latent diffusion models.

Now, I provide an individual and summarized description of each paper that I have published.

## Context Encoding applied to eye fundus images

**Moris, D. I.**, Hervella, A. S., Rouco, J., Novo, J., & Ortega, M. (2021). Context encoder self-supervised approaches for eye fundus analysis. 2021 International Joint Conference on Neural Networks (IJCNN) (Vol. 313, pp. 1–8)

[[Paper](https://doi.org/10.1109/ijcnn52387.2021.9533567)]

> Demonstration that the Context Encoder paradigm is able to understand the structures that appear in eye fundus images, enabling the possible use of this kind of self-supervised paradigm as a pretraining for other domain-related tasks.

***

**Morís, D. I.**, Hervella, Á. S., Rouco, J., Novo, J., & Ortega, M. (2023). Context encoder transfer learning approaches for retinal image analysis. Computers in Biology and Medicine (Vol. 152, p. 106451)

[[Paper](https://doi.org/10.1016/j.compbiomed.2022.106451)]

> In this paper, we used the Context Encoder paradigm for eye fundus imaging. The aim of this work was to train a self-supervised model with raw data (this means, without manual labeled data) and reuse it as a pretrained model for domain-related supervised tasks such as vessel segmentation and fovea detection.

***

## Deep Learning applied to chest X-ray images from COVID-19 patients

**Iglesias, D.**, de Moura, J., Novo, J., & Ortega, M. (2021). Comprehensive Analysis of the Screening of COVID-19 Approaches in Chest X-ray Images from Portable Devices. ESANN 2021 proceedings (pp. 165–170). ESANN 2021 - European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning

[[Paper](https://doi.org/10.14428/esann/2021.es2021-31)]

> Use of several deep learning classification architectures for COVID-19 screening using chest X-ray images. 

***

**Morís, D. I.**, de Moura, J., Novo, J., & Ortega, M. (2023). Deep feature analysis in a transfer learning approach for the automatic COVID-19 screening using chest X-ray images. Procedia Computer Science (Vol. 225, pp. 228–237)

[[Paper](https://doi.org/10.1016/j.procs.2023.10.007)]

> This article was presented in the KES 2023 conference. The aim was to use the deep features extracted from several deep learning architectures to then train a Support Vector Machine (SVM) model and conduct the task of COVID-19 screening using chest X-ray images. 

***

**Morís, D. I.**, de Moura, J., Aslani, S., Jacob, J., Novo, J., & Ortega, M. (2024). Multi-task localization of the hemidiaphragms and lung segmentation in portable chest X-ray images of COVID-19 patients. Digital Health (Vol. 10). SAGE Publications

[[Paper](https://doi.org/10.1177/20552076231225853)]

> Multi-task landmark detection and lung segmentation in chest X-ray images. The aim of the work was to localize the points of the hemidiaphragms and to segment the lungs in a multi-task manner. The localization of the points was performed leveraging the so-called heatmap regression paradigm.

***

## Extraction of COVID-19 biomarkers with tabular data

Olañeta, D., **Morís, D. I.**, de Moura, J., Marcos, P. J., Rey, E. M., Novo, J., & Ortega, M. (2023). Explainable learning to analyze the outcome of COVID-19 patients using clinical data. Procedia Computer Science (Vol. 225, pp. 238–247)

[[Paper](https://doi.org/10.1016/j.procs.2023.10.008)]

> This article was presented in the KES 2023 conference. In this case, only clinical data was used. The aim was to provide an explainable framework for the task of outcome estimation in COVID-19 patients, estimating two different scenarios: estimation of the risk of hospitalization and estimation of the risk of death. The explainability was provided by the means of a decision tree, that brings a set of rules that let clinicians not only to evaluate the risk of a patient, but also to understand the reasoning behind that estimation.

***

**Morís, D. I.**, de Moura, J., Marcos, P. J., Rey, E. M., Novo, J., & Ortega, M. (2023). Comprehensive analysis of clinical data for COVID-19 outcome estimation with machine learning models. Biomedical Signal Processing and Control (Vol. 84, p. 104818)

[[Paper](https://doi.org/10.1016/j.bspc.2023.104818)]

> This work did not use images, only tabular data. In this case, using a dataset of COVID-19 patients, including information of their demographics, preconditions and laboratory tests, several machine learning models were used to estimate the risk of hospitalization and the risk of death.

***

## Chest X-ray image generation as a data augmentation strategy

**Moris, D. I.**, de Moura, J., Novo, J., & Ortega, M. (2021). Cycle Generative Adversarial Network Approaches to Produce Novel Portable Chest X-Rays Images for Covid-19 Diagnosis. ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)

[[Paper](https://doi.org/10.1109/icassp39728.2021.9414031)]

> In this work, we proposed the chest X-ray image translation from normal to pathological and vice versa. To that end, we used the CycleGAN model. The most interesting contribution of this paper is the demonstration that the CycleGAN model is able to generate the images, perform the required transformations on them and provide a realistic appearance, with accurate anatomical representation.

***

**Morís, D. I.**, de Moura Ramos, J. J., Buján, J. N., & Hortas, M. O. (2021). Data augmentation approaches using cycle-consistent adversarial networks for improving COVID-19 screening in portable chest X-ray images. Expert Systems with Applications (Vol. 185, p. 115681).

[[Paper](https://doi.org/10.1016/j.eswa.2021.115681)]

> Use of the CycleGAN model, a type of GAN, that incorporates the concept of cycle consistency to improve the image translation. The aim of this work was to convert images from normal to pahtological and vice versa. The studied pathology was COVID-19 and related scenarios. Once the images were generated, they were used to improve the classification performance of a screening model. Therefore, the image generation was leveraged as a data augmentation strategy.

***

**Morís, D. I.**, de Moura, J., Novo, J., & Ortega, M. (2022). Unsupervised contrastive unpaired image generation approach for improving tuberculosis screening using chest X-ray images. Pattern Recognition Letters (Vol. 164, pp. 60–66)

[[Paper](https://doi.org/10.1016/j.patrec.2022.10.026)]

> Use of the contrastive unpaired translation paradigm (CUT) that leverages the concept of Contrastive Learning to train image translation models. The CUT is a kind of GAN architecture that, in this work, was used to translate images from normal to pathological and vice versa. The target pathology, in this case, was tuberculosis and two publicly available datasets were used: Montgomery County and Shenzhen. The final aim was to improve the screening performance obtained by the means of a deep learning classifier, using the novel generated images as a data augmentation strategy.

***

**Morís, D. I.**, Moura, J. de, Novo, J., & Ortega, M. (2024). Adapted generative latent diffusion models for accurate pathological analysis in chest X-ray images. Medical &amp; Biological Engineering &amp; Computing (Vol. 62, Issue 7, pp. 2189–2212) 

[[Paper](https://doi.org/10.1007/s11517-024-03056-5)]

> Use of latent diffusion models (the Stable Diffusion v1.4 architecture, to be precise) with the aim to generate synthetic chest X-ray images and use them as a data augmentation strategy. The new synthetic images are added to the training subset in order to improve the metrics of classification models aimed to perform a pathological screening in two different scenarios: tuberculosis and lung nodules. In the case of tuberculosis, we use two publicly available datasets (Montgomery County and Shenzhen) and, in the case of lung nodules, the public dataset JSRT.

***
