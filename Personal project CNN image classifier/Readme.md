# Image-Based CNN-Powered Plant Leaf Disease Classifier

This web app uses a Convolutional Neural Network (CNN) to detect diseases in **tomato, potato, and bell pepper** leaves from images.

## Features
- Upload a leaf image and get instant predictions
- Supports `.jpg`, `.jpeg`, and `.png` formats
- Trained on 16K+ images with class balancing and augmentation
- Built with TensorFlow + Streamlit

## Upload Guidelines
- Use a **clear image of a single leaf**
- Ensure the **leaf is centered** and **background is plain**
- Avoid blurry or shadow-heavy images

## Model Info
- Architecture: 4 Conv2D layers + BatchNorm + Dense
- Accuracy: 98.99% on validation set
- loss: 
- Saved model: `leafy_crop_disease_best_val_loss_v2.keras`

## Data set link  
https://www.kaggle.com/datasets/arjuntejaswi/plant-village

## How to Run
```In "Anconda Prompt" type below lines one by one
pip install -r requirements.txt
streamlit run app.py
