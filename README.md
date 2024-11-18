
# CycleGAN and DCGAN Implementation

This repository contains implementations of CycleGAN and DCGAN for image-to-image translation and image generation tasks, respectively. The models are trained on custom datasets and the CIFAR-10 dataset, showcasing adversarial training and generative capabilities.

---

## Features
- **CycleGAN**:
  - Translates images between two domains (e.g., domain A and domain B).
  - Includes cycle-consistency and identity loss for stable training.
  - Demonstrates image translation with real examples.
- **DCGAN**:
  - Generates realistic images using a deep convolutional architecture.
  - Allows experimentation with latent dimensions and learning rates.
  - Visualizes generated samples during training.

---

## Getting Started

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CycleGAN-and-DCGAN-Implementation.git
   cd CycleGAN-and-DCGAN-Implementation
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Training
#### CycleGAN:
1. Place your datasets in the `datasets` directory with the following structure:
   ```
   datasets/
       train_a/
       train_b/
       test_a/
       test_b/
   ```
2. Run the CycleGAN training script:
   ```bash
   python train_cyclegan.py
   ```

#### DCGAN:
1. Download and prepare the CIFAR-10 dataset (automatically handled in the script).
2. Run the DCGAN training script:
   ```bash
   python train_dcgan.py
   ```

---

## Results
- **CycleGAN** results include translated images, reconstructed images, and insights into model performance.
- **DCGAN** results include generated images sampled during training.

---

## Future Improvements
- Increase training epochs for better results.
- Experiment with alternative loss functions.
- Incorporate advanced GAN stabilization techniques.

---
