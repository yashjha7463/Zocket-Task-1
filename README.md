# Generative AI for Visual Tasks

This repository contains a Jupyter Notebook (`task-1.ipynb`) that demonstrates the use of Generative AI and image classification techniques for various visual tasks. The notebook covers the following topics:

## 1. Generative AI for Visuals

In this section, the notebook showcases the use of Stable Diffusion, a state-of-the-art generative AI model, for generating images from text prompts. The code includes:

- Installation of required libraries (`accelerate`, `diffusers`, and `keras_cv`)
- Loading and configuring the Stable Diffusion model
- A function to generate images from text prompts
- Example usage of the image generation function with the prompt "Car"
- Plotting the generated images using `matplotlib`

## 2. Product Recognition (Image Classification)

This section focuses on image classification using pre-trained models like EfficientNetV2B0 and MobileNetV2. The code includes:

- Loading the pre-trained EfficientNetV2B0 model for image classification
- Functions for preprocessing and classifying images
- Example usage of the classification functions on the previously generated images
- Commented code for using the MobileNetV2 model for classification

## 3. Exclusion of Non-Relevant Images

In this section, the notebook provides a mechanism to filter out images that do not contain any of the specified target products. This ensures that only relevant visuals are processed and enhanced. The code includes:

- A function `find_target_products` that searches for the target products in the classification results
- Example usage of the `find_target_products` function with a target product "sports_car"

## Usage

To use this notebook, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies (`accelerate`, `diffusers`, `keras_cv`, `tensorflow`, `numpy`, `pandas`, and `matplotlib`).
3. Open the `task-1.ipynb` notebook in your preferred Jupyter environment.
4. Run the notebook cells to execute the code and explore the different sections.

Note: Due to the large size of the pre-trained models and computational requirements, some cells may take a significant amount of time to execute, particularly on systems with limited resources.

## Acknowledgemet 
I have used the help of LLMs like Claude and ChatGPT for this.
