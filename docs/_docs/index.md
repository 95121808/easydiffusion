---
title: Stable Diffusion UI v3
permalink: /docs/home/
redirect_from: /docs/index.html
---

The easiest way to install and use [Stable Diffusion](https://github.com/CompVis/stable-diffusion) on your computer.

Does not require technical knowledge, does not require pre-installed software. 1-click install, powerful features, friendly community.

️‍🔥🎉 **New!** Support for SDXL, ControlNet, multiple LoRA files, embeddings (and a lot more) have been added!

# Features in the new v3 Version:
- **No Dependencies or Technical Knowledge Required**: 1-click install for Windows, Mac and Linux. *No dependencies*, no need for WSL or Docker or Conda or technical setup. Just download and run!
- **ControlNet** - Full support for ControlNet, with native integration of the common ControlNet models. Just select a control image, then choose the ControlNet filter/model and run. No additional configuration or download necessary. Supports custom ControlNets as well.
- **SDXL** - Full support for SDXL. No configuration necessary, just put the SDXL model in the `models/stable-diffusion` folder.
- **Multiple LoRAs** - Use multiple LoRAs, including SDXL and SD2-compatible LoRAs. Put them in the `models/lora` folder.
- **Embeddings** - Use textual inversion embeddings easily, by putting them in the `models/embeddings` folder and using their names in the prompt (or by clicking the `+ Embeddings` button to select embeddings visually). Thanks @JeLuf.
- **Seamless Tiling** - Generate repeating textures that can be useful for games and other art projects. Works best in 512x512 resolution. Thanks @JeLuf.
- **Inpainting Models** - Full support for inpainting models, including custom inpainting models. No configuration (or yaml files) necessary.
- **Faster than v2.5** - Nearly 40% faster than Easy Diffusion v2.5, and can be even faster if you enable xFormers.
- **Even less VRAM usage** - Less than 2 GB for 512x512 images on 'low' VRAM usage setting (SD 1.5). Can generate large images with SDXL.
- **WebP images** - Supports saving images in the lossless webp format.
- **Undo in the UI** - Remove tasks or images from the queue easily, and undo the action if you removed anything accidentally. Thanks @JeLuf.
- **Three new samplers, and latent upscaler** - Added `DEIS`, `DDPM` and `DPM++ 2m SDE` as additional samplers. Thanks @ogmaresca and @rbertus2000.
- **Significantly faster 'Upscale' and 'Fix Faces' buttons on the images**
- **Major rewrite of the code** - We've switched to using diffusers under-the-hood, which allows us to release new features faster, and focus on making the UI and installer even easier to use.

![262597678-11089485-2514-4a11-88fb-c3acc81fc9ec](https://github.com/easydiffusion/easydiffusion/assets/844287/050b5e15-e909-45bf-8162-a38234830e38)

## Problems? Troubleshooting
Please try the common [troubleshooting](https://github.com/easydiffusion/easydiffusion/wiki/Troubleshooting) steps. If that doesn't fix it, please ask on the [discord server](https://discord.com/invite/u9yhsFmEkB), or [file an issue](https://github.com/easydiffusion/easydiffusion/issues).

# Bugs reports and code contributions welcome
If there are any problems or suggestions, please feel free to ask on the [discord server](https://discord.com/invite/u9yhsFmEkB) or [file an issue](https://github.com/easydiffusion/easydiffusion/issues).

Also, please feel free to submit a pull request, if you have any code contributions in mind. Join the [discord server](https://discord.com/invite/u9yhsFmEkB) for development-related discussions, and for helping other users.
