---
title: "05 - Fine-Tuning Techniques"
draft: false
---

# 05 - Fine-Tuning Techniques

Base models are powerful, but production workflows often require custom adaptation for style, identity, or controllability.

## 1) LoRA (Low-Rank Adaptation)

- Lightweight method to adapt a base model without full retraining.
- Useful for style packs, character looks, or domain-specific visual language.
- Practical advantage: small files, easy to switch/combine in workflows.

## 2) DreamBooth

- Personalization method that teaches a model a specific subject/identity.
- Can work with relatively small image sets (often 3–5+ high-quality images for starter experiments).
- Strong for “this exact subject in different contexts,” but quality depends on dataset consistency.

## 3) ControlNet

- Adds structural guidance using auxiliary conditions (pose, depth, edges, segmentation, etc.).
- Great when composition must be controlled, not just style.
- Frequently used for repeatability in pipelines where layout matters.

## When to Use What

- **LoRA:** style/subject adaptation with lightweight deployment
- **DreamBooth:** personalized subject fidelity
- **ControlNet:** composition and structure control

Many professional workflows combine these methods depending on project constraints.

## Reference

- [Mozilla Future Guide – Image Models](https://ai-guide.future.mozilla.org/content/image-models/)
