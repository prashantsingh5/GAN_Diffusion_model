# Project Description

## Text to Image generation

This project is a Text-to-Image Generator that utilizes a diffusion model to create high-quality images based on user-provided text prompts. The model takes various input parameters, including prompt text, strength, CFG scale, sampler type, and seed, to generate detailed and customizable images.

The project uses Gradio to provide an interactive web-based interface, making it easy for users to input their parameters and view the generated images instantly. The model is built on top of state-of-the-art diffusion techniques and leverages the CLIPTokenizer for text processing.

Key Features:
1. Text Prompt Input: Generate images based on detailed descriptions.
2. Strength Control: Adjust the level of noise to influence the abstraction level of the generated image.
3. CFG Scale: Modify the guidance scale for the model to follow the text prompt more or less strictly.
4. Multiple Samplers: Choose from different sampling methods like DDPM, PNDM, LMS, and Heun.
5. Gradio Interface: A user-friendly interface to interact with the model, offering real-time image generation.

link:
Download weights and tokenizer files:
Download v1-5-pruned-emaonly.ckpt from [https://huggingface.co/runwayml/stable-diffusion-v1-5/tree/main](https://huggingface.co/runwayml/stable-diffusion-v1-5/tree/main) and save it in the data folder
