# 🎗️ Breast Cancer Prediction

### 🤖 Machine Learning Project by **RogithKumar**

<p align="center">

**Predict • Analyze • Learn • Innovate**


## 🌟 About

**Breast Cancer Prediction** is a Machine Learning project that analyzes breast cancer dataset features and applies different ML algorithms for **regression and classification**.

The project works with features such as:

📏 `mean_radius`
🧩 `mean_texture`
📐 `mean_perimeter`
📊 `mean_area`
🌊 `mean_smoothness`
🎯 `diagnosis`

The project explores both **continuous-value prediction** and **diagnosis classification**.

---

## 🧠 Machine Learning Models

### 📈 Linear Regression

Used to predict:

```text
mean_radius → mean_area
```

The model learns the relationship between `mean_radius` and `mean_area` and evaluates the prediction using metrics such as **MSE, MAE and R²**.

---

### 🎯 Logistic Regression

Used for **classification**:

```text
mean_texture → diagnosis
```

The model predicts the probability of a sample belonging to a diagnosis class such as **Benign (B)** or **Malignant (M)**.

---

### 🌳 Decision Tree Regression

Predicts:

```text
mean_radius
mean_texture
mean_perimeter
mean_area
        ↓
mean_smoothness
```

The Decision Tree creates a series of conditions and splits the data into smaller groups before producing the final prediction.

---

### 🌲 Random Forest Regression

Random Forest combines **multiple Decision Trees** to produce a more reliable prediction.

```text
        🌳 Tree 1
        🌳 Tree 2
Input → 🌳 Tree 3 → Prediction
        🌳 Tree 4
        🌳 Tree 5
```

It is used to predict `mean_smoothness` from the selected features.

---

### ⚡ Support Vector Regression

**SVM** is used in the project as **SVR (Support Vector Regression)** because `mean_smoothness` is a continuous value.

The project uses an **RBF kernel** to learn non-linear relationships between the features and `mean_smoothness`.

---

### 👥 K-Nearest Neighbors

KNN is used as a **Regression model** to predict `mean_smoothness`.

```text
New Data Point
      ↓
Calculate Distance
      ↓
Find K Neighbors
      ↓
K = 5
      ↓
Average Values
      ↓
Prediction
```

The project uses **K = 5** nearest data points.

---

### 🧮 Gaussian Naive Bayes

Used for **diagnosis classification**.

```text
Input Features
      ↓
Gaussian Naive Bayes
      ↓
Probability Calculation
      ↓
Diagnosis
      ↓
Benign / Malignant
```

The project uses **Gaussian Naive Bayes** because `diagnosis` is a categorical output.

---

## 🔄 Project Workflow

```text
                📊 Dataset
                    │
                    ▼
             🧹 Data Processing
                    │
                    ▼
             🔍 Feature Selection
                    │
                    ▼
              ✂️ Train / Test
                    │
                    ▼
          🤖 Machine Learning Models
                    │
          ┌─────────┼─────────┐
          ▼         ▼         ▼
       📈 Regression 🎯 Classification
          │         │
          └────┬────┘
               ▼
          🔮 Prediction
               │
               ▼
          📊 Evaluation
```

---

## 🛠️ Technologies Used

<p align="center">

🐍 **Python**   
📊 **Pandas**   
🔢 **NumPy**   
📈 **Matplotlib**   
📉 **Seaborn**   
🤖 **Scikit-learn**

</p>

---

## 📚 Concepts Covered

* 🤖 Supervised Machine Learning
* 📈 Regression
* 🎯 Classification
* 🌳 Decision Trees
* 🌲 Ensemble Learning
* ⚡ Support Vector Regression
* 👥 K-Nearest Neighbors
* 🧮 Naive Bayes
* 📊 Model Evaluation
* 🔍 Feature Analysis

---

## 📂 Project Structure

```text
Breast-Cancer-Prediction/
│
├── 📓 Breast_Cancer_Prediction.ipynb
├── 📊 data.csv
├── 📁 assets/
│   └── 🖼️ project-preview.png
├── 📄 requirements.txt
└── 📄 README.md
```

---

## 🚀 How to Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/breast-cancer-prediction.git
```

### 2️⃣ Install Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 3️⃣ Open the Notebook

Open:

```text
Breast_Cancer_Prediction.ipynb
```

You can run it using **Google Colab** or **Jupyter Notebook**.

---

## 📊 Model Summary

| 🤖 Model                    | 🎯 Prediction     |
| --------------------------- | ----------------- |
| 📈 Linear Regression        | `mean_area`       |
| 🎯 Logistic Regression      | `diagnosis`       |
| 🌳 Decision Tree Regression | `mean_smoothness` |
| 🌲 Random Forest Regression | `mean_smoothness` |
| ⚡ SVR                       | `mean_smoothness` |
| 👥 KNN Regression           | `mean_smoothness` |
| 🧮 Gaussian Naive Bayes     | `diagnosis`       |

---

## 👨‍💻 Author

# **Rogithkumar M**

🎓 Computer Science & Engineering
🤖 Machine Learning Enthusiast
💻 Developer

---

## ⭐ Support

If you found this project useful:

⭐ **Star this repository**
🍴 **Fork this repository**
💡 **Share your feedback**

---

<p align="center">

### 🎗️ Breast Cancer Prediction using Machine Learning

**Made with ❤️ by RogithKumar**

</p>
