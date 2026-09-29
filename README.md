# Deep Learning Coursework

Graduate-level **Deep Learning coursework and implementations** completed as part of my studies in Computer Engineering at **Sharif University of Technology**.

The repository includes five assignments covering deep learning foundations, computer vision, sequence models, generative modeling, and modern vision-language systems. Most implementations are developed with **Python and PyTorch**.

---

## Assignment 01 — Deep Learning Foundations & Optimization

This assignment focuses on the foundations of deep learning and numerical optimization.

It begins with PyTorch fundamentals and basic neural-network training, then moves to implementing a fully connected neural network from scratch using NumPy, including forward propagation, backpropagation, and gradient checking. The final part explores and compares several first- and second-order optimization algorithms on benchmark functions.

**Notebooks**
- `01-pytorch-basics.ipynb`
- `02-neural-network-from-scratch.ipynb`
- `03-optimization-algorithms.ipynb`

---

## Assignment 02 — Computer Vision

This assignment explores several core computer vision tasks using deep neural networks.

The classification section includes a ResNet implementation, feature analysis, and transfer learning experiments. The second notebook develops an end-to-end license plate detection and recognition pipeline using YOLOv8 and an EfficientNet-based recognition model. The final notebook implements U-Net for multi-class semantic segmentation.

**Notebooks**
- `01-image-classification.ipynb`
- `02-object-detection-and-license-plate-recognition.ipynb`
- `03-semantic-segmentation-unet.ipynb`

---

## Assignment 03 — Sequence Models & Large Language Models

This assignment moves from classical sequence modeling toward modern transformer-based language models.

The first part compares RNN, LSTM, and GRU architectures for time-series forecasting. The second notebook implements a compact GPT-2-style model from scratch with PyTorch. The remaining experiments explore parameter-efficient fine-tuning methods such as LoRA and Prefix Tuning, followed by several inference-time reasoning strategies for large language models.

**Notebooks**
- `01-time-series-rnn-lstm-gru.ipynb`
- `02-gpt2-from-scratch-persian.ipynb`
- `03-parameter-efficient-fine-tuning.ipynb`
- `04-llm-reasoning-and-inference.ipynb`

---

## Assignment 04 — Generative Models

This assignment focuses on deep generative modeling through Variational Autoencoders and Diffusion Models.

The VAE notebook studies latent-space representation, reconstruction, sampling, clustering, and visualization. The second notebook implements a Denoising Diffusion Probabilistic Model using a U-Net architecture and extends it to conditional generation with classifier-free guidance.

**Notebooks**
- `01-variational-autoencoder.ipynb`
- `02-ddpm-diffusion-model.ipynb`

---

## Assignment 05 — Vision Foundation Models & Generative AI

This assignment explores more recent developments in computer vision and multimodal deep learning.

The first notebook experiments with DINO and Grounding DINO for self-supervised visual representation learning, attention visualization, and text-guided object detection. The second uses CLIP representations for image optimization and generation. The final notebook explores Stable Diffusion, latent diffusion, cross-attention, and guidance-based image generation.

**Notebooks**
- `01-dino-and-grounding-dino.ipynb`
- `02-clip-guided-image-generation.ipynb`
- `03-stable-diffusion.ipynb`

---

## Technologies

`Python` · `PyTorch` · `NumPy` · `Pandas` · `Matplotlib` · `Scikit-learn` · `Transformers` · `PEFT` · `Diffusers` · `Ultralytics YOLO`

---

## Repository Structure

```text
sharif-deep-learning-coursework/
│
├── README.md
│
└── assignments/
    ├── 01-foundations-and-optimization/
    ├── 02-computer-vision/
    ├── 03-sequence-models-and-llms/
    ├── 04-generative-models/
    └── 05-vision-foundation-models/
```

---

## Academic Context

These notebooks contain selected implementations and experiments completed as part of my graduate **Deep Learning** coursework at **Sharif University of Technology**.

The original coursework has been reorganized for readability and presentation while preserving the main implementations and experimental results.
