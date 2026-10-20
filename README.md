# 🤖 Machine Learning Foundations: Master Curriculum & Practice Hub

> **A Complete, Step-by-Step, Rigorous Curriculum from Python & Mathematical Foundations to Advanced Gradient Boosting, Production Pipelines, Deep Learning with PyTorch, and Hands-on Projects.**

This repository is built for **rigorous self-study, research foundations, and hands-on practice**. Every module includes conceptual intuition, mathematical derivations, clear code implementations, and project templates for active skill enhancement.

---

## 🗺️ Master Curriculum Roadmap

```text
[ Phase 1: Python & Data Science Tooling ]
  │── 01. Python Basics & Operators
  │── 02. Data Structures (Lists, Tuples, Sets, Dictionaries)
  │── 03. Functions & Functional Paradigms
  │── 04. Object-Oriented Programming (OOP) in Python
  │── 05. NumPy for Numerical Computing & Linear Algebra
  │── 06. Pandas for Data Manipulation & Wrangling
  └── 07. Data Visualization with Matplotlib & Seaborn
  │
  ▼
[ Phase 2: Data Preprocessing & Feature Engineering ]
  │── 08. Feature Scaling, Train/Test Split & PCA (Dimensionality Reduction)
  └── 09. Outlier Detection (IQR, Z-Score) & Categorical Encoding (One-Hot, Ordinal, Label)
  │
  ▼
[ Phase 3: Classical Supervised Learning ]
  │── 10. Linear Regression (Simple & Multiple, OLS, Gradient Descent)
  │── 11. Logistic Regression & Binary/Multiclass Classification
  │── 12. Model Persistence (Pickle, Joblib)
  │── 13. k-Nearest Neighbors (k-NN) Classification & Distance Metrics
  │── 14. Decision Trees & Cross-Validation Strategies
  │── 15. Support Vector Machines (SVM, Kernels, Hyperplanes)
  └── 18. Naive Bayes Classifiers & Probabilistic Modeling
  │
  ▼
[ Phase 4: Ensemble Learning & Modern Boosting ]
  │── 16. Ensemble Learning (Bagging, Random Forests, Voting, GridSearch)
  └── 20. Modern Gradient Boosting Mastery (XGBoost, LightGBM, CatBoost)
  │
  ▼
[ Phase 5: Unsupervised Learning ]
  └── 17. K-Means Clustering & RFM Customer Segmentation
  │
  ▼
[ Phase 6: Production Engineering & Deep Learning ]
  │── 19. Artificial Neural Networks (ANN) & Perceptrons
  │── 21. Model Evaluation, PR-AUC, Diagnostics & Optuna Hyperparameter Optimization
  └── 22. Deep Learning Foundations with PyTorch (Tensors, Autograd, Backprop from Scratch)
```

---

## 📂 Modules & Learning Index

| Module | Core Concepts & Highlights | Formats & Materials |
| :--- | :--- | :--- |
| **[01-Python](1-Python/)** | Variables, control flow, loops, conditionals, basic syntax | Notebooks, Slides |
| **[02-List, Tuples, Set, Dict](2-List,%20Tuples,%20Set,%20Dict/)** | Python data structures, mutability, hash maps, complexity | Notebooks, Excel guides |
| **[03-Function](3-Function/)** | Scope, lambda functions, args/kwargs, recursion | Notebooks, Slides |
| **[04-OOP](4-OOP/)** | Classes, objects, inheritance, polymorphism, encapsulation | Notebooks, Slides |
| **[05-Numpy](5-Numpy/)** | Vectorized math, broadcasting, matrix algebra, slicing | Notebooks, Assignment |
| **[06-Pandas](6-Pandas/)** | Series, DataFrames, GroupBy, joins, missing data handling | 9 Practice Notebooks |
| **[07-Matplotlib, Seaborn](7-Matplotlib,%20Seaborn/)** | Distribution plots, categorical plots, statistical graphics | Notebooks, Datasets |
| **[08-Feature Scaling & PCA](8-Feature%20Scaling%20&%20PCA/)** | Normalization, Standardization, PCA eigen-decomposition | Notebooks, Datasets |
| **[09-IQR, Encoding](9-IQR,%20Encoding/)** | IQR outlier filtering, Z-score, One-Hot, Ordinal, Label encoding | Notebooks, Datasets |
| **[10-Linear Regression](10-Linear%20Regression/)** | Simple & Multiple Linear Regression, cost function, $R^2$ | Notebooks, Datasets |
| **[11-Logistic Regression](11-Logistic%20Regression/)** | Sigmoid function, odds ratios, decision boundaries | Notebooks, Titanic data |
| **[12-Save and Load the Model](12-Save%20and%20Load%20the%20Model/)** | Serializing models with `pickle` and `joblib` | Notebooks |
| **[13-KNN](13-KNN/)** | Euclidean/Manhattan distance, choosing optimal $k$ | Notebooks, OCR data |
| **[14-Decision Tree, Cross Validation](14-Decision%20Tree,%20Cross%20Validation/)** | Gini impurity, entropy, tree pruning, k-fold CV | Notebooks, Assignments |
| **[15-SVM](15-SVM/)** | Maximum margin hyperplanes, soft-margins, kernel trick (RBF) | Notebooks, Cancer data |
| **[16-Ensemble Learning, GridSearch](16-Ensemble%20Learning,%20GridSearch/)** | Bagging, Random Forest, voting ensembles, Grid Search CV | Notebooks |
| **[17-K Means Clustering](17-K%20Means%20Clustering/)** | Centroid initialization, Elbow method, RFM segmentation | Notebooks, Retail data |
| **[18-Naive Bayes](18-Naive%20Bayes/)** | Bayes' theorem, conditional independence, text classification | Notebooks, Spam data |
| **[19-ANN](19-ANN/)** | Multi-layer perceptrons, forward pass, activation functions | Notebooks, Digits data |
| **[20-Gradient Boosting](20-Gradient%20Boosting%20(XGBoost,%20LightGBM,%20CatBoost)/)** | Pseudo-residuals, Taylor expansion in XGBoost, GOSS in LightGBM | Master Notebook, Benchmark |
| **[21-Model Evaluation & Optuna](21-Model%20Evaluation%20and%20Hyperparameter%20Tuning/)** | PR-AUC vs ROC-AUC, Learning Curves, Scikit-learn Pipelines, Optuna | Master Notebook, Code |
| **[22-Deep Learning with PyTorch](22-Deep%20Learning%20Foundations%20with%20PyTorch/)** | Backprop calculus from scratch in pure NumPy, PyTorch `nn.Module` | Master Notebook, Code |

