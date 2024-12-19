# Awesome-3D-Gaussian-Splatting-in-Robotics
[![arXiv](https://img.shields.io/badge/arxiv-2410.12262-b31b1b?style=flat&logoColor=red)](https://arxiv.org/abs/2410.12262)

<div align="center">
    <img src="img/overview.png" width="100%">
</div>

## 🏠 Overview
  - [Application of 3DGS in Robotics](#application-of-3dgs-in-robotics)
    - [Scene Understanding](#scene-understanding)
      - [Reconstruction](#reconstruction)
        - [Static Reconstruction](#static-reconstruction)
        - [Dynamic Reconstruction](#dynamic-reconstruction)
      - [Segmentation & Editing](#segmentation-rditing)
        - [Scene Segmentation](#scene-segmentation)
        - [Scene Editing](#scene-editing)
      - [SLAM](#slam)
        - [Visual SLAM](#visual-slam)
        - [Semantic SLAM](#semantic-slam)
        - [Multi-sensor Fusion SLAM](#multi-sensor-fusion-slam)
    - [Scene Interaction](#scene-interaction)
      - [Manipulation](#manipulation)
      - [Navigation](#navigation)
        - [Localization](#localization)
        - [Path Planning](#path-planning)
  - [Advance of 3DGS in Robotics](#advance-of-3dgs-in-robotics)
    - [Adaptability](#adaptability)
      - [Large-Scale](#large-scale)
      - [Motion-Blurred](#motion-blurred)
    - [Efficiency](#efficiency)
      - [Few-Shot](#few-shot)
      - [RMemory Efficiency](#memory-efficiency)


## Application of 3DGS in Robotics

### Static Reconstruction
* **360-GS**: "360-GS: Layout-guided Panoramic Gaussian Splatting For Indoor Roaming", *arXiv*. [[Paper](https://arxiv.org/abs/2402.00763.pdf)] [[Code](https://github.com/LeoDarcy/360GS)] 
* **GaussianRoom**: "GaussianRoom: Improving 3D Gaussian Splatting with SDF Guidance and Monocular Cues for Indoor Scene Reconstruction", *arXiv*. [[Paper](https://arxiv.org/abs/2405.19671.pdf)] [[Code](https://github.com/xhd0612/GaussianRoom)] 
* **IM3DG**: "Integrating Meshes and 3D Gaussians for Indoor Scene Reconstruction with SAM Mask Guidance", *arXiv*. [[Paper](https://arxiv.org/abs/2407.16173.pdf)]
* **GaussianPro**: "GaussianPro: 3D Gaussian Splatting with Progressive Propagation", *ICML 2024*. [[Paper](https://arxiv.org/abs/2402.14650.pdf)] [[Code](https://github.com/kcheng1021/GaussianPro)] [[Project Page](https://kcheng1021.github.io/gaussianpro.github.io/)] 
* **SWAG**: "SWAG: Splatting in the Wild images with Appearance-conditioned Gaussians", *ECCV 2024*. [[Paper](https://arxiv.org/abs/2403.10427.pdf)]
* **GauStudio**: "GauStudio: A Modular Framework for 3D Gaussian Splatting and Beyond", *arXiv*. [[Paper](https://arxiv.org/abs/2403.19632.pdf)] [[Code](https://github.com/GAP-LAB-CUHK-SZ/gaustudio)] 
* **HGS-Mapping**: "HGS-Mapping: Online Dense Mapping Using Hybrid Gaussian Representation in Urban Scenes", *RAL 2024*. [[Paper](https://arxiv.org/abs/2403.20159.pdf)] 
* **HO-Gaussian**: "HO-Gaussian: Hybrid Optimization of 3D Gaussian Splatting for Urban Scenes", *ECCV 2024*. [[Paper](https://arxiv.org/abs/2403.20032.pdf)] 
* **TCLC-GS**: "TCLC-GS: Tightly Coupled LiDAR-Camera Gaussian Splatting for Autonomous Driving", *ECCV 2024*. [[Paper](https://arxiv.org/abs/2404.02410.pdf)]
* **PGSR**: "PGSR: Planar-based Gaussian Splatting for Efficient and High-Fidelity Surface Reconstruction", *TVCG 2024*. [[Paper](https://arxiv.org/abs/2406.06521.pdf)] [[Code](https://github.com/zju3dv/PGSR)] 
* **Wild-GS**: "Wild-GS: Real-Time Novel View Synthesis from Unconstrained Photo Collections", *NeurIPS 2024*. [[Paper](https://arxiv.org/abs/2406.10373.pdf)] [[Code](https://github.com/XuJiacong/Wild-GS)] 
* **WildGaussians**: "WildGaussians: 3D Gaussian Splatting in the Wild", *NeurIPS 2024*. [[Paper](https://arxiv.org/abs/2407.08447.pdf)] [[Code](https://github.com/jkulhanek/wild-gaussians/)] [[Project Page](https://wild-gaussians.github.io//)] 
* **DHGS**: "DHGS: Decoupled Hybrid Gaussian Splatting for Driving Scene", *arXiv*. [[Paper](https://arxiv.org/abs/2407.16600.pdf)] [[Project Page](https://ironbrotherstyle.github.io/dhgs_web///)] 

### Dynamic Reconstruction

 