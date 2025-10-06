# 🌸 Iris Flower Classification Project  
**Internship Project – Unified Mentor**

---

## 🧩 Problem Statement

The iris flower, scientifically known as *Iris*, is a distinctive genus of flowering plants. Within this genus, there are three primary species: **Iris Setosa**, **Iris Versicolor**, and **Iris Virginica**. These species exhibit variations in their physical characteristics, particularly in the measurements of **sepal length**, **sepal width**, **petal length**, and **petal width**.

---

## 🎯 Objective

The objective of this project is to develop a **machine learning model** capable of learning from the measurements of iris flowers and accurately classifying them into their respective species. The model's primary goal is to **automate the classification process** based on the distinct characteristics of each iris species.

---

## 📘 Project Details

- **Iris Species:** The dataset consists of iris flowers from the species *Setosa*, *Versicolor*, and *Virginica*.  
- **Key Measurements:** Sepal length, sepal width, petal length, and petal width.  
- **Machine Learning Model:** The project involves creating and training a machine learning model to classify iris flowers accurately.  

This project can **streamline and automate the classification** of iris species, with applications in **botany, horticulture, and environmental monitoring**.

---


## 🧰 Technologies / Languages Used

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)


## 🧠 Project Summary

### Description
The Iris Flower Classification project develops a machine learning model to classify iris flowers into their respective species based on specific measurements. Each species exhibits unique characteristics, making it suitable for supervised learning classification.

### Key Details
- Dataset features: sepal length, sepal width, petal length, petal width.  
- Species: Setosa, Versicolor, Virginica.  
- Model training: Multiple machine learning algorithms were tested.  
- The trained model classifies flowers into the correct species based on input features.

---

## 📊 Results

**Primary Evaluation Metric:** Recall  

After removing overfitted models (train metrics = 100%), the final results are:

| Sl. No. | Classification Model       | Recall Train (%) | Recall Test (%) |
|---------|---------------------------|----------------|----------------|
| 1       | Decision Tree (tuned)     | 95.24          | 95.56          |
| 2       | Random Forest (tuned)     | **97.14**      | **97.78**      |
| 3       | Naive Bayes               | 94.28          | 97.78          |
| 4       | Naive Bayes (tuned)       | 94.28          | 97.78          |

✅ The **tuned Random Forest model** showed the best performance.

---

## 🏁 Conclusion

The **tuned Random Forest model** was selected as the final prediction model for classifying Iris flowers into three species: *Setosa*, *Versicolor*, and *Virginica*.

### Key Insights
- **Data Exploration:** *Iris Setosa* features are clearly separable from the other two species.  
- **Data Preprocessing:** Missing values handled; categorical features encoded.  
- **Model Selection:** Tuned Random Forest chosen for accuracy and interpretability.  
- **Evaluation:** Model showed excellent recall and accuracy.

### Challenges & Future Work
- Feature engineering and model tuning were challenging.  
- Future enhancements: ensemble learning, deep learning, or cross-validation optimization.

### Practical Application
- Can be used in **botanical studies**, **horticulture**, and **environmental monitoring**.  
- Automates species identification based on flower measurements.

---

✅ **Final Note:**  
This project successfully demonstrates the **machine learning workflow**: data exploration, preprocessing, model training, evaluation, and tuning, providing insights into feature importance for classification tasks.

---

## 👩‍💻 Author
**Hyndavi Thota**  
