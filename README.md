

#Text-to-Image Generator with Hugging Face Diffusers

This project uses the Hugging Face `diffusers` library to convert natural language **text prompts into images** using a pre-trained **Stable Diffusion** model.

## ✨ Features

- Generate images from text prompts
- Avoid unwanted features with negative prompts
- Reproducible output using random seed
- Save and store multiple generated images

---

## 📦 Installation

Before running the code, install the required libraries:

```bash
pip install diffusers transformers torch torchvision accelerate safetensors
