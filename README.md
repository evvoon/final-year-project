# Drone Image Super-Resolution Enhancement

## Introduction
This project explores the use of advanced super-resolution techniques to enhance the quality of drone-captured images. The integration of AI-driven models, particularly in UAV operations, has enabled drones to capture images in various challenging environments. This project focuses on improving the resolution and quality of such images using deep learning techniques like Generative Adversarial Networks (GANs), Enhanced Super-Resolution GAN (ESRGAN), and other state-of-the-art models.

## Motivation
Drone-captured images often suffer from suboptimal resolution, limiting their utility in fields requiring high precision. The goal of this project is to assess and refine super-resolution models, focusing on improving image detail and quality, which is critical for applications in environmental monitoring, urban planning, and security surveillance.

## Objectives
- Conduct a comparative analysis of various image enhancement models.
- Fine-tune models to improve the resolution of drone-captured images.
- Develop a framework for evaluating the performance of these models in real-world scenarios.

## Methodology
The project explores several image enhancement models, including:
- **Bicubic Interpolation**
- **Deep Convolutional Neural Networks (DeepCNN)**
- **Generative Adversarial Networks (GANs)**
- **ESRGAN and its variations (Real-ESRGAN, BSRGAN, A-ESRGAN, SwinIR)**

Each model was applied to a dataset of 500 images collected from drone imagery and tested under various conditions to assess their performance.

## Dataset
The dataset includes images taken from different terrains, including:
- **Campus Images**: Captured from high vantage points to simulate drone imagery.
- **Drone Datasets**: Images sourced from academic research collections like the Stanford Drone Dataset.

## Results
The models were evaluated both qualitatively and quantitatively using metrics such as:
- **Peak Signal to Noise Ratio (PSNR)**
- **Structural Similarity Index (SSIM)**
- **Learned Perceptual Image Patch Similarity (LPIPS)**
- **Feature Similarity Index (FSIM)**

Fine-tuning Real-ESRGAN led to significant improvements in texture preservation, edge sharpness, and color fidelity in drone images.

## Future Scope
- **Exploration of Emerging Models**: Investigating new models like Stable Diffusion for further image enhancement.
- **Video Enhancement**: Expanding the application to video super-resolution.
- **Optimization for Edge Devices**: Improving model efficiency for real-time deployment on drones.
