# 🌀 Customer Churn Analysis with Machine Learning
---
## 📌 Project Overview

Customer churn (the loss of clients or subscribers) is one of the most critical challenges businesses face. This project analyzes a telecom dataset to identify patterns and factors that contribute to customer churn. The analysis includes data cleaning, feature engineering, exploratory analysis, visualizations, and a machine learning model for churn prediction. Using Python, Pandas, Matplotlib, Seaborn, and Scikit-learn.
---
### Key goals:
* Understand patterns behind customer churn
* Visualize important metrics (e.g., churn by city, contract type, tenure).
* Build an interpretable predictive model.
* Provide business recommendations to reduce churn.
---

## 🔑 Key Features

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
## 🛠️ Tools & Technologies
* Programming Language: Python
* Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* Environment: Jupyter Notebook
---
## 📂 Repository Structure
  
```
📁 Churn-Analysis

├── data/  
│   ├── raw/                
│
├── 📄 Churn_Analysis.ipynb      # Jupyter notebook with full analysis 
│
├── 📊 images/                   # Visualizations (churn by city, heatmaps, etc.
│   ├── churn_by_city.png  
│   ├── churn_by_contract.png  
│   ├── correlation_heatmap.png  
│   ├── tenure_segmentation.png  
│   ├── decision_tree_importance.png  
│   └── [Any extra plots you want to add]  
│
├── scripts/                # Python scripts for reusable functions  
│   ├── data_preprocessing.py  
│   ├── visualization_utils.py  
│   └── modeling.py  
│
├── 📄 README.md                 # Project documentation (this file) 
└── requirements.txt  
```
---
## 🔍 Analysis Highlights
1. Data Cleaning & Preprocessing
 * Removed duplicates, missing values, and irrelevant columns.
 * Encoded categorical variables.
 * Created new features like tenure bins for segmentation.
 * [Optional: Add your own data wrangling idea here]

2. Exploratory Data Analysis (EDA)
Key breakdowns include:
* Churn by city
* Churn by contract type
* Churn by charge
* Churn across tenure groups
* Churn by gender
* Churn by reason
* Churn by age group (Senoir/Not Senoir Citizen)
* Churn by Partner/No Partner
* Churn by Dependent/No Dependent
* Churn by service used
* Churn by Tech Support
* Churn by Online Security
* Churn by Payment Method
* Churn by customer life time value
* Correlation heatmap to check feature relationships

3. Visualizations
All plots are saved in the visuals/ folder:
* 📊 churn_by_city.png
* 📊 churn_by_contract.png
* 📊 tenure_segmentation.png
* 📊 Churn by reason
* 📊 Churn by age group (Senoir/Not Senoir Citizen)
* 📊 Churn by Partner/No Partner
* 📊 Churn by Dependent/No Dependent
* 📊 Churn by service used
* 📊 Churn by Tech Support
* 📊 Churn by Online Security
* 📊 Churn by Payment Method
* 📊 Churn by customer life time value
* 📊 Correlation heatmap to check feature relationshipChurn by reason
* 📊 Churn by age group (Senoir/Not Senoir Citizen)
* 📊 Churn by Partner/No Partner
* 📊 Churn by Dependent/No Dependent
* 📊 Churn by service used
* 📊 Churn by Tech Support
* 📊 Churn by Online Security
* 📊 Churn by Payment Method
* 📊 Churn by customer life time value
* 📊 Correlation heatmap to check feature relationship
* 🔥 correlation_heatmap.png
* 🌳 decision_tree_importance.png

4. Machine Learning Model

Model: Decision Tree Classifier

Performance evaluated with: Accuracy, Precision, Recall, F1-score, Confusion Matrix

Feature importance visualized using decision tree feature ranking

5. Business Insights

Customers on month-to-month contracts are more likely to churn.

Short-tenure customers have higher churn rates.

Certain cities show above-average churn.

Key factors driving churn: Contract type, tenure, internet service, payment method.
## 📈 Results & Insights
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
✨ Future Work

Test ensemble methods (Random Forest, XGBoost).

Add customer lifetime value analysis.

Deploy churn prediction model as a web app (Flask/Streamlit).
---
# 👤 Author
👋 Hi, I'm Peter Junior Nwachineke – a passionate Data Analyst with hands-on experience in SQL, Power BI, Excel, and Python. I'm currently pursuing an MBA in International Business Management at ISTEC and building data projects that turn raw information into actionable insights. I'm especially interested in process automation, dashboard reporting, and helping businesses make smarter, data-driven decisions.

📧 [Email](peter.j.nwachineke@gmail.com)

🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/peter-j-nwachineke-819291247/)
