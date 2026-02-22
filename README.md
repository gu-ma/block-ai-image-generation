
# Block: AI – Image Generation

This block is an intro to generative models, with a focus on image models. Students move from conceptual framing to practical image workflows: understanding diffusion pipelines, comparing model families, writing stronger prompts, applying fine-tuning methods, and critically evaluating ethical trade-offs.

## Learning Objectives

By the end of this block, you will be able to:

- Explain the core components of modern diffusion-based image generation
- Compare diffusion with autoregressive, GAN, and transformer-based alternatives
- Write effective prompts using structure, negative prompts, and weighting
- Identify when to use LoRA, DreamBooth, and ControlNet for customization
- Apply an iterative, ethics-aware workflow for creative image production

## Session Timeline Overview

- **Part 1 (Lecture + Discussion, ~30–40 min):**
  - Creative process shifts with AI image generation
  - Diffusion pipeline fundamentals
  - Model-family comparison and practical trade-offs
- **Part 2 (Hands-on Studio, ~60–75 min):**
  - Prompt crafting + iteration loops
  - Guided experiments with model settings and constraints
  - Fine-tuning and controllability examples
- **Debrief (10–15 min):**
  - Ethics, authorship, and production reflection

## Part 1: Concepts + Technical Foundations

**Format:** Lecture + guided discussion

- **Slides**
  - [PDF copy (to replace)](./slides/image_gen.pdf)
- **Core notes:**
  - [01 – Image Generation Overview](./content/01-image-generation-overview.md)
  - [02 – Core Components: Diffusion Pipeline](./content/02-core-components-diffusion-pipeline.md)
  - [03 – Alternatives to Diffusion](./content/03-alternatives-to-diffusion.md)

## Part 2: Studio Workflow + Creative Control

**Format:** Hands-on workshop

- **Practice notes:**
  - [04 – Prompt Engineering Basics](./content/04-prompt-engineering-basics.md)
  - [05 – Fine-Tuning Techniques](./content/05-fine-tuning-techniques.md)
  - [06 – Practical Tools, Ethics, and Iterative Practice](./content/06-tools-ethics-and-practice.md)

- **Beginner notebooks (Jupyter / Colab):**
  - [01 – CLIP Intuition](./samples/01-clip-intuition.ipynb)
  - [02 – First Image Generation with Hugging Face](./samples/02-hf-diffusion-first-generation.ipynb)
  - [03- Running Flux on HF](./samples/03-diffusers-flux-quickstart.ipynb)
  - 04 - Using Replicate.

## Preparation (Between classes)

- Read the core notes in order (01→06)
- Read article [How does Stable Diffusion work?](https://stable-diffusion-art.com/how-stable-diffusion-work/)
- Find 3 reference images (style, subject, composition) for prompt testing

## Going Further

- [Kittl: AI Image Generation Guide (pipeline + sampling overview)](https://www.kittl.com/blogs/ai-image-generation-guide-ais/)
- [Mozilla Future Guide: Image Models](https://ai-guide.future.mozilla.org/content/image-models/)
- [Video explainer: model families and generation paradigms](https://www.youtube.com/watch?v=jP2WXIZy6WE)
- [ImgGen: 2026 model landscape overview](https://www.imggen.org/blog/model2026)

## Tools

- [Flux](https://blackforestlabs.ai/)
- [Midjourney](https://www.midjourney.com/)
- [Stable Diffusion](https://stability.ai/)
- [ComfyUI](https://www.comfy.org/)
- [Google Colab](https://colab.research.google.com/)
- [Hugging Face](https://huggingface.co/)
