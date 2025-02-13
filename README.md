# 🚀 Logistic Regression Model for Social Network Ads

## 📖 Project Overview
In this project, we built a Logistic Regression model to predict whether users purchased a product based on their age and estimated salary. The dataset was taken from Social Network Ads, and the model was trained and tested using Python's machine learning libraries.

---

## ⚙️ Key Steps

### 1️⃣ Data Importing & Preprocessing
- **Imported Libraries:** Pandas, NumPy, and Matplotlib.
- **Dataset:** Social Network Ads.
- **Features:** Age, Estimated Salary.
- **Target:** Purchase status (Yes/No).
- **Preprocessing:** Handled data with feature scaling to normalize age and salary for better model performance.

---

### 2️⃣ Splitting the Dataset
- Divided the dataset into training (80%) and testing (20%) subsets.
- Ensured reproducibility by setting a random state.

---

### 3️⃣ Model Training: Logistic Regression
- Used `LogisticRegression` from `sklearn.linear_model`.
- Fitted the model with the training dataset.

---

### 4️⃣ Predictions & Model Evaluation
- Predicted results on the test set.
- Compared predictions with actual results.
- **Evaluation Metrics:**
  - **Confusion Matrix:** To analyze true positives, true negatives, false positives, and false negatives.
  - **Accuracy Score:** To measure the overall performance of the model.
---

## 📊 Results Analysis
- Achieved a solid performance in distinguishing between users who made a purchase and those who didn’t.
- The confusion matrix highlighted correct and incorrect predictions effectively.
- ![alt text](https://github.com/tanveerj5/Logistic-Regression-Model-for-Social-Network-Ads/blob/main/Accuracy.png)
---

## 🎨 Data Visualization
### 🧠 Training Set
- Visualized the decision boundary using a scatter plot.
- Red and green regions showed distinct classes (Purchased/Not Purchased).

### 🧪 Test Set
- Repeated the visualization for the test set to validate model performance.
- Observed how well the model generalizes to unseen data.

---

## 🔍 Insights
- The logistic regression model successfully classified users based on age and salary.
- Feature scaling played a crucial role in improving model performance.
- Visualizations provided clear, intuitive insights into decision boundaries.

- Train Set Visualization
- ![alt text](https://github.com/tanveerj5/Logistic-Regression-Model-for-Social-Network-Ads/blob/main/output%20train.png)
- 
- Test Set Visualization
- ![alt text](https://github.com/tanveerj5/Logistic-Regression-Model-for-Social-Network-Ads/blob/main/output%20test.png)
---

## 🤖 Logistic Regression Model Insights
- **Sigmoid Function:** Logistic regression uses the sigmoid function to map predicted values to probabilities between 0 and 1.
- **Probabilistic Nature:** It provides the probability of a data point belonging to a particular class.
- **One-to-One Mapping:** The sigmoid function is one-to-one and can be inverted using the logit function.

---

## 🛠️ Technologies Used
- Python 🐍
- Pandas 📑
- NumPy 🔢
- Matplotlib 📊
- Scikit-Learn 🤖

---

## 💡 Potential Improvements
- Experiment with more complex models (e.g., Random Forest, SVM).
- Apply hyperparameter tuning for improved performance.
- Explore additional features or data sources to enhance prediction accuracy.

---

### 🌐 Connect with Me
If you’re interested in more of my projects, feel free to check out my GitHub profile!

Happy Coding! 😊

