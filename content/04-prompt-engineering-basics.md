---
title: "04 - Prompt Engineering Basics"
draft: false
---

# 04 - Prompt Engineering Basics

Prompting is not magic wording: it is structured direction for composition, style, and detail.

## Prompt Structure That Works

Use a layered format:

**Subject + Style + Details + Camera/Lighting + Output intent**

Example:

`cyberpunk cat, neon lights, shallow depth of field, cinematic framing, rain-soaked street, high detail`

## Negative Prompts

Negative prompts help remove common artifacts or unwanted traits.

Example:

`blurry, low quality, extra fingers, deformed hands, text artifacts`

Use them as constraints, not as a replacement for a clear positive prompt.

## Prompt Weights

Weighted emphasis can tune priority:

- `(neon lighting:1.2)` increases emphasis
- `(background crowd:0.8)` reduces emphasis

Exact syntax varies by tool, but the idea is consistent: prioritize what matters most.

## Common Pitfalls

1. **Too vague**: “make it cool” gives unstable outputs
2. **Contradictions**: “minimalist but ultra ornate” confuses intent
3. **Over-detailing**: too many constraints can flatten creativity or break composition
4. **No iteration log**: without documenting changes, improvement is hard to reproduce

## Practical Iteration Loop

1. Start with a clear baseline prompt
2. Change one variable at a time (style, lighting, CFG, sampler, etc.)
3. Keep best candidates and annotate why
4. Refine toward your project intent

## Reference

- [AIWiner – AI Image Generation Guide 2026](https://aiwiner.com/ai-image-generation-the-complete-2026-guide-for-creating-stunning-visuals/)
