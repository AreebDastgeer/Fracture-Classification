# Fracture Classification System

A deep learning-based system to classify medical X-ray images into **fracture** and **non-fracture** categories.

## Project Overview

This project uses **computer vision** and **deep learning** techniques to detect fractures from medical images.  
Key features include:

- Image preprocessing: resizing, normalization, and train-test splitting
- Deep learning model training (ResNet50)
- Model evaluation using standard metrics (accuracy, precision, recall, F1-score)
- Visualization of results and predictions


## Installation

1. Clone the repository:  
```bash
git clone https://github.com/YOUR_USERNAME/FracAtlas.git
cd FracAtlas
```


2. Create a virtual environment and install dependencies:
```bash
python -m venv venv
venv\Scripts\activate  # Windows
# source venv/bin/activate  # macOS/Linux
pip install -r requirements.txt
```

### Usage

Open fracture_classification.ipynb to explore data preprocessing, model training, and evaluation.

Replace 22F-3099_FracAtlas_ResNet50.zip with your own data or model weights if needed.

### Results

Achieved high accuracy in distinguishing fracture vs. non-fracture X-ray images.

Visualizations and performance metrics are included in the notebook.


