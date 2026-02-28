# 🧍 Human Action Detection using Machine Learning

This project aims to classify human actions based on motion or behavior-related data using traditional machine learning techniques. The notebook demonstrates the full pipeline including data exploration, preprocessing, model training, evaluation, and interpretation.

---

## 📁 Project Structure

- `Human Action Detection.ipynb` – Jupyter Notebook containing the complete implementation.
- `README.md` – Project overview and documentation.
---

## 📦 Requirements

Install the required Python libraries using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## 🛠️ How to Run the Notebook
1. Clone this repository and navigate to the project folder:
```bash
git clone https://github.com/yourusername/Human-Action_Detection.git
cd Human-Action-Detection
```
2. Open the notebook in Jupyter:
```bash
jupyter notebook "Human Action Detection.ipynb"
```
3. Run all the cells in order to:

   Load and explore the dataset

   Visualize class distributions

   Preprocess data (e.g., label encoding, resampling, scaling)

   Train a classification model

   Evaluate the model with accuracy and confusion matrix

   View key insights from model coefficients

## 🧠 Model Summary
Model Used: Logistic Regression and KNN (K-Nearest Neighbors)

Preprocessing:

Label encoding for categorical variables

Scaling using StandardScaler and RobustScaler

Resampling to balance class distribution

Train/Test Split: 80/20

Metrics Used: Accuracy, Confusion Matrix

## 📊 Key Insights
Actions with distinct motion patterns are more separable.

Feature importance from model coefficients shows which signals impact classification.

Resampling significantly improved class balance and model performance.

## 👤 Author
Sivaramakrishnan
GitHub – Si-ra-kri









