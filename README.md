# Exploratory Data Analysis (EDA) on Titanic Dataset

This beginner-level project performs EDA to uncover patterns in passenger survival on the Titanic.

## 🚀 Project Objectives

- Visualize survival counts
- Analyze survival based on gender and class
- Examine class distribution
- Explore age distribution

## 📁 Dataset

The dataset should be in the `data/` folder with the name `titanic.csv`. It must contain the following columns:
- `PassengerID`
- `Name`
- `Age`
- `Gender`
- `Class`
- `Survived`

## 📊 Visualizations

- Countplot: Survived vs Not Survived
- Bar Plot: Survival by Gender and Class
- Pie Chart: Class Distribution
- Histogram: Age Distribution

## 🛠️ Installation

Create a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

Install required packages:

```bash
pip install -r requirements.txt
```

## ▶️ Run the Notebook

```bash
jupyter notebook eda_titanic.ipynb
```

## 📦 Requirements

See `requirements.txt`

## 📜 License

This project is open source and free to use under the MIT License.
