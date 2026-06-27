# 🎯 Logistic Regression Project – Advertisement Click Prediction

## 📖 Overview

This project demonstrates how to build a **Logistic Regression** machine learning model to predict whether a user will click on an online advertisement based on their demographic information and online behavior.

Unlike Linear Regression, which predicts numerical values, Logistic Regression is used for **classification problems** where the output belongs to predefined categories.

This project walks through the complete machine learning workflow, from data exploration to model evaluation.

---

# 🎯 Project Objective

Build a machine learning model that predicts whether a user will click on an advertisement.

**Target Variable**

* **Clicked on Ad**

  * `1` → User clicked the advertisement
  * `0` → User did not click the advertisement

---

# 📂 Dataset

The dataset contains information about website visitors, including:

| Feature                  | Description                          |
| ------------------------ | ------------------------------------ |
| Daily Time Spent on Site | Average time spent on the website    |
| Age                      | User's age                           |
| Area Income              | Average income of the user's area    |
| Daily Internet Usage     | Daily internet usage time            |
| Male                     | User's gender (1 = Male, 0 = Female) |
| Clicked on Ad            | **Target variable**                  |

---

# 🤔 Why Logistic Regression?

This project is a **classification problem**.

The model predicts one of two possible outcomes:

* ✅ Clicked the advertisement
* ❌ Did not click the advertisement

Linear Regression cannot solve this problem effectively because it predicts continuous numerical values, while Logistic Regression predicts probabilities between **0 and 1**, making it ideal for binary classification.

---

# ⚖️ Linear Regression vs Logistic Regression

| Linear Regression            | Logistic Regression                     |
| ---------------------------- | --------------------------------------- |
| Predicts continuous values   | Predicts categories                     |
| Used for regression problems | Used for classification problems        |
| Output can be any number     | Output is a probability (0–1)           |
| Example: House price         | Example: Spam detection                 |
| Example: Salary prediction   | Example: Disease prediction             |
| Example: Customer spending   | Example: Advertisement click prediction |

---

# 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

# 📊 Project Workflow

## 1️⃣ Import Libraries

Import all required libraries for:

* Data manipulation
* Mathematical operations
* Data visualization
* Machine Learning

---

## 2️⃣ Load the Dataset

Read the CSV dataset using Pandas.

---

## 3️⃣ Exploratory Data Analysis (EDA)

Analyze and understand the dataset by:

* Viewing sample rows
* Checking data types
* Finding missing values
* Computing summary statistics
* Visualizing feature distributions
* Exploring relationships between variables

---

## 4️⃣ Feature Selection

Input Features:

* Daily Time Spent on Site
* Age
* Area Income
* Daily Internet Usage
* Male

Target:

* Clicked on Ad

---

## 5️⃣ Split the Dataset

Split the data into:

* **70% Training Data**
* **30% Testing Data**

The training data is used to teach the model, while the testing data evaluates its performance on unseen examples.

---

## 6️⃣ Train the Model

Train a **Logistic Regression** classifier using Scikit-learn.

During training, the model learns patterns that distinguish users who clicked the advertisement from those who did not.

---

## 7️⃣ Make Predictions

Use the trained model to predict whether users in the testing dataset clicked on the advertisement.

Predicted outputs are:

* `1` → Clicked
* `0` → Did not click

---

## 8️⃣ Evaluate the Model

Evaluate the classifier using:

* Classification Report
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics measure how accurately the model classifies users.

---

# 📈 Results

The Logistic Regression model successfully classified users based on their browsing behavior and demographic information.

Performance was evaluated using a **Classification Report**, providing insights into:

* Precision
* Recall
* F1-score
* Overall accuracy

---

# 💡 Business Insight

This model can help marketing teams:

* Predict which users are likely to click advertisements.
* Improve ad targeting strategies.
* Increase conversion rates.
* Reduce advertising costs by focusing on high-probability users.

---

# 📷 Visualizations

The notebook includes several visualizations, such as:

* Histograms
* Joint Plots
* Pair Plots
* Distribution Plots

These graphs help reveal relationships between user behavior and advertisement clicks.

---

# 📚 What I Learned

Through this project, I learned how to:

* Perform Exploratory Data Analysis (EDA)
* Visualize data using Matplotlib and Seaborn
* Build a Logistic Regression classifier
* Split data into training and testing sets
* Train a machine learning classification model
* Make predictions on unseen data
* Evaluate classification performance using Precision, Recall, F1-score, and Confusion Matrix
* Interpret model results to generate business insights

---

# 🚀 How to Run

```bash
git clone https://github.com/Abdelrahman-Noaman/Logistic-Regression-Project.git

cd Logistic-Regression-Project

pip install -r requirements.txt
```

Open the Jupyter Notebook and run all cells.

---

# 📁 Project Structure

```
Logistic-Regression-Project/
│
├── 02-Logistic Regression Project.ipynb
├── advertising.csv
├── README.md
└── requirements.txt (optional)
```

---

# 👨‍💻 Author

**Abdelrahman Noaman**

Computer & Software Engineering Student

Cloud & DevOps Enthusiast ☁️

Machine Learning Learner 🤖

---

⭐ If you found this project helpful, consider giving it a **Star ⭐** on GitHub!
