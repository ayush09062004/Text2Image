# Text2Image
# Text-to-Image Generation using Stable Diffusion and Gradio

This project implements a **Text-to-Image** generation tool using the **Stable Diffusion** model for creating high-quality images based on text prompts. The interface is built with **Gradio**, which allows easy interaction for users to input text prompts and generate images.

## Project Overview

The goal of this project is to enable users to generate images from textual descriptions using a pre-trained **Stable Diffusion** model. Users can adjust several parameters, including the number of inference steps and the image dimensions, to fine-tune the generated images.

### Features
- **Text-to-Image Generation**: Generate images from descriptive text.
- **User Customization**: Adjust **Inference Steps**, **Width**, and **Height** of the generated image.
- **Easy-to-use Interface**: Built with **Gradio** for seamless interaction.
- **Pre-trained Model**: Uses the **Stable Diffusion** model from **Hugging Face**.

## Usage

1. **Run the Interface**:

    After installing the dependencies, you can start the Gradio interface by running:

2. **Input Parameters**:

    The interface allows you to provide the following inputs:
    - **Prompt**: A text description for the image you want to generate.
    - **Inference Steps**: The number of inference steps (default: 50).
    - **Width**: Width of the generated image (default: 512).
    - **Height**: Height of the generated image (default: 768).

3. **Submit to Generate**:

    After entering the desired prompt and adjusting the parameters, click the **Submit** button to generate the image.

    The image will be displayed below the input fields once the generation process is complete.

## Example Prompts

Here are a few example prompts to try:
- "A fantasy landscape with a waterfall and rainbow."
- "An astronaut floating in space surrounded by stars."
- "A portrait of a lion with a crown sitting on a throne."

## Requirements

- Python 3.x
- **Hugging Face Transformers**: For downloading and using pre-trained models.
- **Diffusers**: For image generation with Stable Diffusion.
- **Gradio**: For creating the web interface.

## Model Used

This project uses the **Stable Diffusion** model to generate images based on text prompts. The specific model used here is:

- **Model Name**: `dreamlike-art/dreamlike-diffusion-1.0`
- **Model Source**: [Hugging Face Model Hub](https://huggingface.co)

