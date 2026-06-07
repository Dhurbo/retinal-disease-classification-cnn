# Retinal Disease Classification CNN

A deep learning project for classifying retinal fundus images into four categories: cataract, glaucoma, diabetic retinopathy, and normal. The project uses convolutional neural networks and transfer learning workflows to support automated retinal disease screening from image data.

## Project Overview

Retinal diseases can lead to serious vision loss if they are not detected early. This project explores how computer vision and deep learning can assist in identifying common eye conditions from retinal images.

The notebooks cover dataset preparation, image preprocessing, model training, evaluation, and a basic Streamlit-based user interface for prediction.

## Features

- Multi-class retinal image classification
- Supports four classes: cataract, glaucoma, diabetic retinopathy, and normal
- CNN-based model training with TensorFlow/Keras
- Image preprocessing and augmentation workflow
- Model evaluation using classification reports and confusion matrices
- Streamlit notebook for a simple prediction interface
- Project diagrams and documentation included for presentation and explanation

## Tech Stack

| Area | Tools |
| --- | --- |
| Language | Python |
| Notebook Environment | Jupyter Notebook / Google Colab |
| Deep Learning | TensorFlow, Keras |
| Computer Vision | OpenCV, Pillow |
| Data Processing | NumPy, pandas |
| Visualization | matplotlib, seaborn |
| Evaluation | scikit-learn |
| UI Prototype | Streamlit |

## Dataset Classes

The dataset is organized into four image classes:

```text
dataset/
+-- cataract/
+-- diabetic_retinopathy/
+-- glaucoma/
+-- normal/
```

The dataset folder and `dataset.zip` are intentionally ignored by Git because they are large files. Keep them locally, or provide a dataset download link in this README if you host the dataset externally.

## Project Structure

```text
AI Project/
+-- Milestone1.ipynb
+-- Milestone2.ipynb
+-- milestone3.ipynb
+-- User_Interface.ipynb
+-- Dhurbo_Documentation.pdf
+-- Final_ppt.pptx
+-- MODEL FLOW.png
+-- MODEL TRAING.png
+-- PREPRCOESS.png
+-- cnn.png
+-- cnn2.png
+-- modules.png
+-- modules1.png
+-- user iterface.png
+-- .gitignore
+-- README.md
```

## Notebook Summary

| Notebook | Purpose |
| --- | --- |
| `Milestone1.ipynb` | Initial dataset setup and early project workflow |
| `Milestone2.ipynb` | Main preprocessing, training, evaluation, and model experimentation |
| `milestone3.ipynb` | Additional model training workflow |
| `User_Interface.ipynb` | Streamlit-based user interface prototype |

## Model Approach

The project includes CNN-based image classification using TensorFlow/Keras. The training workflow includes:

- Loading retinal images from class-based folders
- Resizing and preprocessing image data
- Applying image augmentation
- Training CNN/deep learning models
- Evaluating performance with classification metrics
- Testing predictions through a simple user interface

## Setup Instructions

Clone the repository:

```bash
git clone https://github.com/your-username/retinal-disease-classification-cnn.git
cd retinal-disease-classification-cnn
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install tensorflow keras opencv-python pillow numpy pandas matplotlib seaborn scikit-learn streamlit
```

Place the dataset locally using this structure:

```text
dataset/
+-- cataract/
+-- diabetic_retinopathy/
+-- glaucoma/
+-- normal/
```

Then open the notebooks in Jupyter Notebook or Google Colab and run them step by step.

## GitHub Notes

Large dataset and model files are not committed to this repository. The `.gitignore` excludes:

- `dataset/`
- `dataset.zip`
- trained model files such as `.h5`, `.keras`, `.pkl`, `.pt`
- checkpoints and experiment outputs
- virtual environments and cache files
- API keys and `.env` files

This keeps the repository lightweight and professional for GitHub.

## Future Improvements

- Add a clean `requirements.txt`
- Save the final trained model separately
- Add dataset source and download instructions
- Improve the Streamlit app into a standalone `app.py`
- Add accuracy, precision, recall, F1-score, and confusion matrix screenshots
- Add sample prediction images
- Deploy the Streamlit interface

## Repository Name Suggestion

```text
retinal-disease-classification-cnn
```

## GitHub Description

```text
A CNN-based retinal image classification project for detecting cataract, glaucoma, diabetic retinopathy, and normal eye images using deep learning.
```

## Author

Developed as an AI/computer vision project to demonstrate deep learning, image classification, model evaluation, and medical AI application fundamentals.
