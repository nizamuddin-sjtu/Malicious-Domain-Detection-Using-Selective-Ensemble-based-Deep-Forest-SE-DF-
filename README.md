# Malicious-Domain-Detection-Using-Selective-Ensemble-based-Deep-Forest-SE-DF-
A machine learning-based system for detecting malicious domains using a novel Selective Ensemble-based Deep Forest (SE-DF) model. This project includes both a Jupyter Notebook for model training and a user-friendly GUI application for real-time domain classification.
**Overview**
This repository contains:
1. Model Training Notebook (malicious_domain_detection.ipynb):
2. Trains a SelectiveDeepForest model using handcrafted features extracted from domain names.
3. Saves the trained model as model.pkl.
3. GUI Application (DomainDetection.ipynb):

Provides an interactive interface to classify domains as Malicious or Benign.

Displays feature values and supports both single and batch domain input.

**Features**
**Feature Extraction:** 23 handcrafted features including:
Length, digit/letter counts, entropy, vowel ratio, positional stats, and more.

**Selective Deep Forest Model:**
Multi-layer Random Forest ensemble.
Tree selection based on AUC score to improve generalization.

**User-Friendly GUI:**
Real-time prediction.
Feature value visualization.
Support for multiple domain inputs.

**Installation & Usage**
1. Install Dependencies
bash
pip install pandas numpy scikit-learn tkinter pillow
2. Train the Model
Run the malicious_domain_detection.ipynb notebook to train and save the model.
3. Launch the GUI
Run the DomainDetection.ipynb notebook to start the classification app.

**GUI Preview**

1. Enter a domain and click Predict.
2. View results with color-coded labels (✅ Benign / ❌ Malicious).
3. See all extracted features in a structured table.

**Project Structure**

├── malicious_domain_detection.ipynb  # Model training
├── DomainDetection.ipynb             # GUI application
├── model.pkl                         # Trained model (generated)
├── domain_classification_dataset.csv # Dataset (not included)
└── logo.png                          # Optional logo for GUI

**Developers**
**Developer:** Nizamuddin & Samar Abbas Mangi

**License**
This project is developed for academic purposes at Shah Abdul Latif University, Khairpur.

**Future Enhancements**
1. Real-time API integration for domain lookup
2. Model explainability (SHAP/LIME)
3. Cloud deployment

**Try it now!**
Clone the repo, train the model, and run the GUI to detect malicious domains with state-of-the-art ensemble learning.

