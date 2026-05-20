# Plant Disease Prediction Using CNN & Deep Learning

An end-to-end Computer Vision application built with Python that classifies crop leaf health conditions using a Convolutional Neural Network (CNN). The trained neural network model is deployed as a production-ready, interactive web tool available globally.

## 🚀 Live Demo
Before that download test_images in your local computer
Test the live web application here:  
👉 **[https://plant-disease-detection-using-cnn-deep-learning.streamlit.app/](https://plant-disease-detection-using-cnn-deep-learning.streamlit.app/)**

---

## 📊 Dataset & Model Assets
* **Dataset Source:** [Kaggle PlantVillage Dataset](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset) — A comprehensive, open-source repository containing healthy and pathologically infected crop foliage images.
* **Trained Model Weights Binary (.h5):** [Google Drive Backup Link](https://drive.google.com/file/d/1rKh-IElSdHTqax7XdfSdZTn-r8T_qWPf/view?usp=drive_link) *(Note: The production Streamlit app pulls this layer automatically using Git LFS setup within this repo).*

---

## 📂 Repository Structure

```text
├── app/
│   ├── main.py                 # Streamlit web application dashboard entrypoint
│   ├── requirements.txt        # Host-environment production dependencies
│   ├── class_indices.json      # Dictionary mapping index labels to disease names
│   ├── config.toml             # Streamlit thematic and execution styling configuration
│   └── credentials.toml        # Deployment verification tokens
├── model_training_notebook/
│   └── Plant_Disease_Prediction_CNN_Image_Classifier.ipynb  # Comprehensive model design notebook
├── test_images/                # Validation images for immediate interface testing
│   ├── test_apple_black_rot.JPG
│   ├── test_blueberry_healthy.jpg
│   └── test_potato_early_blight.jpg
├── .gitattributes              # Git LFS tracking configuration for tracking large binaries
├── .gitignore                  # Extraneous local data filters (prevents venv and cache uploads)
└── README.md                   # Technical documentation and system instructions
