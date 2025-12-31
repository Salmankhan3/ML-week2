# Week 2: Python Fundamentals for Machine Learning

![GitHub stars](https://img.shields.io/github/stars/SalmanKhan3/ML-Internship-B01?style=social)
![GitHub forks](https://img.shields.io/github/forks/SalmanKhan3/ML-Internship-B01?style=social)
![Internship](https://img.shields.io/badge/ML%20Internship-B01-red)
![MIT License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-success)
![GitHub Repo Size](https://img.shields.io/github/repo-size/SalmanKhan3/ML-week2)

---

## 📘 Description
This notebook documents my learning progress for **Week 2 of the ML Internship (Batch-2) at Neuro App**.  
The focus of this week was building a strong foundation in **Python for Machine Learning**, including NumPy, Pandas, data visualization, and object-oriented programming.

---

## 📑 Table of Contents
- [NumPy Array Operations](#numpy-array-operations)
- [Pandas Data Manipulation](#pandas-data-manipulation)
- [Data Visualization with Matplotlib & Seaborn](#data-visualization-with-matplotlib--seaborn)
- [Object-Oriented Programming for ML](#object-oriented-programming-for-ml)

---

## NumPy Array Operations (3 hours)
In this section, I practiced:
- Creating arrays using `np.array`
- Reshaping arrays
- Array slicing and indexing
- Mathematical operations:
  - Addition
  - Subtraction
  - Multiplication
  - Matrix multiplication
  - Dot product

### Screenshots
![numpy](screenshots/Screenshot%20(131).png)
![numpy](screenshots/Screenshot%20(132).png)
![numpy](screenshots/Screenshot%20(133).png)
![numpy](screenshots/Screenshot%20(134).png)
![numpy](screenshots/Screenshot%20(135).png)
![numpy](screenshots/Screenshot%20(136).png)
![numpy](screenshots/Screenshot%20(137).png)
![numpy](screenshots/Screenshot%20(138).png)
![numpy](screenshots/Screenshot%20(139).png)
##  Pandas Data Manipulation (4 hours)
In this notebook, I explored and manipulated the **Titanic dataset** using Pandas.

### Tasks performed:
- Data exploration and summary statistics
- Handling missing values (dropping and imputing)
- Feature engineering:
  - `FamilySize`
  - `IsAlone`
  - `Title`
  - `IsChild`
  - `HasCabin`

This step helped in preparing a cleaner and more informative dataset for ML models.


## 📊 Data Visualization with Matplotlib & Seaborn (3 hours)
Using Matplotlib and Seaborn, I visualized the Titanic dataset to better understand relationships between features.

### Plots created:
- Bar plot
- Histogram
- Line plot
- Pair plot
- Scatter plot
- Heatmap
- Box plot
- Violin plot

### Saved visualizations:
!['age'](visualizations/age_destribution.jpeg)
!['age_vs_fare'](isualizations/age_vs_fare.jpeg)
!['correlation'](visualizations/Corelation.png)
!['pair plot'](visualizations/pairplot.jpg)
!['srvival Rate'](visualizations/survival_rate.png)
!['voilin plot'](visualizations/voilin_plot.jpg)
!['Pasenger_class_dest'](visualizations/Pasenger_class_dest.png)

---

##  Object-Oriented Programming for ML (3 hours)
In this section, I applied **Object-Oriented Programming (OOP)** principles to machine learning workflows.

### Implemented class: `DataPreprocessor`
Methods included:
- `load_data()` – Load the dataset
- `handle_missing_values()` – Clean missing data
- `encode_categorical()` – Encode categorical variables (`sex`, `embarked`)
- `scale_features()` – Scale numerical features using `StandardScaler`
- `split_data()` – Split data into training and testing sets

### Outcome
A **cleaned, encoded, scaled, and split dataset**, ready for machine learning algorithms.

---

## 🚀 Skills Gained
- NumPy for numerical computation
- Pandas for data manipulation
- Data visualization with Matplotlib & Seaborn
- Feature engineering
- OOP for ML pipelines
- Data preprocessing best practices
