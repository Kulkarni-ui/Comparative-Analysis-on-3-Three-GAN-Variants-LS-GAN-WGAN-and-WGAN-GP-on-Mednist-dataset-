# 🧠 GAN-Based Image Generation on MedMNIST Dataset

This project applies **Generative Adversarial Networks (GANs)** to generate synthetic images using the **MedMNIST** dataset. The focus is on comparing various GAN variants in terms of quality, training stability, and visual results.

## Objective

To generate and evaluate synthetic medical images using:
- **LS-GAN** (Least Squares GAN)
- **WGAN** (Wasserstein GAN)
- **WGAN-GP** (WGAN with Gradient Penalty)

## Dataset

- **MedMNIST** (PneumoniaMNIST and others)
- Lightweight medical image dataset ideal for GAN training and testing

## Technologies Used

- **Python**, **PyTorch**
- **Torchvision** for data handling
- **TensorBoard** for training visualization
- **Matplotlib**, **NumPy**

## Key Features

- Implementation of three GAN variants
- Training for 50+ epochs to ensure convergence
- Metric-based evaluation: **Inception Score (IS)**, **FID**, and **visual inspection**
- Comparative plots of real vs generated images

## Evaluation Metrics

- **Inception Score (IS)**: Measures image quality and diversity
- **Fréchet Inception Distance (FID)**: Measures similarity between real and generated images
- **Visual Inspection**: Qualitative judgment of outputs

## Future Work

- Train on higher-resolution medical datasets
- Apply **Conditional GANs** for class-controlled generation
- Use GAN outputs for **data augmentation** in downstream classification tasks

## Repository Structure

```
 GAN_MedMNIST_Assignment/
 ┣  GAN_FINAL_4_ASSIGNMENT.ipynb
 ┣  README.md
 ┗  outputs/  (generated images, checkpoints, TensorBoard logs)
```
