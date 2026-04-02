# Negative Prompts Reference

Negative prompts tell the model what to *avoid*. These are battle-tested.

---

## Universal Negative Prompt (use on everything)
```
worst quality, low quality, normal quality, lowres, low details, 
oversaturated, undersaturated, overexposed, underexposed, 
grayscale, bw, bad photo, bad photography, bad art, watermark, 
text, logo, letterboxed, distorted, jpeg artifacts, deformed, 
ugly, bad anatomy, disfigured, poorly drawn face, mutation, 
mutated, extra limbs, cloned face, extra fingers, missing fingers
```

## For Portraits — Extra
```
cartoon, anime, painting, illustration, cgi, render, 3d, 
blurry background, fake, plastic, doll, mannequin
```

## For Landscapes / Architecture
```
people, crowds, overcast, grey sky, power lines, modern buildings (if going historical),
oversaturated colors, haze, fog (unless intended)
```

## For Product Photography
```
shadow artifacts, reflection artifacts, multiple products, 
background clutter, text on product, deformed packaging,
bad proportions, distorted shape
```

## For Abstract / Art
```
realistic, photographic, human face, text, words, letters,
figurative, traditional, flat, basic
```

---

## Notes
- In AUTOMATIC1111 you can save negative prompts as **styles** so you don't retype them
- In ComfyUI use a dedicated `CLIPTextEncode` node for negative conditioning  
- SDXL responds better to descriptive negatives than SD 1.5
- Flux.1 largely ignores negative prompts — focus on positive prompt quality instead
