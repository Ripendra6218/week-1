# Week 2 - E-Waste Image Classification (EfficientNetV2B0)

## ✅ Tasks Completed:
- Uploaded and managed the dataset manually in Google Colab (`train.zip`, `test.zip`, `val.zip`)
- Extracted datasets into `/content/train`, `/content/test`, and `/content/val` using Python's `zipfile` module
- Performed preprocessing including resizing and normalization of images
- Visualized data distribution and sample images for EDA
- Built and trained a Convolutional Neural Network using EfficientNetV2B0 (Transfer Learning)
- Achieved ~96% test accuracy
- Evaluated the model using classification report and confusion matrix

## 📁 Files Included:
- `ripendra E_Waste_Generation_Classification` – Complete code for preprocessing, EDA, model training, and evaluation

## 🧰 Tools & Libraries Used:
- Python
- TensorFlow & Keras
- Matplotlib & Seaborn
- Google Colab
- image_dataset_from_directory()

## 📍 Notes:
- The datasets were originally in `.zip` format (`train.zip`, `test.zip`, and `val.zip`) and **manually uploaded** to Google Colab
- Each was extracted into separate folders (`/content/train`, `/content/test`, and `/content/val`) using the Python `zipfile` module
- The model was trained entirely in Google Colab using the uploaded datasets
