#  Neural 3D Reconstruction and Immersive VR Visualization of Row Crops Across Phenological Growth Stages

This repository contains the official implementation and resources for our **published paper** on integrating **Neural Radiance Fields (NeRF)**, **3D Gaussian Splatting (G-Splat)**, and **Virtual Reality (VR)** for plant phenotyping across BBCH growth stages.

---

## Overview

We present a unified pipeline that bridges **image-based 3D reconstruction** and **immersive visualization** for agricultural analysis.

The workflow includes:

- Multi-view plant data acquisition in controlled greenhouse environments  
- Camera pose estimation using a globally optimized SfM pipeline (GLOMAP)  
- High-fidelity 3D reconstruction using NeRF (Nerfacto) and G-Splat  
- Alignment with **BBCH growth stages** for biologically meaningful analysis  
- Real-time rendering and interaction in a VR greenhouse (Unreal Engine, Meta Quest)  

This system enables both:
- **Quantitative evaluation** (PSNR, SSIM, LPIPS)  
- **Qualitative exploration** through immersive VR  

---
## Paper Website  
[Website Link](https://idealab-isu.github.io/Neural-3D-Reconstruction-and-Immersive-VR-Visualization-of-Row-Crops/)

## Paper

Read the full paper here:  
[Paper Link](https://www.sciencedirect.com/science/article/pii/S2772375526002479)

---

## Dataset

Access the dataset used in this study:  
 [Dataset Link](https://huggingface.co/datasets/ShambhaviJoshi/Neural_3D_Reconstruction_and_Immersive_VR_Visualization_of_Row_Crops)

The dataset includes:

- Multi-view RGB image sequences (video-derived + photogrammetry)  
- BBCH-labeled plant growth stages  
- Multiple crop species (millets, mungbean, Delta & Amarillo peas)  
- Image sets for both **training (known views)** and **evaluation (unseen views)**  

---

##  Code

All code used in this paper is provided in the `code/` folder.

This includes components for: 
- NeRF and G-Splat reconstruction workflows  
- Integration with Unreal Engine for VR visualization  

---

## Tutorial Video

A tutorial demonstrating how to **convert COLMAP poses to Unreal Engine** will be available here:  
[Video Link](INSERT_VIDEO_LINK_HERE)

---

## Key Components

- **Pose Estimation:** GLOMAP (global SfM, COLMAP-based)  
- **Reconstruction:** Nerfacto (NeRF) + 3D Gaussian Splatting  
- **Rendering & VR:** Unreal Engine (Meta Quest deployment)  
- **Evaluation Metrics:** PSNR, SSIM, LPIPS  

---

##  Key Insights

- **NeRF** provides strong perceptual realism and smooth radiance consistency  
- **G-Splat** achieves better structural fidelity and real-time rendering efficiency  
- Both methods run at **real-time VR performance (~72 FPS)** on standalone headsets  
- The combined pipeline enables scalable and interpretable **3D plant phenotyping**

---

##  Applications

- Plant phenotyping and growth analysis  
- Precision agriculture workflows  
- Digital twins of crops  
- Immersive scientific visualization and education  

---

## Citation

If you use this work, please cite:

```bibtex
@article{joshi2026neural,
  title={Neural 3D Reconstruction and Immersive VR Visualization of Row Crops Across Phenological Growth Stages},
  author={Joshi, Shambhavi and Di Salvo, Juan and Shen, Yanben and Hadadi, Mozhgan and Boddepalli, Venkata Naresh and Jubery, Zaki and Sarkar, Soumik and Singh, Arti and Ganapathysubramanian, Baskar and Singh, Asheesh K and others},
  journal={Smart Agricultural Technology},
  pages={102024},
  year={2026},
  publisher={Elsevier}
}
```

---
