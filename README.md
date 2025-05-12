# Comparative Analysis of GAN, CGAN and VAE

This project presents a detailed implementation and comparison of Generative Adversarial Networks (GANs), Conditional GANs (CGANs), and Variational Autoencoders (VAEs) using the MNIST and Fashion-MNIST datasets. The goal is to analyze their image quality, training stability and latent space representation.

📁 Datasets Used
MNIST Digits: 70,000 images of handwritten digits

Fashion-MNIST: 70,000 images of fashion items

🚀 Model Architectures
1. GAN
- Generator and Discriminator use linear layers and LeakyReLU activations.

- Trained using Binary Cross-Entropy loss.

2. CGAN
- Conditions both generator and discriminator on class labels.

- Label embeddings are concatenated with noise or image input.

- Helps generate class-specific digits.

3. VAE
- Encoder compresses input into latent vector with mean and variance.

- Decoder reconstructs image from sampled latent vector.

- Loss = Reconstruction Loss + KL Divergence

More information is provided in Architecture and Analysis.pdf.

📊 Evaluation Metrics
- Loss Curves for generator and discriminator

- Latent Space Visualization using PCA

- Generated Image Samples

- Training Stability & Convergence Speed
