# 🧠 K-Nearest Neighbors (KNN) Classification

This project demonstrates how to implement the K-Nearest Neighbors (KNN) algorithm using the Iris dataset in Python with Scikit-learn, and visualize the decision boundaries and performance metrics.

---

## 🎯 Objective

- Understand the working of the KNN algorithm.
- Classify data using `KNeighborsClassifier` from Scikit-learn.
- Evaluate the model with different values of K.
- Visualize accuracy, confusion matrix, and decision boundaries.

---

## 🛠️ Tools & Libraries

- Python 3.x
- [Scikit-learn](https://scikit-learn.org/)
- Pandas
- Matplotlib
- Seaborn (optional, for styling)
- NumPy
- Google Colab / Jupyter Notebook

---

## 📂 Dataset Used

- **Iris Dataset** (inbuilt in Scikit-learn)
  - Classes: Setosa, Versicolor, Virginica
  - Features: Sepal length, Sepal width, Petal length, Petal width

---

## 📌 Steps Followed

1. **Load Dataset**  
   Load the Iris dataset and extract features & labels.

2. **Normalize Data**  
   Use `StandardScaler` to scale features.

3. **Train-Test Split**  
   Split data into 70% training and 30% testing sets.

4. **Train KNN Model**  
   Use `KNeighborsClassifier` for different values of K (1 to 10).

5. **Evaluate Performance**  
   - Compute **accuracy** for each K.
   - Display the **confusion matrix** for the best K.
   - Plot **Accuracy vs. K**.

6. **Decision Boundary Visualization**  
   - Reduce to 2D features for visualization.
   - Plot decision regions using `matplotlib`.

---

## 📊 Output

- Accuracy plot for different K values.
- Confusion matrix visualization.
- 2D decision boundary for the best-performing model.

---

## 🧪 How to Run

1. Clone the repository or open the notebook in Google Colab.
2. Install required packages (usually pre-installed in Colab).
3. Run each cell step-by-step to see the output and visualizations.

---

## 📎 Sample Results

- Best Accuracy: *~96% at K=3* (may vary)
- Confusion Matrix and classification boundaries plotted.

---

## 📬 Contact

Created by [Your Name]  
Feel free to reach out for contributions or suggestions!