---

## 🛠️ Hands-on Projects & Guided Practice Templates

### Guided Project Templates (For Active Practice):
1. **[Customer Churn Prediction Pipeline](Projects%20-%20ML/Project_Template_Customer_Churn_Prediction/Customer_Churn_Prediction_Template.ipynb)**:
   - Full tabular classification pipeline with `ColumnTransformer` (scaling + one-hot encoding).
   - Logistic Regression vs Random Forest vs Gradient Boosting.
   - PR-AUC, Confusion Matrix, and Business Threshold Optimization.
   - Includes realistic companion dataset: `telecom_churn_data.csv`.
2. **[House Price Regression Pipeline](Projects%20-%20ML/Project_Template_House_Price_Prediction/House_Price_Regression_Template.ipynb)**:
   - Real estate valuation pipeline.
   - OLS vs Ridge ($L_2$) vs Lasso ($L_1$) vs Gradient Boosting Regressor.
   - Residual diagnostics ($Q-Q$ plot, heteroskedasticity check).
   - Includes realistic companion dataset: `house_pricing_data.csv`.

### Capstone EDA & ML Projects:
- **[Projects - EDA](Projects%20-%20EDA/)**:
  - `Project_01`: City of Chicago Payroll Data Analysis
  - `Project_02`: Customer Purchase Fake Data Analysis
  - `Project_03_Capstone`: Comprehensive Titanic Disaster EDA
- **[Projects - ML](Projects%20-%20ML/)**:
  - Breast Cancer Prediction using Support Vector Machines (SVM)
  - Ham/Spam Email Filtering using Naive Bayes & NLP
  - Handwritten Digits OCR Classification using k-NN
  - RFM Customer Segmentation using K-Means Clustering
  - Student Marks Prediction using Linear Regression

---

## 📐 Mathematical Formulation Reference Cards

### 1. Ordinary Least Squares (OLS) Closed-Form Solution:
$$\hat{\beta} = (X^T X)^{-1} X^T y$$

### 2. Logistic Function & Log-Loss (Binary Cross-Entropy):
$$\sigma(z) = \frac{1}{1 + e^{-z}}, \quad \mathcal{L}_{\text{BCE}} = -\frac{1}{N} \sum_{i=1}^N \left[ y_i \log(\hat{p}_i) + (1 - y_i) \log(1 - \hat{p}_i) \right]$$

### 3. Ridge vs Lasso Regularization:
$$\mathcal{L}_{\text{Ridge}} = \text{MSE} + \lambda \sum_{j=1}^p w_j^2 \quad (L_2), \qquad \mathcal{L}_{\text{Lasso}} = \text{MSE} + \alpha \sum_{j=1}^p |w_j| \quad (L_1)$$

### 4. XGBoost Optimal Leaf Weight:
$$w_j^* = -\frac{G_j}{H_j + \lambda} = -\frac{\sum_{i \in I_j} g_i}{\sum_{i \in I_j} h_i + \lambda}$$

### 5. Multi-Layer Perceptron Backpropagation Error:
$$\delta^{(l)} = \left( \delta^{(l+1)} (W^{(l+1)})^T \right) \odot \sigma'(z^{(l)})$$
$$\frac{\partial \mathcal{L}}{\partial W^{(l)}} = (a^{(l-1)})^T \delta^{(l)}, \quad \frac{\partial \mathcal{L}}{\partial b^{(l)}} = \sum \delta^{(l)}$$

---

## 💡 How to Master This Repository

1. **Active Coding**: Open the notebooks in Jupyter or VS Code. Type through code cells and inspect intermediate variable values.
2. **Practice the Templates**: Open the `Project_Template_*` notebooks and implement the `TODO` sections.
3. **Experiment with Edge Cases**: Modify hyperparameter values, introduce missing data or outliers, and observe how pipelines handle them.
4. **Track Progress**: Move systematically from Module 01 through Module 22.
