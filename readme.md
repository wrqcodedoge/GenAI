# ✨ Awesome visual generative models 🎨🧠
*A reading list for beginners* 📚🌱

---

## 🧬 VAE 🧪
- Auto-Encoding Variational Bayes (VAE)
- Neural Discrete Representation Learning (VQ-VAE)
- Taming Transformers for High-Resolution Image Synthesis (VQGAN)

---

## 🥊 GAN 🎭
- A Style-Based Generator Architecture for Generative Adversarial Networks (StyleGAN)

---

## 🌊 Normalizing Flows 🔁
- Glow: Generative Flow with Invertible 1×1 Convolutions

- STARFlow: Scaling Latent Normalizing Flows for High-resolution Image Synthesis


---

## 🧱 Autoregressive Models 🧠
- Autoregressive Model Beats Diffusion: Llama for Scalable Image Generation
- Visual Autoregressive Modeling: Scalable Image Generation via Next-Scale Prediction
- RandAR: Decoder-only Autoregressive Visual Generation in Random Orders

---

## 🌫️ Diffusion / Flow ⚡
- Score-Based Generative Modeling through Stochastic Differential Equations                
- Flow Straight and Fast: Learning to Generate and Transfer Data with Rectified Flow       
- Understanding Diffusion Objectives as the ELBO with Simple Data Augmentation             
- High-Resolution Image Synthesis with Latent Diffusion Model
- DiT: Scalable Diffusion Models with Transformers


---

## 🧱➕🌫️ AR + Diffusion 🔀
- Autoregressive Image Generation without Vector Quantization

---

## 🎭 Masked Modeling / Masked Diffusion 🥷
- MaskGIT: Masked Generative Image Transformer

---

# 🧪 Downstream 🚀
(1) Controlling image generation
- Adding Conditional Control to Text-to-Image Diffusion Models



(2) Generative model for Image super-resolution
- Scaling Up to Excellence: Practicing Model Scaling for Photo-Realistic Image Restoration In the Wild

- Diffusion Posterior Sampling for General Noisy Inverse Problems





(3) Diffusion distillation
- One-step Diffusion with Distribution Matching Distillation

- Adversarial Diffusion Distillation

- Consistency models

- Simplifying, Stabilizing and Scaling Continuous-Time Consistency Models

- Mean Flows for One-step Generative Modeling



(4) Diffusion + RL

- Flow-GRPO: Training Flow Matching Models via Online RL



# Coding

(1) Classical diffusion model architechture (for class-conditioned generation)
- Unet: https://github.com/openai/guided-diffusion/blob/main/guided_diffusion/unet.py

- Dit: https://github.com/facebookresearch/DiT/blob/main/models.py

- LightingDiT: https://github.com/hustvl/LightningDiT/blob/main/models/lightningdit.py



# Useful blogs

- https://yang-song.net/blog/2021/score/    (https://www.bilibili.com/video/BV1XYiiYXEba/?vd_source=f706732c93d1a9c8fd7357365bc7ce2d)

- https://rectifiedflow.github.io/index.html  (https://www.bilibili.com/video/BV1pqHezrED5/?buvid=YC4A18C88131D84346AAB02C6EA43CAF142E)

- https://diffusionflow.github.io/   The relationship between diffusion and flow

- https://blog.alexalemi.com/kl-is-all-you-need.html  Understand KL divergence



# Good book

- https://probml.github.io/pml-book/book2.html

# Good cource

- Stanford CS236: Deep Generative Models, by Stefano Ermon 


