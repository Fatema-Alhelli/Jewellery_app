# 💎 Jewelry Visual Search Engine

A visual search engine that finds visually similar jewelry images from a jewelry catalog.

## 🔍 How It Works

- Images are processed using **MobileNetV2**
- Visual embeddings are extracted from the images
- **Nearest Neighbors** is used to find similar images
- Users can **upload an image** or **take a photo**
- The application displays visually similar jewelry items

## 🛠️ Technologies

- Python
- TensorFlow / Keras
- MobileNetV2
- NumPy
- Scikit-learn
- Streamlit
- PIL

## 📂 Project Files

- `prepare_data.py` — Generates and saves image embeddings
- `Jewellery_app.py` — Streamlit application
- `jewelry_embeddings.npz` — Saved image embeddings and image paths
- `requirements.txt` — Required libraries

## 📊 Dataset

**Tanishq Jewellery Dataset**

## 🚀 Application

The application allows users to upload a jewelry image or take a photo and find visually similar jewelry items.
