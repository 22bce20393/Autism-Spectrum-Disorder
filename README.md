# 🧠 Autism Spectrum Disorder Classification

This project focuses on classifying Autism Spectrum Disorder (ASD) using facial image data. It uses both **transfer learning (VGG16, InceptionV3)** and a **hybrid approach** involving traditional ML models like Logistic Regression, Random Forest, and XGBoost.

  📂 Project Structure
├── models/ # Saved trained models
├── data/ # Preprocessed image dataset
├── feature_extraction/ # Scripts to extract features using CNNs
├── ml_models/ # ML training on extracted features
├── predict_single.py # Predict ASD from a new image
├── utils/ # Helper functions (preprocessing, plotting)
├── README.md # Project documentation
├── requirements.txt # Required Python packages

  🧠 Techniques Used
- ✅ VGG16 and InceptionV3 (Transfer Learning)
- ✅ Feature extraction using CNNs
- ✅ Training Logistic Regression, Random Forest, XGBoost
- ✅ Evaluation with Accuracy, F1-score, Confusion Matrix
- ✅ Visualizations: Heatmaps, accuracy/loss plots
- ✅ Single image classification pipeline
