# DiffusionWizard
A collection of Jupyter notebooks that can be used to generate images using various Stable Diffusion checkpoints.

Do you want to run an image generation model you found on CivitAI on Google colab? Well, these notebooks are probably all you need. Currently, the following functionality is tested and available:

- Generate images using checkpoint merges that have Stable Diffusion 1.5 as the base model. You can adjust the number of inference steps, guidance scale, seed, more.
- Automatically convert safetensors to a format that `diffusers` can handle.
- Upscale images

The idea is to just enter a prompt, a negative prompt, and (optionally) other details, and hit a button to generate an image. That's how easy it is now. If you like the image, you can download it or move it to your Google Drive.

Screenshots:

<img src="https://raw.githubusercontent.com/hathibelagal-dev/DiffusionWizard/refs/heads/main/assets/shot1.png" width="520px"/>
