# `README.md` — Root

# Deep Learning Coursework

Graduate-level **Deep Learning coursework and implementations** completed as part of my studies in Computer Engineering at **Sharif University of Technology**.

This repository contains selected assignments, experiments, and implementations covering fundamental and modern topics in deep learning using primarily **Python and PyTorch**.

## Topics

- Neural Networks & Backpropagation
- Optimization Algorithms
- Convolutional Neural Networks
- ResNet & Transfer Learning
- Object Detection
- Semantic Segmentation
- RNN, LSTM & GRU
- Transformers & GPT-2
- Parameter-Efficient Fine-Tuning
- Variational Autoencoders
- Diffusion Models
- Vision Transformers
- CLIP
- DINO & Grounding DINO
- Stable Diffusion

---

## Assignments

| Assignment | Topics |
|---|---|
| [01 — Foundations & Optimization](./assignments/01-foundations-and-optimization/) | PyTorch fundamentals, neural networks from scratch, optimization |
| [02 — Computer Vision](./assignments/02-computer-vision/) | ResNet, transfer learning, object detection, segmentation |
| [03 — Sequence Models & LLMs](./assignments/03-sequence-models-and-llms/) | RNN/LSTM/GRU, GPT-2, PEFT, reasoning |
| [04 — Generative Models](./assignments/04-generative-models/) | VAE, DDPM, conditional diffusion |
| [05 — Vision Foundation Models](./assignments/05-vision-foundation-models/) | DINO, Grounding DINO, CLIP, Stable Diffusion |

---

## Repository Structure

```text
sharif-deep-learning-coursework/
│
├── README.md
│
├── assignments/
│   ├── 01-foundations-and-optimization/
│   ├── 02-computer-vision/
│   ├── 03-sequence-models-and-llms/
│   ├── 04-generative-models/
│   └── 05-vision-foundation-models/

```

---

## Tech Stack

- Python
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Hugging Face Transformers
- PEFT
- Diffusers
- Ultralytics YOLO

Additional libraries are used in individual assignments where required.

---

## Notes

This repository contains selected implementations and experiments completed as part of my graduate Deep Learning coursework.

The notebooks have been reorganized and cleaned for readability and reproducibility while preserving the original implementations and experimental results.

---

# `assignments/01-foundations-and-optimization/README.md`

# Assignment 01 — Foundations & Optimization

This assignment focuses on fundamental concepts in **PyTorch, neural networks, backpropagation, and numerical optimization**.

## Notebooks

### 1. PyTorch Basics

[`01-pytorch-basics.ipynb`](./01-pytorch-basics.ipynb)

Introduction to PyTorch and basic deep-learning workflows, including:

- Tensor operations
- Broadcasting and vectorization
- GPU computation
- Dataset and DataLoader usage
- Basic neural network training
- Model saving and loading
- Visualization of network behavior

### 2. Neural Network from Scratch

[`02-neural-network-from-scratch.ipynb`](./02-neural-network-from-scratch.ipynb)

Implementation of a fully connected neural network using **NumPy**, including:

- Affine layers
- ReLU and Sigmoid activations
- Forward propagation
- Backpropagation
- Mean Squared Error
- Gradient checking
- SGD
- Momentum

### 3. Optimization Algorithms

[`03-optimization-algorithms.ipynb`](./03-optimization-algorithms.ipynb)

Implementation and comparison of several optimization methods:

- SGD
- Momentum
- Nesterov Accelerated Gradient
- AdaGrad
- RMSprop
- Adam
- AdaDelta
- Nadam
- Newton's Method
- L-BFGS

The optimizers are evaluated on multiple benchmark optimization functions.

---

# `assignments/02-computer-vision/README.md`

# Assignment 02 — Computer Vision

This assignment explores several fundamental **Computer Vision** tasks using deep neural networks and PyTorch.

## Notebooks

### 1. Image Classification

[`01-image-classification.ipynb`](./01-image-classification.ipynb)

Image classification experiments including:

- ResNet implementation
- BasicBlock and Bottleneck architectures
- CIFAR-10 classification
- Feature extraction
- Feature-map analysis
- t-SNE visualization
- Nearest-neighbor analysis
- Transfer learning on CIFAR-100

### 2. Object Detection & License Plate Recognition

[`02-object-detection-and-license-plate-recognition.ipynb`](./02-object-detection-and-license-plate-recognition.ipynb)

An end-to-end license plate detection and recognition pipeline using:

- YOLOv8
- License plate detection
- Image cropping and preprocessing
- EfficientNet-based recognition
- End-to-end inference pipeline

### 3. Semantic Segmentation

[`03-semantic-segmentation-unet.ipynb`](./03-semantic-segmentation-unet.ipynb)

Implementation of **U-Net** for multi-class semantic segmentation, including:

