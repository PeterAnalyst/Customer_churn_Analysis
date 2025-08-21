#📊 Customer Churn Analysis with Machine Learning
📌 Project Overview

Customer churn (the loss of clients or subscribers) is one of the most critical challenges businesses face. This project analyzes a telecom dataset to identify patterns and factors that contribute to customer churn. Using Python, Pandas, Matplotlib, Seaborn, and Scikit-learn, I built data visualizations and applied machine learning techniques to predict churn behavior.

The goal is not only to predict customer churn but also to generate actionable insights that can help businesses retain valuable customers.
---

#🔑 Key Features

*Exploratory Data Analysis (EDA):
  * Visualized churn by contract type, tenure, and payment methods.
  * Correlation heatmaps to understand feature relationships.
  * Segmentation of customers by tenure and contract type.

* Feature Engineering:
  * Created tenure bins for segmentation.
  * Encoded categorical variables.
  * Handled missing values and scaled numeric features.

* Machine Learning Models:
  * Logistic Regression for churn prediction.
  * Feature importance analysis using Decision Trees.
  * Evaluation with Confusion Matrix, Accuracy, Precision, Recall, and F1-score.

* Data Visualizations:
 * Churn rate comparison across categories (contract type, internet service, etc.).
 * Distribution plots and bar charts to highlight churn trends.
---
# 🛠️ Tools & Technologies
* Programming Language: Python
* Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* Environment: Jupyter Notebook
---
📂 Repository Structure
  
```
📁 Churn-Analysis

│── 📄 Churn_Analysis.ipynb      # Jupyter notebook with full analysis
│── 📊 images/                   # Visualizations (churn by city, heatmaps, etc.)
│── 📄 README.md                 # Project documentation (this file)
```
---
# 📈 Results & Insights
* Customers on month-to-month contracts showed the highest churn rate.
* Electronic check payments were strongly associated with churn compared to automatic bank transfers or credit card payments.
* Tenure plays a big role: customers with shorter tenures are more likely to churn.
* Logistic Regression achieved a good baseline accuracy, while decision tree analysis revealed the most influential features.
---
 # 🚀 How to Run the Project

1. Clone the repository:
```
git clone https://github.com/your-username/Churn-Analysis.git
cd Churn-Analysis
```

2. Install dependencies:
```
pip install -r requirements.txt
```

3. Open the Jupyter notebook:
```
jupyter notebook Churn_Analysis.ipynb
```
---
# 👤 Author
👋 Hi, I'm Peter Junior Nwachineke – a passionate Data Analyst with hands-on experience in SQL, Power BI, Excel, and Python. I'm currently pursuing an MBA in International Business Management at ISTEC and building data projects that turn raw information into actionable insights. I'm especially interested in process automation, dashboard reporting, and helping businesses make smarter, data-driven decisions.

📧 [Email](peter.j.nwachineke@gmail.com)

🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/peter-j-nwachineke-819291247/)
