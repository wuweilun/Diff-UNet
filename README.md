# MIP_Tumor_Segmentation
This repository is the 2023 final project for the NTU Medical Image Processing course.
We aim to experiment with different state-of-the-art (SOTA) models, exploring their strengths and weaknesses. We also compare their performances in terms of WT, TC, ET, and visualize the segmentation results for a comprehensive evaluation.
## Dataset (Brain Tumor Segmentation 2020)
Brain Tumor Segmentation(BraTS2020) challenge is the semantic segmentation of brain tumors. This is achieved by providing a 3D MRI dataset with voxel-wise ground truth labels annotated by medical professionals.
It contains training dataset comprises 369 subjects, each with four 3D MRI modalities:

- native (T1)
- post-contrast T1-weighted (T1Gd)
- T2-weighted (T2)
- T2 Fluid-attenuated Inversion Recovery (T2-FLAIR)
## Methodology
We chose four different types of popular models: 3D-CNN-based (3D-UNet, SegResNet), Transformer-based (Swin-UNETR), and Diffusion-Based (Diff-UNet)
1. 3D-UNet (2016 Jun)
2. SegResNet (2018 Nov)
3. Swin-UNETR (2022 Jan)
4. Diff-UNet (2023 Mar)
## Reference

[BraTS2020 Dataset](https://www.kaggle.com/datasets/awsaf49/brats20-dataset-training-validation/data)

[MONAI tutorial for 3D-UNet, SegResNet, Swin-UNETR](https://github.com/Project-MONAI/tutorials/tree/main/3d_segmentation)

[Diff-UNet github](https://github.com/ge-xing/Diff-UNet/tree/main)

[3D-UNet paper link](https://arxiv.org/pdf/1606.06650.pdf)

[SegResNet paper link](https://arxiv.org/pdf/1810.11654.pdf)

[Swin-UNETR paper link](https://arxiv.org/pdf/2201.01266.pdf)

[Diff-UNet paper link](https://arxiv.org/pdf/2303.10326.pdf)
