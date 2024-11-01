# Plant Disease Classification

## Overview
![Website Screenshot 1](https://raw.githubusercontent.com/Priyanshu1303d/Plant_Disease_Classification/refs/heads/main/website_1.png?token=GHSAT0AAAAAACWWQUDKQJGC62FO2SIAMII6ZZEKCGA)
![Website Screenshot 2](https://raw.githubusercontent.com/Priyanshu1303d/Plant_Disease_Classification/refs/heads/main/website_2.png?token=GHSAT0AAAAAACWWQUDKDECBMDILC7E44ER4ZZEKB3A)

The Plant Disease Classification project is designed to assist in identifying various plant diseases using deep learning techniques. By leveraging a pre-trained model, users can upload images of plants, and the system will analyze them to detect potential diseases. This project aims to help farmers and agricultural professionals make informed decisions to protect crops and ensure a healthier harvest.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)

## Technologies Used
- Python
- TensorFlow
- OpenCV
- NumPy
- Matplotlib
- Matplotlib
- Streamlit

## Dataset
The model is trained on a dataset of plant images labeled with various diseases. This dataset includes categories for healthy plants as well as specific diseases affecting different plants.

## Installation
To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Priyanshu1303d/Plant_Disease_Classification.git
   cd Plant_Disease_Classification
2. Create a virtual environment:
   ```bash
   python -m venv .venv
3. Activate the virtual environment:
  ```bash
.venv\Scripts\activate
```
## Usage
After installation, you can run the application using Streamlit. Execute the following command in your terminal:
```bash
streamlit run app.py
```
This will start a local server, and you can access the application in your web browser at http://localhost:8501.

## How It Works
1. Image Upload: Users can upload images of plants using the web interface.
2. Pre-processing: The uploaded image is pre-processed to match the input size required by the deep learning model.
3. Prediction: The pre-trained model analyzes the image and predicts whether the plant is healthy or affected by a disease.
4. Results Display: The application displays the results, including the predicted disease and confidence score.

