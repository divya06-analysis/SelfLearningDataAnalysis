# Self Learning Data Analysis Tool

##  Project Overview

The **AI-Powered Self Learning Data Analysis Tool** is an intelligent web application developed using Python and Streamlit that automates the process of data analysis, visualization, preprocessing, and machine learning.

The tool allows users to upload datasets and automatically:

* Analyze data
* Handle missing values
* Encode categorical data
* Scale features
* Generate visualizations
* Train ML models
* Recommend best-performing algorithms
* Generate automatic insights

It also includes a simple **self-learning recommendation system** using SQLite database to remember previously successful models.

---

#  Features

##  Dataset Upload

* Upload CSV datasets
* Preview uploaded data instantly

---

##  Automatic Dataset Analysis

* Number of rows and columns
* Data types
* Duplicate detection
* Missing value analysis

---

##  Data Cleaning

Supports:

* Mean Imputation
* Median Imputation
* Drop Missing Rows

---

##  Categorical Encoding

* Automatic Label Encoding

---

##  Feature Scaling

* StandardScaler integration

---

##  Data Visualization

Interactive visualizations including:

* Histogram
* Scatter Plot
* Box Plot
* Correlation Heatmap

---

##  Machine Learning

Supports:

### Classification Models

* Logistic Regression
* Random Forest Classifier
* Support Vector Machine (SVM)

### Regression Models

* Linear Regression
* Random Forest Regressor

---

##  Self Learning Recommendation Engine

The application stores:

* Best-performing algorithms
* Previous accuracy scores

And recommends models based on historical performance.

---

##  Automatic Insight Generation

Automatically detects:

* Strong correlations
* Relationships between features

---

##  Dataset Download

* Download cleaned dataset directly

---

# 🛠️ Technologies Used

| Technology   | Purpose                |
| ------------ | ---------------------- |
| Python       | Core Programming       |
| Streamlit    | Web Application        |
| Pandas       | Data Handling          |
| NumPy        | Numerical Computation  |
| Scikit-learn | Machine Learning       |
| Matplotlib   | Visualization          |
| Seaborn      | Visualization          |
| Plotly       | Interactive Charts     |
| SQLite       | Self-Learning Database |

---

#  Project Structure

```text
SelfLearningDataAnalysis/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
├── user_history.db
│
├── datasets/
├── models/
├── reports/
└── visualizations/
```

---

# ⚙️ Installation

## 1️ Clone Repository

```bash
git clone https://github.com/yourusername/SelfLearningDataAnalysis.git
```

---

## 2️ Move into Project Folder

```bash
cd SelfLearningDataAnalysis
```

---

## 3️ Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Mac/Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 4️ Install Dependencies

```bash
pip install -r requirements.txt
```

---

#  Run Application

```bash
streamlit run app.py
```

---

# 📌 How It Works

1. Upload Dataset
2. Analyze Dataset
3. Clean Missing Values
4. Encode Data
5. Scale Features
6. Visualize Data
7. Train ML Models
8. Compare Results
9. Generate Insights
10. Recommend Best Algorithm

---

#  Sample Functionalities

## ✔ Upload Dataset

Users can upload CSV datasets directly through the web interface.

## ✔ Automatic Analysis

The tool automatically displays:

* Missing values
* Data types
* Duplicate rows
* Dataset dimensions

## ✔ Visualizations

Generate:

* Histograms
* Scatter plots
* Heatmaps
* Boxplots

## ✔ Machine Learning

Train ML models directly from the interface.

---

#  Future Enhancements

Future improvements may include:

* AutoML integration
* AI chatbot assistant
* PDF report generation
* Explainable AI (SHAP)
* Voice assistant
* Cloud database integration
* User authentication
* Real-time analytics dashboard

---

#  Deployment

This project can be deployed using:

* Streamlit Cloud
* Render
* Railway
* Heroku

---

#  Learning Outcomes

This project demonstrates:

* Data preprocessing
* Exploratory Data Analysis (EDA)
* Machine Learning
* Data visualization
* Recommendation systems
* Database integration
* Web app development

---

#  Author

**Divya Ikhar**
B.Tech AI & Data Science Student
Data Analyst & AI Enthusiast

---

# License

This project is developed for educational and learning purposes.
