# Breast Cancer Prediction Model

This project implements a machine learning model to predict breast cancer diagnosis using various classification algorithms. The model achieves high accuracy in predicting whether a tumor is malignant or benign based on various features extracted from breast cancer images.

## Features

- Data preprocessing and exploratory data analysis
- Implementation of multiple classification models:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Random Forests
  - Support Vector Machines (SVM)
- Model performance comparison and visualization
- High accuracy prediction (up to 98.24%)
- Cross-validation and hyperparameter tuning
- Feature importance analysis
- Confusion matrix visualization

## Dataset

The dataset used in this project contains features computed from digitized images of fine needle aspirate (FNA) of breast mass. The features describe characteristics of the cell nuclei present in the image.

### Dataset Features
- Number of instances: 569
- Number of attributes: 30
- Target classes: Malignant (M) and Benign (B)
- Features include:
  - radius
  - texture
  - perimeter
  - area
  - smoothness
  - compactness
  - concavity
  - symmetry
  - fractal dimension

## Requirements

- Python 3.x
- Required Python packages:
  - numpy
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn
  - jupyter
  - imbalanced-learn
  - scipy

## Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/breast-cancer-prediction.git
cd breast-cancer-prediction
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the Jupyter notebook:
```bash
jupyter notebook breast-cancer-prediction-accuracy-98-24.ipynb
```

2. Or run the Python script directly:
```bash
python breast-cancer-prediction-accuracy-98-24.py
```

## Model Performance

### Accuracy Scores
- Logistic Regression: 97.37%
- K-Nearest Neighbors: 96.49%
- Random Forests: 96.49%
- Support Vector Machines: 98.24%

### Additional Metrics
- Precision
- Recall
- F1-Score
- ROC-AUC Score

## Model Evaluation
- Cross-validation scores
- Confusion matrix analysis
- ROC curves
- Feature importance rankings
- Learning curves

## Data Preprocessing Steps
1. Missing value handling
2. Feature scaling
3. Feature selection
4. Handling class imbalance (if any)
5. Train-test split (80-20)

## Future Improvements
- Implementation of deep learning models
- Feature engineering
- Hyperparameter optimization using Grid Search
- Ensemble methods
- Web application deployment

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Wisconsin Diagnostic Breast Cancer (WDBC) dataset
- scikit-learn documentation and community
- Research papers and articles referenced in the project

## Contact
For any queries or suggestions, please reach out to [Your Contact Information]

## Citation
If you use this project in your research, please cite: