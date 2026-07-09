# PRODIGY_GA_05
PRODIGY_GA_05
Neural Style Transfer using TensorFlow Hub
Overview

This project demonstrates Neural Style Transfer, a deep learning technique that combines the content of one image with the artistic style of another image.

A pre-trained TensorFlow Hub model was used to transfer the artistic style of Vincent van Gogh's famous painting The Starry Night onto a modern dental clinic image. The model preserves the structural content of the dental clinic while applying the visual textures, colors, and brushstroke patterns of the artwork.

Project Objective

Apply the artistic style of a famous painting to a real-world image using Neural Style Transfer.

Dataset
Images Used
Content Image
Modern Dental Clinic Interior
Style Image
Vincent van Gogh's The Starry Night

The content image provides the scene structure, while the style image contributes artistic patterns, textures, and color composition.

Technologies Used
Python
TensorFlow
TensorFlow Hub
NumPy
Matplotlib
Google Colab
Model Architecture
TensorFlow Hub Style Transfer Model

A pre-trained Arbitrary Image Stylization model from TensorFlow Hub was used.

Model Features:

Content Preservation
Style Extraction
Fast Neural Style Transfer
Real-time Image Stylization

The model extracts artistic characteristics from the style image and applies them to the content image while maintaining the original scene layout.

Style Transfer Process

The following steps were performed:

Load the content image.
Load the style image.
Import the TensorFlow Hub style transfer model.
Generate the stylized output image.
Visualize the content, style, and generated images.
Results

The model successfully transformed the dental clinic image into an artwork inspired by The Starry Night.

The generated image retained the clinic's structure and objects while adopting the painting's characteristic brush strokes, textures, and color palette.

This demonstrates the effectiveness of Neural Style Transfer for combining artistic styles with real-world photographs.

Screenshots
Content and Style Images

TensorFlow Hub Model Loading

Style Transfer Execution

Final Stylized Output

Repository Structure
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
Internship Information

Completed as part of the Generative AI Internship Program at Prodigy InfoTech.
