# Building Generative AI Applications with Gradio

![image](https://github.com/user-attachments/assets/52c977fe-f5f0-4b39-9788-8dc1f0c81116)


## Overview
This repository contains a collection of generative AI applications built using Gradio, a user-friendly UI library for creating web-based machine learning demos. The projects utilize various models available on Hugging Face, including both open-source and gated models, along with OpenAI's API. Each application demonstrates the power of generative AI across different domains, including natural language processing (NLP), image captioning, and more.

## Tools and Platforms
- **Gradio**: A Python library for creating simple, interactive web interfaces for machine learning models.
- **Hugging Face API**: A platform for accessing a wide range of pre-trained models for NLP and other tasks.
- **OpenAI API**: Provides access to cutting-edge language models for generating human-like text.
- **Pretrained Models**: A mix of open-source and gated models from Hugging Face, tailored for specific generative tasks.

## Sub-Projects

### 1. NLP Tasks with a Simple Interface
An application that allows users to perform various NLP tasks such as text summarization, translation, and sentiment analysis using a simple Gradio interface. The app leverages models from Hugging Face to process and generate text.

### 2. Image Captioning App
This app generates descriptive captions for images. Users can upload an image, and the model will generate a corresponding caption. The backend is powered by pre-trained image captioning models from Hugging Face.

### 3. Image Generation App
An application that enables users to generate images from text prompts using powerful image generation models. The interface is designed to be intuitive, allowing users to input a prompt and receive a generated image in real-time.

### 4. Describe and Generate Game
A fun and interactive game where users describe an object or scene, and the application generates an image based on the description. This project combines the capabilities of both NLP and image generation models to create an engaging experience.

### 5. Chat with Any LLM
A chat application that allows users to interact with various large language models (LLMs). The interface supports conversation with different models, providing an opportunity to explore their unique capabilities and behaviors.

## Setup and Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/aftabbs/Building-Generative-AI-Applications-with-Gradio.git
    cd Building-Generative-AI-Applications-with-Gradio
    ```

2. **Install the required libraries**:
    ```bash
    pip install gradio transformers openai
    ```

3. **Set up API keys**:
   - Obtain API keys from Hugging Face and OpenAI.
   - Store them securely, either as environment variables or in a configuration file.

4. **Run the applications**:
   Navigate to the folder of the sub-project you want to run and execute:
    ```bash
    python app.py
    ```

## Usage
Each application can be accessed via a local web interface provided by Gradio. Users can interact with the models by uploading images, entering text, or typing prompts, depending on the application's functionality.

## Results
These applications demonstrate the versatility of generative AI, offering practical solutions and engaging experiences across various tasks, from text processing to image generation.

## Future Enhancements
- Expand the range of models and tasks supported.
- Improve the UI/UX of the applications.
- Integrate additional generative AI tools and platforms.


