# Image-Caption-Generator

This project is a deep learning-based Image Caption Generator that can analyze the content of an image and generate a meaningful natural language description. It uses **DenseNet-201** as a Convolutional Neural Network (CNN) for image feature extraction and **LSTM (Long Short-Term Memory)** networks for caption generation.

## Demo
Upload an image, and the model will return a caption describing the image content.

## Features
- **DenseNet-201** as CNN for image feature extraction.
- **LSTM** for generating captions based on extracted image features.
- Trained on the **Flickr8k** dataset for caption generation.
- **TensorFlow** and **Keras** for model building and training.
- Text tokenization and padding for processing captions.
- Able to generate human-readable, contextually relevant captions.

## Technologies Used
- **DenseNet-201**, **CNN**, **LSTM**
- **TensorFlow**, **Keras**
- **NumPy**, **Pandas**, **Matplotlib**
- **Python**

## Dataset : Flickr8k Dataset

## How to Run

1. **Clone the repository:**
```bash
git clone https://github.com/Teena-Sapra/Image-Caption-Generator.git
cd Image-Caption-Generator
```

2. **Install Dependencies**
```bash
pip install -r requirements.txt
```

3. **Run Streamlit app**

4. **Upload an image and get the predicted caption.**