- Encoder-decoder architecture
- Skip connections
- Transposed convolutions
- Multi-class segmentation
- Training and evaluation

---

# `assignments/03-sequence-models-and-llms/README.md`

# Assignment 03 — Sequence Models & Large Language Models

This assignment covers **sequence modeling, transformer language models, parameter-efficient fine-tuning, and LLM inference techniques**.

## Notebooks

### 1. Time-Series Forecasting with RNNs

[`01-time-series-rnn-lstm-gru.ipynb`](./01-time-series-rnn-lstm-gru.ipynb)

Time-series forecasting experiments using:

- RNN
- LSTM
- GRU
- ARIMA
- SARIMA

Models are evaluated using metrics such as RMSE, MAE, MAPE, and R².

### 2. GPT-2 from Scratch

[`02-gpt2-from-scratch-persian.ipynb`](./02-gpt2-from-scratch-persian.ipynb)

Implementation of a compact GPT-2-style language model using PyTorch.

Main components include:

- Causal Self-Attention
- Transformer Blocks
- MLP layers
- Positional Embeddings
- Autoregressive generation
- Training and evaluation

The model is trained on Persian text data.

### 3. Parameter-Efficient Fine-Tuning

[`03-parameter-efficient-fine-tuning.ipynb`](./03-parameter-efficient-fine-tuning.ipynb)

Comparison of different fine-tuning strategies for language models:

- Full Fine-Tuning
- Prefix Tuning
- LoRA
- Different LoRA ranks
- Custom LoRA implementation

Experiments also compare training efficiency and model behavior.

### 4. LLM Reasoning & Inference

[`04-llm-reasoning-and-inference.ipynb`](./04-llm-reasoning-and-inference.ipynb)

Experimental evaluation of several inference-time reasoning strategies:

- Chain-of-Thought
- Best-of-N
- Beam Search
- Self-Refinement

Experiments are performed on mathematical reasoning problems.

---

# `assignments/04-generative-models/README.md`

# Assignment 04 — Generative Models

This assignment explores two major families of deep generative models: **Variational Autoencoders and Diffusion Models**.

## Notebooks

### 1. Variational Autoencoder

[`01-variational-autoencoder.ipynb`](./01-variational-autoencoder.ipynb)

Implementation and analysis of Autoencoders and Variational Autoencoders.

Topics include:

- Autoencoders
- Variational Autoencoders
- Reparameterization Trick
- Reconstruction Loss
- KL Divergence
- Latent Space Sampling
- Latent Traversal
- t-SNE Visualization
- Clustering in Latent Space

### 2. DDPM Diffusion Model

[`02-ddpm-diffusion-model.ipynb`](./02-ddpm-diffusion-model.ipynb)

Implementation of **Denoising Diffusion Probabilistic Models (DDPM)**.

Topics include:

- Forward diffusion
- Reverse diffusion
- Noise scheduling
- U-Net architecture
- Residual blocks
- Attention
- Timestep embeddings
- Conditional generation
- Classifier-Free Guidance
- FID-based evaluation

---

# `assignments/05-vision-foundation-models/README.md`

# Assignment 05 — Vision Foundation Models & Generative AI

This assignment explores modern **self-supervised vision models, vision-language models, and text-to-image generation systems**.

## Notebooks

### 1. DINO & Grounding DINO

[`01-dino-and-grounding-dino.ipynb`](./01-dino-and-grounding-dino.ipynb)

Experiments with modern vision foundation models, including:

- DINO
- Self-Supervised Learning
- Vision Transformers
- Student-Teacher learning
- Attention visualization
- Grounding DINO
- Text-guided object detection
- Zero-shot detection

### 2. CLIP-Guided Image Generation

[`02-clip-guided-image-generation.ipynb`](./02-clip-guided-image-generation.ipynb)

Experiments using CLIP representations for image optimization and generation.

Topics include:

- CLIP embeddings
- Text-guided image optimization
- Image generation
- Style transfer
- Image reconstruction
- Inpainting
- Multi-resolution optimization

### 3. Stable Diffusion

[`03-stable-diffusion.ipynb`](./03-stable-diffusion.ipynb)

Experiments with Stable Diffusion and latent diffusion concepts, including:

- VAE latent representations
- CLIP text encoding
- U-Net denoising
- Diffusion schedulers
- Classifier-Free Guidance
- Cross-Attention
- Attention visualization
- Latent optimization
- Text-to-image generation

---

## Course Progression

The five assignments collectively cover a progression from deep-learning fundamentals to modern foundation and generative models:

```text
Neural Networks & Optimization
            ↓
      Computer Vision
            ↓
 Sequence Models & LLMs
            ↓
     Generative Models
            ↓
Vision Foundation Models
```
