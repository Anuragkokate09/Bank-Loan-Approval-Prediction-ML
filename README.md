# 🏦 **Bank Loan Approval Prediction – Decision Tree Classification**
### *Supervised Machine Learning for Financial Risk Assessment*

---

## 📝 **Project Overview**
This project focuses on automating the loan approval process for financial institutions. By implementing a **Decision Tree Classifier**, the model analyzes historical customer data to learn complex decision rules. The final goal is to provide a highly interpretable model that predicts whether a loan should be **Approved** or **Rejected** based on an applicant's profile.

---

## 🛠️ **Project Scope**
The notebook follows a complete Machine Learning pipeline:
1.  **Dataset Loading & Preprocessing**: Handling raw data for analysis.
2.  **Categorical Feature Encoding**: Transforming categorical variables into numerical format using Label Encoding.
3.  **Feature-Target Separation**: Separating predictive features from the target variable and performing a train-test split.
4.  **Model Training**: Implementing and training the Decision Tree algorithm.
5.  **Evaluation**: Measuring performance via Accuracy, Confusion Matrix, Precision, Recall, and F1-score.
6.  **ROC-AUC Analysis**: Conducting advanced analysis to test the model's discrimination power.
7.  **Visualization**: Generating a visual representation of the Decision Tree logic.



---

## ⚙️ **Technical Stack**
* **Environment**: Jupyter Notebook
* **Language**: Python 3.x
* **Libraries**:
    * `Pandas`: For data manipulation and preprocessing.
    * `Scikit-Learn`: For machine learning modeling, encoding, and evaluation.
    * `Matplotlib / Seaborn`: For statistical data visualization.

---

## 📈 **Model Performance Metrics**
The project evaluates the model using industry-standard metrics to ensure banking compliance and accuracy:
* **Accuracy Score**: Measures overall correctness.
* **Confusion Matrix**: Tracks false approvals vs. false rejections.
* **ROC-AUC Curve**: Visualizes the trade-off between sensitivity and specificity.
* **Interpretability**: A visualized tree structure that explains the logic behind every loan decision.



---

## 🚀 **How to Use**
1.  **Prepare Environment**: Ensure you have `scikit-learn`, `pandas`, and `matplotlib` installed.
2.  **Run Notebook**: Open and execute `bank_loan_decision_tree.ipynb.ipynb`.
3.  **Test New Data**: You can use the `new_customer` DataFrame block at the end of the notebook to test custom applicant data.
4.  **Get Results**: The model will output the **Approval Probability** and the final **Approved/Rejected** status.

---

## 🤝 **Acknowledgments**
* **Author**: Anurag Kokate
* **Mentor**: Yash
* **Institution**: Developed at **Fireblaze Technologies Pvt. Ltd.**
