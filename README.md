# Machine Learning

A collection of Jupyter notebooks covering fundamental Machine Learning concepts, tools, and hands-on projects. All notebooks are created and run in Google Colab.

## 📁 Repository Structure

```
MachineLearning/
├── Introduction to Numpy.ipynb
├── car_price_prediction.ipynb
├── customer_churn_prediction.ipynb
├── section-2-data-science-and-ml-tools/
│   ├── pandas-exercises.ipynb
│   └── pandas-exercises_1.ipynb
└── README.md
```

## 📓 Notebooks

### 1. [Introduction to NumPy](./Introduction%20to%20Numpy.ipynb)

An introductory notebook covering the core concepts of NumPy, the fundamental library for numerical computing in Python.

**Topics Covered:**
- One-Dimensional Arrays — creating and manipulating 1D NumPy arrays
- Multi-Dimensional Arrays — working with 2D/nD arrays and element access
- Randomly Generated Arrays — using `np.random` to generate arrays
- Element-Wise Operations — arithmetic operations on arrays
- Comparison Operations — boolean masking and filtering
- Summarizing Operations — `sum`, `mean`, `min`, `max`, etc.
- Vector Operations — vector-vector multiplication (dot product)
- Matrix Operations — matrix-matrix multiplication and identity matrices

---

### 2. [Car Price Prediction with Linear Regression](./car_price_prediction.ipynb)

A beginner-friendly, end-to-end machine learning project that builds a **Car Price Prediction** model using **Linear Regression**.

**Topics Covered:**
- Uploading and loading data in Google Colab
- Data cleaning and preprocessing (standardizing column names, handling string columns)
- Exploratory Data Analysis (EDA) with visualizations
- Feature engineering (log transformation)
- Setting up a validation framework (train/validation/test split)
- Training Linear Regression using the Normal Equation
- Training Linear Regression in vector form

**Dataset:** Car sales dataset (uploaded via Colab)

---

### 3. [Customer Churn Prediction](./customer_churn_prediction.ipynb)

A complete machine learning pipeline to predict **customer churn** — the likelihood that a customer will stop using a service — using the Telco Customer Churn dataset.

**Topics Covered:**
- Data preparation: downloading from Kaggle, loading, and inspecting the dataset
- Handling missing values and standardizing column names
- Encoding the target variable (`churn`) as binary integers
- Setting up a validation framework (train/validation/test splits)
- Exploratory Data Analysis (EDA): churn rate analysis, risk ratios
- Identifying numerical and categorical features
- Feature importance analysis

**Dataset:** [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) — 7,043 customers with demographics, account info, and service usage data.

---

### 4. [Pandas Exercises](./section-2-data-science-and-ml-tools/pandas-exercises.ipynb)

A hands-on practice notebook for working with **Pandas**, the primary data manipulation library in Python.

**Topics Covered:**
- Loading and exploring DataFrames (shape, dtypes, head/tail)
- Indexing and selecting data with `.loc` and `.iloc`
- Working with car sales data (`car-sales.csv`)
- Converting data types (e.g., string columns to numeric)
- Extensions section for advanced practice

**Based on:** The Pandas quick introduction series.

---

### 5. [Pandas Exercises (Part 2)](./section-2-data-science-and-ml-tools/pandas-exercises_1.ipynb)

A continuation of Pandas exercises with additional tasks and practice problems.

**Topics Covered:**
- Further Pandas data manipulation tasks
- Extended exercises covering filtering, grouping, and data transformation

---

## 🛠️ Tools & Libraries

| Library | Purpose |
|---|---|
| NumPy | Numerical computing and array operations |
| Pandas | Data manipulation and analysis |
| Matplotlib / Seaborn | Data visualization |
| Scikit-learn | Machine learning models and utilities |
| Google Colab | Interactive notebook environment |

## 🚀 Getting Started

All notebooks are designed to run in **Google Colab**. Click the **"Open in Colab"** badge at the top of each notebook to launch it directly in your browser without any local setup.

You can also clone this repository and run the notebooks locally:

```bash
git clone https://github.com/SathyaPrakashD/MachineLearning.git
cd MachineLearning
jupyter notebook
```
