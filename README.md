# Task 6: K-Nearest Neighbors (KNN) Classification 🌸

This Repository contains the implementation of **K-Nearest Neighbors (KNN)** for classification using the **Iris dataset** as part of the AI & ML Internship.

## 🔧 Tools & Libraries Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 📌 Task Objectives

- Implement KNN using `sklearn.neighbors.KNeighborsClassifier`
- Normalize feature data
- Experiment with different values of `K`
- Evaluate the model using:
  - Accuracy Score
  - Confusion Matrix
- Visualize decision boundaries (with 2 selected features)

## 📂 Dataset

- Dataset Used: [Iris Dataset](https://www.kaggle.com/datasets/uciml/iris)
- Columns:
  - SepalLengthCm
  - SepalWidthCm
  - PetalLengthCm
  - PetalWidthCm
  - Species (target)

## 📊 Output & Evaluation

- Trained KNN models with different `k` values (1, 3, 5, 7, 9)
- Printed accuracy for each value
- Displayed confusion matrix
- Visualized decision boundary using 2 features (SepalLength & PetalLength)

## 📷 Ouput Plots

<div align="">

  ### 📊 Evaluating K values from 1 to 9:
  1. 🔎 Accuracy for K = 1: 0.9667 <br/>
![image](https://github.com/user-attachments/assets/ce823ae3-dfdd-4e8c-8202-f8e361e4857f)
  <br/>
  
  2. 🔎 Accuracy for K = 3: 0.9333 <br/>
![image](https://github.com/user-attachments/assets/3cd955d1-bc6d-4930-a6f6-062b4761e18e)
  <br/>
  
  3. 🔎 Accuracy for K = 5: 0.9333 <br/>
![image](https://github.com/user-attachments/assets/706d3281-3589-413c-bad7-7e9b83b0bb29)
  <br/>
  
  4. 🔎 Accuracy for K = 7: 0.9667 <br/>
![image](https://github.com/user-attachments/assets/a04d9208-8c2a-4e90-a6fe-b342c71f657a)
  <br/>
  
  5. 🔎 Accuracy for K = 9: 0.9667 <br/>
![image](https://github.com/user-attachments/assets/59c2d5f8-37f3-4c1a-b774-00466bef187d)
  <br/>

  ###  🌸📊 KNN Decision Boundary(with 'Sepal' & 'Petal' features)
![image](https://github.com/user-attachments/assets/4e805171-c0b5-470a-954a-7f02c1af05ae)

</div>

---

<br/>

## 📁 Files Included

- `KNN_Iris_Colab.ipynb` – Colab-ready notebook with upload support and visualizations
- `Iris.csv` – Dataset file (you will be prompted to upload in Colab)
- `README.md` – This file

## 🚀 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Upload `Iris.csv` when prompted
3. Run all cells
4. Observe output metrics and decision boundary plot

## 💡 Concepts Learned

- Instance-based learning
- Euclidean distance & K selection
- Importance of feature normalization in KNN
- KNN decision boundaries in 2D space

## ❓ Interview Questions Prepared

1. How does the KNN algorithm work?
2. How do you choose the right K?
3. Why is normalization important in KNN?
4. What is the time complexity of KNN?
5. What are the pros and cons of KNN?
6. Is KNN sensitive to noise?
7. How does KNN handle multi-class problems?
8. What’s the role of distance metrics in KNN?


---

> ✨ Feel free to  use the repo⭐ if you find it useful!
