# Stable Diffusion & AI Image Prompt Collection

A curated, categorized collection of high-quality prompts for **Stable Diffusion**, **Midjourney**, **DALL·E**, and **Flux** — built from hands-on experimentation. This repo is a living reference I update as I explore AI image generation tools.

---

## Contents

| File | Description |
|---|---|
| `prompts/portrait.md` | Photorealistic and stylized portrait prompts |
| `prompts/product_design.md` | Product photography & commercial use prompts |
| `prompts/cinematic.md` | Film-style, dramatic lighting prompts |
| `prompts/ui_mockups.md` | App UI & web design mockup prompts |
| `prompts/abstract.md` | Abstract, generative art styles |
| `notes/negative_prompts.md` | Useful negative prompts to avoid artifacts |
| `notes/model_notes.md` | Notes on SDXL vs SD1.5 vs Flux differences |

---

## Sample Prompts

### Portrait — Photorealistic
```
RAW photo, a close-up portrait of a 30-year-old woman, 
natural studio lighting, bokeh background, shot on Sony A7IV, 
85mm lens, ultra-detailed skin texture, 8k resolution
Negative: cartoon, painting, blurry, overexposed, deformed
```

### Cinematic Scene
```
cinematic wide shot, abandoned train station at golden hour, 
dust particles in light beams, film grain, anamorphic lens flare, 
color graded like a Denis Villeneuve film, 4k, hyperrealistic
Negative: anime, illustration, low quality, modern, people
```

### Product Photography
```
a minimalist perfume bottle on white marble surface, 
soft diffused studio lighting, luxury brand aesthetic, 
sharp focus product shot, commercial photography, 8k
Negative: blurry, shadow artifacts, text, watermark, deformed bottle
```

### Abstract / Generative Art
```
fluid simulation abstract art, iridescent liquid metal,
flowing organic shapes, macro photography style, 
trending on ArtStation, ultra HD, neon accents on dark background
Negative: text, words, figurative, people, animals
```

---

## Prompt Anatomy

Every great prompt has these layers:

```
[SUBJECT] + [STYLE/MEDIUM] + [LIGHTING] + [CAMERA/LENS] + [QUALITY TAGS]
```

**Example breakdown:**
- Subject: `a cyberpunk street market in Vilnius`
- Style: `cinematic photography, film noir`
- Lighting: `neon lights, rain reflections`  
- Camera: `35mm lens, shallow depth of field`
- Quality: `8k, hyperrealistic, award-winning photography`

---

## Tools Covered

- **Stable Diffusion** (AUTOMATIC1111, ComfyUI)
- **Midjourney v6**
- **DALL·E 3** via ChatGPT / API
- **Flux.1** (Black Forest Labs)
- **Leonardo.ai**

---

## Notes on Models

| Model | Best For | Notes |
|---|---|---|
| SDXL | Photorealism, portraits | Needs good negative prompts |
| SD 1.5 | Speed, flexibility | Huge community LoRA library |
| Flux.1 | Prompt adherence | Excellent for text in images |
| Midjourney v6 | Aesthetics, art | Less controllable but stunning |

---

## How to Use

1. Pick a prompt from any category
2. Modify the subject to your needs
3. Keep the style/lighting/quality tags
4. Test and iterate — small word changes = big visual differences
5. Save what works in your own notes

---

## 🔗 Resources

- [Civitai](https://civitai.com) — Models, LoRAs, community prompts
- [PromptHero](https://prompthero.com) — Searchable prompt gallery
- [ComfyUI GitHub](https://github.com/comfyanonymous/ComfyUI) — Node-based SD interface
- [Hugging Face](https://huggingface.co) — Free model hosting & inference API

---

## About

I'm a first-year Applied AI student at VGTU (Vilnius Tech) exploring the intersection of generative AI and practical creative tools. This repo documents my learning in AI image generation — part of a broader interest in AI automation and creative workflows.

Feel free to use, fork, or contribute prompts!

---
*Last updated: April 2026*
