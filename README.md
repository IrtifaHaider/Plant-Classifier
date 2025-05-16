# Plant Classification Using HOG Features and Machine Learning

## Overview
This project develops a machine learning pipeline to classify images of 18 plant types (e.g., banana, rice, tomato) using Histogram of Oriented Gradients (HOG) features. Built with Python, it processes RGB images, extracts HOG features, and trains classifiers (SGD and SVM) to achieve accurate plant identification, supporting applications in agriculture and biodiversity.

## Features
- **Image Preprocessing**: Resizes images to 80x80 pixels, converts to grayscale, and handles RGB/grayscale inconsistencies.
- **Feature Extraction**: Uses HOG to extract robust features for classification.
- **Model Training**: Implements a pipeline with SGDClassifier and SVM, optimized via GridSearchCV for hyperparameter tuning.
- **Evaluation**: Visualizes data distribution, confusion matrices, and classification accuracy (up to ~80% on test data).

## Technologies
- **Languages**: Python
- **Libraries**: scikit-learn, skimage, NumPy, pandas, matplotlib, joblib
- **Tools**: GridSearchCV, Pipeline, StandardScaler
- **Classifiers**: SGDClassifier, SVM (linear kernel)

## Key Achievements
- Processed a dataset of diverse plant images with consistent preprocessing.
- Optimized HOG parameters and classifier settings, improving accuracy through cross-validation.
- Visualized results with confusion matrices and sample images for interpretability.

## Usage
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Place plant images in the specified directory (`P:\CSE 458_Machine Learning Lab\00_Project_Plant Classification\plants`).
4. Run `new - Copy.py` to preprocess images, train the model, and evaluate performance.

## Future Improvements
- Incorporate deep learning models (e.g., CNNs) for higher accuracy.
- Expand the dataset to include more plant species.
- Deploy the model as an API for real-time classification.

## Contact
For questions or collaboration, reach out via [GitHub](https://github.com/IrtifaHaider) or [email](mailto:haiderirtifa@gmail.com).

---

*Developed by Irtifa Haider as part of CSE 458 Machine Learning Lab at Jahangirnagar University.*
