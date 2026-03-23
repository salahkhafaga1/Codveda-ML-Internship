#  Codveda Technology - Machine Learning Internship Portfolio

Welcome to my official repository documenting my journey and projects as a Machine Learning Intern at **Codveda Technology**. 

This repository serves as a complete portfolio of all the tasks, code, and documentation I am completing across the different levels of the internship program.

---

## 📁 Repository Structure
To keep things organized, the tasks are divided into folders based on their difficulty level:

* `📁 Level_1_Tasks/` : Basic Machine Learning concepts, data preprocessing, and simple models.
* `📁 Level_2_Tasks/` : *(Coming Soon)* Intermediate Machine Learning algorithms and techniques.
* `📁 Level_3_Tasks/` : *(Coming Soon)* Advanced Machine Learning projects and deep learning concepts.

---

##  Internship Progress & Completed Tasks

### ✅ Level 1: Basic Machine Learning
In this level, I focused on preparing raw data and building foundational predictive models.
* **Task 1: Advanced Data Preprocessing:** * Cleaned the Boston Housing dataset.
  * Detected and removed outliers using the IQR method.
  * Handled highly skewed data using Log Transformations (`np.log1p`).
  * Resolved multicollinearity by analyzing the correlation matrix.
  * Scaled numerical features using `StandardScaler`.
* **Task 2: Simple Linear Regression:** * Built and trained a Linear Regression model using `scikit-learn` to predict house prices. 
  * Evaluated the model using MSE and R-squared.
  * **Result:** Achieved an impressive **82% ($R^2$) accuracy** thanks to the advanced preprocessing steps.

###  ---

## 📌 Level 2: Intermediate

### Task 1: Logistic Regression for Binary Classification
* **Objective:** Predict customer churn (classifying whether a customer will cancel their subscription or stay).
* **Dataset:** Customer Churn Prediction Dataset.
* **Tools Used:** Python, pandas, scikit-learn, matplotlib.
* **Key Highlights:**
  * Handled categorical data using One-Hot Encoding (`pd.get_dummies`) and Label Encoding.
  * Applied feature scaling using `StandardScaler` for optimal model convergence.
  * Evaluated the model using Accuracy, Precision, Recall, and plotted the ROC Curve (AUC).
  * Calculated the Odds Ratio to interpret and extract the top 10 features driving customer churn.

### Task 2: Decision Trees for Classification
* **Objective:** Classify flower species using decision rules.
* **Dataset:** Iris Dataset (Local file integration).
* **Tools Used:** Python, pandas, scikit-learn, matplotlib.
* **Key Highlights:**
  * Implemented an algorithmic approach to **Hyperparameter Tuning** using nested loops.
  * Dynamically discovered the optimal `max_depth` and splitting `criterion` (`gini` vs. `entropy`) to prevent overfitting.
  * Plotted and visualized the final pruned decision tree.
  * Created a side-by-side visual comparison of trees generated using different mathematical criteria to deeply analyze the model's decision-making process.

---

## 🛠️ Setup & Execution
1. Clone this repository to your local machine.
2. Ensure you have the required datasets in the appropriate directories.
3. Open the Jupyter Notebooks and run the cells sequentially to reproduce the results and visualizations.
###  Level 3: Advanced Machine Learning
*(Tasks will be uploaded here once assigned and completed)*

---

##  Technologies & Libraries Used
Throughout this internship, I am utilizing the following tools:
* **Programming Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn
* **Data Visualization:** Matplotlib, Seaborn

---

## 🤝 Let's Connect
Feel free to explore the code in the folders above. I am always open to feedback and discussions!
*This repository is continuously updated as I progress through the Codveda Technology Internship program.*
