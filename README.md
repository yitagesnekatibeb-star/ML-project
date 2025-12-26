# ML-project
Breast Cancer Detection System
This project implements a Machine Learning solution using a Random Forest Classifier to detect breast cancer from two distinct medical imaging modalities: Ultrasound and Mammography. The system features a comprehensive pipeline for image processing, feature extraction, and real-time prediction via a web interface.

📊 Project Overview

Modality 1: Ultrasound (BUSI Dataset)

Modality 2: Mammography (MIAS Dataset)

Core Algorithm: Random Forest Classifier.

Data Balancing: Utilizes SMOTE (Synthetic Minority Over-sampling Technique) to ensure the model handles class imbalances effectively.

Methodology: Employs an 80/20 train-test split to validate the model's accuracy on unseen data.

📈 Experimental Results (Actual Performance)

The following results were achieved during the final model training:

1. Ultrasound Analysis

Total Dataset: 1,578 images

Training Set (SMOTE Balanced): 2,136 samples

Testing Set (20% Holdout): 316 samples

Test Accuracy: 75.63%

Test AUC-ROC: 0.9032

F1-Score: 0.7574

2. Mammography Analysis

Total Dataset: 1,939 images

Training Set (SMOTE Balanced): 1,590 samples

Testing Set (20% Holdout): 388 samples

Test Accuracy: 75.26%

Test AUC-ROC: 0.9090

F1-Score: 0.7517

📂 Dataset Information

The project is designed to work with the following datasets:

Ultrasound (BUSI): [Insert Dataset Link Here]

Mammography (MIAS): [Insert Dataset Link Here]

Note: The script is configured to look for these datasets within Google Drive at the path /My Drive/breast c.

🛠️ Installation

To set up the environment and install the necessary dependencies, run:

pip install -r requirements.txt


🚀 Execution Guide

Environment: Open the project in Google Colab.

Data Setup: Ensure the datasets are uploaded to your Google Drive in a folder named breast c.

Process: Execute the notebook cells to:

Mount Google Drive for data access.

Extract enhanced features (Intensity, Entropy, GLCM Texture, and Shape Circularity).

Train models and generate evaluation visualizations.

Launch the Gradio Interface for interactive image analysis.

👤 Author

Your Name

Submitted to: [Teacher's Name]

Disclaimer: This system is intended for educational and research purposes only. It is not a substitute for professional medical advice, diagnosis, or treatment.
