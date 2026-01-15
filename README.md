# 📡 Sonar Rock vs. Mine Prediction

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Library](https://img.shields.io/badge/Library-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Status-Complete-green)

## 📄 Overview
This project is a Machine Learning application that predicts whether a sonar signal has bounced off a **Metal Cylinder (Mine)** or a **Rough Rock**. 

It uses **Logistic Regression**, a supervised learning algorithm, to classify sonar return data into two categories:
* **M:** Mine
* **R:** Rock

## 📂 Dataset
The model is trained on the **connectionist-bench (Sonar, Mines vs. Rocks)** dataset.

* **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+(Sonar,+Mines+vs.+Rocks))
* **Description:** The file contains 208 patterns obtained by bouncing sonar signals off a metal cylinder (mine) and a somewhat cylindrical rock at various angles and under various conditions.
* **Features:** 60 numerical attributes (energy within a particular frequency band).

## 🛠️ Technologies Used
* **Python:** Core programming language.
* **Pandas:** For loading and manipulating the dataset.
* **NumPy:** For numerical operations and array handling.
* **Scikit-Learn:** For splitting the data, training the Logistic Regression model, and evaluating accuracy.

## ⚙️ Installation & Setup

