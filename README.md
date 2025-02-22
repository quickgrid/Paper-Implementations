# Paper-Implementations

Implementation attempts of various AI papers in simple form etc for my learning purposes. These implementations are not meant to be exact and are categorized into a general section. 

**WARNING: Codes may be incomplete, will likely have bugs, mistakes. Reports for any bugs, mistakes welcome.** 

:rocket: Represents I am fairly confident implementation works **(some things may not be same as defined in paper)** on custom dataset and at least part of it is close enough to proposed paper topic. 

In newer codes mostly tried to follow [PEP 8](https://www.python.org/dev/peps/pep-0008/) and [google python style guide](https://google.github.io/styleguide/pyguide.html). Old codes have poor coding conventions and quality.

## Pytorch

| Topic | Code |
| --- | --- |
| **Generative Adverserial Networks (GAN)** | :rocket: [Generative Adversarial Networks (GAN)](pytorch/gan) |
|  | :rocket: [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks (DCGAN)](pytorch/dcgan) |
|  | :rocket: [Wasserstein GAN (WGAN)](pytorch/wgan) |
|  | :rocket: [Improved Training of Wasserstein GANs (WGAN-GP)](pytorch/wgan-gp) |
|  | :rocket: [Conditional Generative Adversarial Nets](pytorch/conditional-wgan) |
|  | [Semantic Image Synthesis with Spatially-Adaptive Normalization (GauGAN/SPADE)](pytorch/gaugan) |
|  | [Progressive Growing of Gans for Improved Quality, Stability, and Variation (ProGAN)](pytorch/progan) |
|  |  |
| **Denoising Diffusion** | :rocket: [Denoising Diffusion Probabilistic Models (DDPM)](pytorch/ddpm) |
|  | :rocket: [Denoising Diffusion Implicit Models (DDIM)](pytorch/ddim) |
|  |  |
| **Multimodal** | [Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding (Imagen)](pytorch/imagen) |
|  |  |
| **Transformers, Attention Mechanisms** | :rocket: [Attention is all you need (Transformers, Self Attention, Multi-Head Self Attention)](pytorch/self-attention) |
|  |  |
| **Neural Style Transfer** | [Image Style Transfer Using Convolutional Neural Networks (NST)](pytorch/neural-style-transfer) |
|  |  |
| **Knowledge Distillation** | :rocket: [Distilling the Knowledge in a Neural Network (Knowledge Distillation)](pytorch/knowledge-distillation) |
|  |  |
| **Vision Transformer** | :rocket: [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale (ViT)](pytorch/vision_transformer) |
|  |  |
| **Image Segmentation** | [U-Net: Convolutional Networks for Biomedical Image Segmentation (UNet)](pytorch/u-net) |
|  |  |
| **Verification, Recognition, Clutering** <br> TAG: `Siamese Network (Siam)` | :rocket: [FaceNet: A Unified Embedding for Face Recognition and Clustering (Triplet Loss)](pytorch/siamese-triplet-loss) |
|  | :rocket: [Siamese Neural Networks for One-shot Image Recognition](pytorch/siamese-contrastive-loss) <br>  &nbsp; &nbsp;  &nbsp; [Dimensionality Reduction by Learning an Invariant Mapping (Contrastive Loss)](pytorch/siamese-contrastive-loss) |
|  |  |
| **Implicit Representations** | [Implicit Neural Representations with Periodic Activation Functions (SIREN)](pytorch/siren) <br> [COIN: COmpression with Implicit Neural representations](pytorch/siren) |


## Tools

Various tools useful for custom training. These are not paper implementation.

| Topic | Code |
| --- | --- |
| **Image Resize, Verification** | :rocket: [Fast full image dataset resize and corrupted, low resolution image remover](tools/image-verification/) |
| **Image Captioning** | :rocket: [Image to text caption generation](tools/image-captioning/) |
| **Embedding, Feature extraction** | :rocket: [Embedding Generation, Feature Extraction from Text and Images](tools/feature-extraction/) |
| **Image Depth Generation** | [Generates depth images from single or multiple image](tools/image-depth/) |
| **Image Segmentation Generation** | [Generates semantic, instance, panoptic etc. segmentation images from an image](tools/image-segmentation/) |
|  |  |


## Papers of Interest

Papers links are available here, https://github.com/quickgrid/AI-Resources/blob/master/papers.md.

