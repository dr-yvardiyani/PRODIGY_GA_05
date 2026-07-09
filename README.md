# PRODIGY_GA_05

## Task 05 - Generative AI Internship @ Prodigy InfoTech

## Neural Style Transfer using TensorFlow Hub

## Overview

This project demonstrates Neural Style Transfer, a deep learning technique that combines the content of one image with the artistic style of another image.

A pre-trained TensorFlow Hub model was used to transfer the artistic style of Vincent van Gogh's famous painting The Starry Night onto a modern dental clinic image. The model preserves the structural content of the dental clinic while applying the visual textures, colors, and brushstroke patterns of the artwork.

## Project Objective

Apply the artistic style of a famous painting to a real-world image using Neural Style Transfer.

## Features

- Neural Style Transfer using a pre-trained TensorFlow Hub model
- Content preservation with artistic style transformation
- Fast image stylization without model training
- Real-world image to artwork conversion
- Implemented in Google Colab

## Dataset

## Images Used

## Content Image
Modern Dental Clinic Interior

## Style Image
Vincent van Gogh's The Starry Night

The content image provides the scene structure, while the style image contributes artistic patterns, textures, and color composition.

## Technologies Used
- Python
- TensorFlow
- TensorFlow Hub
- NumPy
- Matplotlib
- Google Colab

## Model Details

TensorFlow Hub Style Transfer Model
A pre-trained Arbitrary Image Stylization model from TensorFlow Hub was used.

Model Features:

- Content Preservation
- Style Extraction
- Fast Neural Style Transfer
- Real-time Image Stylization

The model extracts artistic characteristics from the style image and applies them to the content image while maintaining the original scene layout.

## Project Workflow
1. Selected a content image (modern dental clinic).
2. Selected a style image (The Starry Night).
3. Loaded both images into the notebook.
4. Imported the TensorFlow Hub style transfer model.
5. Applied Neural Style Transfer.
6. Generated the stylized image.
7. Visualized and compared the content, style, and output images.

## Results

- Successfully applied Neural Style Transfer using TensorFlow Hub.
- Generated a stylized dental clinic image inspired by The Starry Night.
- Preserved the clinic's layout and structural elements.
- Successfully transferred artistic textures, colors, and brushstroke patterns.
- The model successfully transformed the dental clinic image into an artwork inspired by The Starry Night.

## Screenshots
Content and Style Images

TensorFlow Hub Model Loading

Style Transfer Execution

Final Stylized Output

## Repository Structure

PRODIGY_GA_05
│
├── screenshots/
│   ├── content_style_images.png
│   ├── model_loading.png
│   ├── style_transfer_execution.png
│   └── final_output.png
│
├── .gitignore
├── PRODIGY_GA_05_Neural_Style_Transfer.ipynb
├── requirements.txt
├── README.md
└── LICENSE
