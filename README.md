# Predicting Loan Defaults with Decision Trees and Random Forests

This project explores the use of Decision Trees and Random Forests to predict whether a borrower will repay their loan. The dataset contains historical lending data from 2007 to 2010 and includes features such as FICO score, loan purpose, interest rate, and more.

The project was completed as part of [Jose Portilla's Python for Data Science and Machine Learning Bootcamp](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/) on Udemy.

---

## 🧠 Objective

To build a classification model that predicts if a borrower will pay back their loan in full, using decision tree algorithms.

---

## 📁 Dataset

- **Name:** Lending Club Data (2007–2010)
- **Source:** Provided in the Udemy course
- **File:** `loan_data.csv`

---

## 📊 Features Used

Some of the key features include:
- `credit.policy`: Whether the customer meets the credit underwriting criteria.
- `purpose`: The purpose of the loan.
- `int.rate`: The interest rate of the loan.
- `installment`: The monthly installments owed by the borrower.
- `log.annual.inc`: The log of the annual income.
- `fico`: FICO credit score.
- `days.with.cr.line`: Number of days the borrower has had a credit line.
- `revol.bal`: Balance on the borrower's revolving line of credit.
- `not.fully.paid`: Target variable (1 = Not paid back, 0 = Paid back).

---

## ⚙️ Technologies & Libraries

- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- Jupyter Notebook

---

## 🧪 Machine Learning Models

- Decision Tree Classifier
- Random Forest Classifier

Performance metrics used:
- Confusion Matrix
- Classification Report
- Accuracy Score

---

## 🖥️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/decision-tree-random-forest-loan-default.git
cd decision-tree-random-forest-loan-default

Create a virtual environment (optional but recommended):

python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

pip install -r requirements.txt
Run the Jupyter Notebook:

jupyter notebook notebook/decision_tree_random_forest.ipynb

📈 Sample Output
Decision Tree and Random Forest classifiers both built and evaluated.

Insights gained on FICO scores, interest rates, and loan purpose.

Random Forest generally provided better predictive performance.

📚 Acknowledgements
Project guided by Jose Portilla's Udemy course on Data Science and Machine Learning.

📜 License
This project is for educational purposes only.
