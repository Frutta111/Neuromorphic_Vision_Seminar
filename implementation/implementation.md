# Implementation Notes  

The **applied experiment** reproduces and extends **Model #5 (ConvNet5)** from *Cohen-Duwek et al., 2021*,  
introducing several **architectural** and **loss-function** variants to test sensitivity in Laplacian-based image reconstruction.

---

## Overview  
- Multiple variants were trained with different configurations, including:  
  - Activation functions: *ReLU*, *Mish*  
  - Architectural features: *Batch Normalization*, *Dilated Convolutions*  
  - Loss weighting parameters *(λ₁, λ₂, λ₃)* to balance pixel, structural, and edge terms  
- Evaluation metrics: **PSNR**, **SSIM**, and **MSE**  
- Dataset: **[N-Caltech101 Event Dataset](https://github.com/NBELab/CVPR-2021-W/tree/main?tab=readme-ov-file#dataset)**  
  (following the setup in *Cohen-Duwek et al., 2021*)  


## Training Scripts and Experiment Files  

- Main code for training ConvNet5 variants is under [notebookes](https://github.com/Frutta111/Neuromorphic_Vision_Seminar/tree/main/implementation/notebooks)
- Each variant was initialized from pretrained weights (`best_model_simplet_6_fixed_model5.h5`) from [CVPR-2021-W](https://github.com/NBELab/CVPR-2021-W/tree/main/notebooks) and fine-tuned individually.
Model weights, configuration and visual outputs files are stored under [trained_models](https://github.com/Frutta111/Neuromorphic_Vision_Seminar/tree/main/implementation/trained_models) with names matching the experiment (e.g., `v1_baseline_config.json`).  

> *For results and detailed model, see the seminar report (Section 6: Implementations).*



