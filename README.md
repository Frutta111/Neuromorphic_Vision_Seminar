# From Perceptual Filling-In to Stable Active Vision  

<p align="center">

&nbsp; <img src="./figures/project_overview.png" alt="Project Overview Diagram" width="600">

</p>



> This project explores \*\*biologically inspired visual perception models\*\*, following a progression from \*perceptual filling-in\* to \*stable active vision\*.  

> It combines insights from neuroscience and neuromorphic computing to reconstruct visual experience from incomplete, dynamic retinal input.  

>  

> The repository includes:

> - \*\*Seminar paper\*\* summarizing four key studies (2020–2024).  

> - \*\*Applied experiment\*\* extending \*Model #5 (ConvNet5)\* from Cohen-Duwek et al., 2021.  

> - \*\*Presentation slides\*\* and visual figures.  

>  

> \*Supervisor: Dr. Hadar Cohen-Duwek | The Open University of Israel | September 2025\*



---



\## Overview

This repository accompanies my academic seminar work and presentation on biologically inspired visual perception models.  

It includes a literature-based analysis (papers 1–4) and an applied experiment based on \*\*Model #5 (ConvNet5)\*\* from Cohen-Duwek et al., 2021 — exploring architectural and parameter sensitivity in Laplacian-based image reconstruction.



---



\## Repository Structure



| Folder | Description |

|---------|-------------|

| \[`seminar\_paper/`](./seminar\_paper/) | Full written seminar report (PDF). |

| \[`presentation/`](./presentation/) | Final presentation slides. |

| \[`implementation/`](./implementation/) | Python notebooks, training scripts, and experiment results. |

| \[`references/`](./references/) | Reference list and external links to cited papers. |



---



\## Related Publications



| Year | Reference | Description |

|------|------------|-------------|

| 2020 | \[Cohen et al., 2020 – Peripheral Color Filling-In (Nature Communications)](https://www.nature.com/articles/s41467-020-14520-9) | Experimental evidence showing humans perceive full color even when peripheral chromatic input is missing. |

| 2021 | \[Cohen-Duwek et al., 2021 – Image Reconstruction from Event Cameras (GitHub)](https://github.com/NBELab/CVPR-2021-W) | Introduces the Laplacian–Poisson pipeline for reconstructing intensity images from event-based sensors. |

| 2023 | \[Cohen-Duwek et al., 2023 – Peripheral Colorization via Adversarial Training (arXiv)](https://arxiv.org/abs/2303.08264) | Adds GAN-based colorization to improve perceptual realism in peripheral reconstruction. |

| 2024 | \[Cohen-Duwek et al., 2024 – Stable Active Vision via ConvLSTM and Corollary Discharge (GitHub)](https://github.com/NBELab/SaccadicVision) | Models visual stability across saccades using ConvLSTM networks and CD signals. |

---



\## Implementation Notes

\- The applied experiment reproduces and extends \*\*Model #5 (ConvNet5)\*\* with several architectural and loss-function variants.  

\- Results include PSNR, SSIM, and MSE comparisons across variants (e.g., ReLU, Mish, BatchNorm, Dilated Convs).  

\- Training was performed using the **[N-Caltech101 Event Dataset](https://github.com/NBELab/CVPR-2021-W/tree/main?tab=readme-ov-file#dataset)**, maintaining the setup described in *Cohen-Duwek et al., 2021*.


---



\## Citation

If you use or reference this work, please cite:

> Friedrich, E. (2025). \*From Perceptual Filling-In to Stable Active Vision.\* Advanced Seminar in Computer Science, The Open University of Israel.  

> Supervisor: Dr. Hadar Cohen-Duwek.



---



\## External Resources

\- \[Dataset – N-Caltech101 Event Camera](https://github.com/NBELab/CVPR-2021-W/tree/main?tab=readme-ov-file#dataset)  

\- \[NBELab – Neuromorphic \& Biologically Inspired Engineering Lab](https://github.com/NBELab)  


