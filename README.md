# Pistachio Image Classification Lab

This project builds a machine learning pipeline to classify pistachio images into two species: Kirmizi and Siirt. It uses a Random Forest Classifier and compares the results with a Support Vector Machine (SVM) model.

## How to Run the Project
1. Open Google Colab.
2. Clone this repository or upload the notebook.
3. Install dependencies: pip install kagglehub numpy matplotlib seaborn scikit-learn pillow.
4. Run all cells to download the dataset, preprocess images, train models, and view results.

## Project Steps Implemented
* Data Preprocessing: Downsamples images to 64x64 pixels, converts to grayscale, and applies min-max normalization.
* Model Training: Optimizes Random Forest parameters using 3-Fold GridSearchCV.
* Evaluation: Outputs confusion matrices and classification reports.
* Feature Importance: Plots the top 15 most critical pixel locations.
* Bonus Model: Compares performance against an Optimized Support Vector Machine (SVM).
