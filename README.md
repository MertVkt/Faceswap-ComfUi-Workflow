# Faceswap-ComfUi-Workflow
Faceswap ComfUi workflow inpainting and another stuff


Download comfyui_portrait_lora64.safetensors and place in /models/loras/
https://huggingface.co/ali-vilab/ACE_Plus/tree/main/portrait

Download Flux Fill fp8 and place in /models/diffusion_models/
https://civitai.com/models/969431/flux-fill-fp8

OR Flux Fill fp16 and place in /models/diffusion_models/
https://huggingface.co/black-forest-labs/FLUX.1-Fill-dev
This version is more demanding for your hardware

Download Flux Turbo Lora and place in /models/loras/
https://civitai.com/models/876388/flux1-turbo-alpha

clip_l, t5xxl_fp16 (or t5xxl_fp8) can be downloaded from the model manager

OPTIONAL FOR FUTURE
Download comfyui_subject_lora16.safetensors and place in /models/loras/
https://huggingface.co/ali-vilab/ACE_Plus/tree/main/subject

Download comfyui_local_lora16.safetensors and place in /models/loras/
https://huggingface.co/ali-vilab/ACE_Plus/tree/main/local_editing



SUPER FAST - 8s on 4090
TeaCache ON
Sampler: Euler - 12 steps
Turbo Lora


FAST - 15s on 4090
TeaCache ON
Sampler: Euler - 25 steps



BEST QUALITY - ~40s on 4090
TeaCache OFF
Sampler: Euler Ancestral - 25 steps
