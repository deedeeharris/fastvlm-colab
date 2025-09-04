# FastVLM-0.5B: Efficient Vision-Language Model Image Captioning

This repository contains a Google Colab notebook for demonstrating **FastVLM-0.5B**, Apple's efficient vision-language model. FastVLM-0.5B is designed for high-speed and accurate image captioning and visual question answering, even on resource-constrained devices.

## Features

- **Fast Inference:** Up to 85x faster than previous models like LLaVA-OneVision.
- **Compact Size:** 3.4x smaller, ideal for on-device deployment.
- **Image Captioning:** Generate descriptive captions for any uploaded image.
- **Visual Question Answering:** Ask questions about an image and get relevant answers.
- **Easy-to-Use Colab Notebook:** A simple interface to upload images, input prompts, and get real-time results.

## Getting Started

1. **Open in Colab:** Click the "Open in Colab" badge below to launch the notebook.

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/deedeeharris/fastvlm-colab/blob/main/FastVLM_0_5B_Local_Image_Prediction_COLAB.ipynb){target="_blank"}
   
3. **Run Setup:** Execute the "Setup" cells to install dependencies and load the model.
   *(Optional: Enable GPU for faster processing via `Runtime > Change runtime type > Hardware accelerator > GPU`)*

4. **Upload Image & Prompt:** Use the interactive widgets to:
   - Enter your desired prompt (e.g., "Describe this image," "What is happening here?").
   - Click "Upload Image & Run" to select an image from your local machine.

5. **View Results:** The generated caption or answer will be displayed along with the processing time.

## Example Usage

Here's an example of what you can expect:

**Prompt:** "What does this image show?"

**Generated Caption:** "A person is riding a bicycle on a city street."
