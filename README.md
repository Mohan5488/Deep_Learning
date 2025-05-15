🥔 Potato Leaf Disease Classification with CNN
This project uses Convolutional Neural Networks (CNN) to detect and classify diseases in potato leaves using the PlantVillage dataset. It includes data extraction, preprocessing, model building, training, and prediction.

📌 Table of Contents
Overview

Dataset

Setup & Installation

How to Run

Model Architecture

Results

Technologies Used

License

🧠 Overview
Potato diseases can significantly impact crop yield. This project leverages CNN models to classify potato leaf images into:

Healthy

Early Blight

Late Blight

📁 Dataset
Source: PlantVillage Dataset

Path after extraction: /content/PlantVillage/PlantVillage

Classes: 3 (Healthy, Early Blight, Late Blight)

🛠️ Setup & Installation
Clone this repo:

bash
Copy
Edit
git clone https://github.com/your-username/potato-disease-classification.git
cd potato-disease-classification
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Upload the dataset to /content/drive/MyDrive/PlantVillage.zip

🚀 How to Run
Open the Jupyter notebook:

bash
Copy
Edit
jupyter notebook Potatao.ipynb
Make sure to mount Google Drive and unzip the dataset:

python
Copy
Edit
from google.colab import drive
drive.mount('/content/drive')
Follow the cells to preprocess the data, build and train the CNN model.

🧱 Model Architecture
Input: Resized 64x64 images

Convolution + MaxPooling layers

Flatten → Dense Layers

Output Layer: 3 classes with softmax activation

📊 Results
Accuracy: (update after training)

Loss: (update after training)

Model performs well on test data and distinguishes between disease types.

🧰 Technologies Used
Python

TensorFlow / Keras

Google Colab

Matplotlib & Seaborn

OpenCV

Pandas & NumPy
