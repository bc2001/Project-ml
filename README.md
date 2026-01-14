 -----------------------------------Flora Diagnosis Using Convolutional Neural Network (CNN)----------------------------------------


📌 Project Overview


Flora Diagnosis is a deep learning–based system designed to automatically detect and classify plant leaf diseases using Convolutional Neural Networks (CNNs). The project aims to assist farmers and agricultural stakeholders by providing an accurate, efficient, and user-friendly disease detection solution, reducing crop loss and improving agricultural productivity.
The model is trained on a large-scale plant disease dataset and is capable of classifying 38 different disease and healthy leaf categories across multiple crops including Apple, Tomato, Potato, Grape, Corn, and more.

🚀 Key Features
Automated plant leaf disease detection using CNN

Supports 38 disease classes across multiple crop types

Handles real-world challenges such as varying illumination, backgrounds, and image resolution

Achieves high training and validation accuracy (~97%)

Streamlit-based web interface for real-time image upload and prediction

Scalable architecture suitable for web and mobile deployment

🧠 Tech Stack
Programming Language: Python

Deep Learning: Convolutional Neural Networks (CNN)

Frameworks & Libraries: TensorFlow, Keras, NumPy, OpenCV, Matplotlib

Frontend: Streamlit

Dataset: PlantVillage Dataset (87,082 images, 38 classes)

Model Output: Multi-class disease classification

🏗️ System Architecture
Image Upload via Web Interface

Image Preprocessing (Resize, Normalize, RGB Conversion)

CNN-based Feature Extraction

Disease Classification using Softmax

Result Display with Predicted Disease Label

📊 Results
Trained on 87,082 images resized to 256×256

Achieved ~98% training accuracy and ~97% validation accuracy

Loss reduced consistently across 10 epochs

Successfully deployed using Streamlit for interactive predictions

▶️ How to Run the Project
bash
Copy code
pip install -r requirements.txt
streamlit run main.py
Upload a leaf image through the UI to get instant disease prediction.

🎯 Use Cases
Farmers for early disease detection

Agricultural institutes and researchers

Precision agriculture solutions

Educational and research purposes
