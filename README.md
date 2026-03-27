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
4. 
# Level 3: Advanced Machine Learning 
**Codveda Technology - Machine Learning Internship**

This directory contains the final and most advanced tasks of the internship, focusing on solving a complex business problem—**Customer Churn Prediction**—using powerful ensemble and distance-based classification algorithms. 

To ensure modularity and clarity, the project is divided into two main notebooks, culminating in a final model comparison.

---

##  Project Structure

### Task 1: Random Forest Classifier (`Task1_RandomForest.ipynb`)
* **Objective:** Build an ensemble learning model to classify customer churn and extract actionable business insights.
* **Dataset:** Customer Churn Prediction Dataset (Imbalanced data).
* **Key Implementations:**
  * **Hyperparameter Tuning:** Utilized `GridSearchCV` with 5-fold Cross-Validation to find the optimal `n_estimators` and `max_depth`, prioritizing the F1-Score.
  * **Feature Importance Analysis:** Extracted and visualized the top driving factors behind customer churn (e.g., *Total day minutes*, *Customer service calls*), providing highly interpretable results for business stakeholders.
  * **Evaluation:** Achieved a perfect Precision score (1.00), minimizing false-positive churn alerts.

### Task 2: Support Vector Machine (SVM) (`Task2_SVM.ipynb`)
* **Objective:** Implement an SVM classifier, compare mathematical kernels, and visualize complex decision-making boundaries.
* **Dataset:** Customer Churn Prediction Dataset.
* **Key Implementations:**
  * **Feature Scaling:** Applied `StandardScaler` to normalize the data, a crucial mathematical prerequisite for distance-based SVM algorithms.
  * **Kernel Comparison:** Trained and evaluated both **Linear** and **RBF (Radial Basis Function)** kernels to handle both linear and non-linear data distributions.
  * **Decision Boundary Visualization:** Successfully reduced dimensionality to plot a comprehensive **2D Decision Boundary**, visually demonstrating how the RBF kernel dynamically separates churn classes based on the top continuous features.

###  Final Model Comparison (`Model_Comparison.ipynb` / End of Task 2)
To conclude the advanced level, a side-by-side evaluation was conducted between the Tuned Random Forest and the SVM models (Linear & RBF). 
* Plotted a visually appealing Bar Chart comparing **Accuracy** and **F1-Score**.
* **Conclusion:** The Random Forest model provided exceptional interpretability and precision, while the SVM (RBF) demonstrated robust handling of complex, non-linear boundaries. Both models serve as strong deployment candidates depending on the prioritized business metric.

---

##  Setup & Execution
1. Clone this repository to your local machine.
2. Ensure you have the required dataset (`churn-bigml-80.csv`) in the root directory.
3. Install the required libraries: `pandas`, `numpy`, `matplotlib`, `scikit-learn`.
4. Open the Jupyter Notebooks and run the cells sequentially to reproduce the models, metrics, and visual plots.
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
