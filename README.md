# Linear Discriminant Analysis (LDA) with Logistic Regression

## 📄 Summary
This project demonstrates the use of Linear Discriminant Analysis (LDA) as a dimensionality reduction technique, followed by Logistic Regression for classification on the Wine dataset.

---

## 📊 Dataset
- **Name**: Wine Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine)
- **Description**: The dataset contains the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars.

---

## 📁 Project Structure
```
linear_discriminant_analysis/
│
├── linear_discriminant_analysis.ipynb   # Main Jupyter notebook
├── Wine.csv                             # Dataset (assumed to be in same directory)
├── README.md                            # Project overview and usage guide
└── CONTRIBUTING.md                      # Guide for contributing
```

---

## 🛠 Requirements
Install dependencies with:
```bash
pip install -r requirements.txt
```

**Main libraries used:**
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

---

## ▶ How to Run
1. Ensure `Wine.csv` is in the same directory.
2. Run the `linear_discriminant_analysis.ipynb` notebook cell-by-cell.
3. Observe training, LDA transformation, logistic regression, and final evaluation metrics.

---

## 📤 Output
- **Confusion Matrix** showing correct vs incorrect predictions
- **Accuracy Score** to evaluate model performance
- **2D Visualization** of LDA-transformed features

---

## 🔍 Details
- **Algorithm**: Linear Discriminant Analysis for dimensionality reduction; Logistic Regression for classification.
- **Distance Metric**: LDA maximizes class separability using the ratio of between-class variance to within-class variance.
- **Model**:
  - Input features reduced to 2 components via LDA
  - Trained using Logistic Regression
  - Evaluated using confusion matrix and accuracy score

---

## 🤔 Understanding
- LDA considers the class labels and attempts to project the data in a way that maximizes class separability.
- It is particularly useful when visualizing high-dimensional data in lower dimensions (e.g., 2D).

---

## 🤝 Contributing
Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details.

---

## 📄 License
This project is licensed under the MIT License.