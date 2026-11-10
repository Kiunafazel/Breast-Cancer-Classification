# Breast Cancer Prediction 🎗️

A Machine Learning project that classifies breast tumors as **Benign** or **Malignant** using Logistic Regression.

## 📊 Dataset

[Breast Cancer Wisconsin (Diagnostic)](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

The dataset contains 569 samples and 30 numerical features describing cell nuclei characteristics, such as radius, texture, perimeter, and area.

- `M`: Malignant (1)
- `B`: Benign (0)

## 🧪 Project Workflow

1. Removed the `id` column.
2. Converted diagnosis labels (`M` and `B`) into numerical values (`1` and `0`).
3. Normalized features using Min-Max Scaling.
4. Split the dataset into training and testing sets (85% / 15%) using stratified sampling.
5. Trained a Logistic Regression model.
6. Evaluated the model using accuracy, confusion matrix, and classification report.

## 📈 Results

The model achieved approximately **89.5% accuracy** on the test set in the previously reported results.

## 🚀 Installation & Usage

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook:

```bash
jupyter notebook Breast-Cancer-Prediction.ipynb
```

## 🛠️ Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
