![](images/decision_confusion.PNG)
# 🌀 Customer Churn Analysis with Machine Learning
---
## 📌 Project Overview
Customer churn (the loss of clients or subscribers) is one of the most critical challenges businesses face. This project analyzes a telecom dataset to identify patterns and factors that contribute to customer churn. The workflow includes:
  * **Data cleaning** & feature engineering
  * **Exploratory Data Analysis (EDA)** to uncover churn drivers
  * **Interactive visualizations** to communicate insights
  * **A predictive Decision Tree model** with performance evaluation
  * **Business recommendations** to reduce churn

#### Tools: Python, Pandas, Matplotlib, Seaborn, Scikit-learn, Plotly
---
## 🎯 Key Goals
  * Understand patterns behind customer churn
  * Visualize churn across demographics, services, contract types, and payment methods
  * Predict churn with an interpretable machine learning model
  * Translate findings into **actionable business recommendations**
---
## 🔎 Executive Summary
  * Exploratory analysis shows higher churn among **month-to-month, low-tenure**, and **non-bundled** customers; **Electronic Check** users also churn more.
  * A baseline **Decision Tree** model achieves **77% accuracy** and highlights **Contract Type, online_security** and **Tenure** as the most important features.
  * Recommended actions: **early-life onboarding, contract-migration offers, service bundling, payment-method nudges**, and **risk-based outreach.**
---
## 🔑 Key Features
**Exploratory Data Analysis (EDA):**
  * Visualized churn by contract type, tenure, payment method, services, and demographics
  * Correlation heatmaps to understand feature relationships
  * Segmentation of customers by tenure and contract type

**Feature Engineering:**
  * Created **tenure bins** for segmentation
  * Encoded categorical variables
  * Handled missing values

**Machine Learning Model:**
  * Decision Tree Classifier for churn prediction
  * Evaluation using Confusion Matrix, Accuracy, Precision, Recall, and F1-score
  * Feature importance ranking to interpret churn drivers

**Data Visualizations:**
  * Churn distribution across demographics & services
  * Churn by contract type, internet service, payment method
  * Feature correlation heatmap
  * Feature importance from Decision Tree

## 🛠️ Tools & Technologies
  * **Programming Language:** Python
  * **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn
  * **Environment:** Jupyter Notebook
---
## 📂 Repository Structure
  
```
📁 Churn-Analysis

│
├── data/  
│   └── raw/                
│
├── 📄 Churn_Analysis.ipynb       # Jupyter notebook with full analysis 
│
├── 📊 images/                    # Visualizations
│   ├── churn_by_city.png  
│   ├── churn_by_contract.png  
│   ├── correlation_heatmap.png  
│   ├── tenure_segmentation.png  
│   ├── decision_tree_importance.png  
│   ├── decision_confusion.PNG  
│   ├── churn_rate_reason.PNG  
│   └── … (other churn plots)
│
├── scripts/                # Python scripts for reusable functions  
│
└── 📄 README.md                 # Project documentation (this file)  
```
---
## 🔍 Analysis Highlights
### 1. Data Cleaning & Preprocessing
- Removed duplicates if any, missing or null values, and removed irrelevant columns
- Encoded categorical variables for machine learning
- Engineered new features such as **tenure bins** for segmentation

### 2. Exploratory Data Analysis (EDA)
Analyzed churn patterns across multiple dimensions:

- **Contract Type**: Month-to-month customers churn the most
- **Tenure Groups**: Short-tenure customers are high-risk
- **Charges**: Higher charges correlate with higher churn probability
- **Demographics**: Non Senior citizens, customers without partners/dependents, and female gender churn more
- **Services**: Customers without Tech Support/Online Security churn more
- **Payment Method**: Electronic check users churn more frequently
- **Customer Lifetime Value (CLV)**
- **Correlation Heatmap** shows relationships across numeric features

### 3. Visualizations
Key plots saved in `/images/`:
- Churn distribution by contract, tenure, age, and city
- Churn by partner/dependent status
- Service usage vs. churn (Online Security, Tech Support, etc.)
- Payment method vs. churn
- Correlation heatmap
- Feature importance from Decision Tree

### 4. Machine Learning Model
- **Model**: Decision Tree Classifier  
- **Metrics**: Accuracy = 77%, with Precision, Recall, and F1-score  
- **Evaluation**: Confusion Matrix and Feature Importance plots

### 📈 Business Insights
- **Month-to-month contracts** → highest churn risk  
- **Short-tenure customers** → over 75% of churned users were young, high-risk profiles  
- **Competitors** → 1/3 churned due to better offers and devices  
- **Support Issues** → poor customer service cited frequently as a churn driver  
- **Demographics** → 64% churners had no partner, seniors churned mostly due to competitors and service attitude .
---
Key factors driving churn: Contract type, tenure, internet service, payment method.
![](images/Decision.PNG)

---
## Business Recommendation
  1. **Early-life onboarding** (first 60 days): guided setup, “first-value” checklist, proactive support ticket on day 7/21; measure 90-day churn.
  2. **Contract migration offers:** targeted discounts to move month-to-month to 12–24 months; A/B test incentive levels
  3. **Service bundling:** bundle Online Security/Tech Support with modest discount; cross-sell in-app nudges to low-tenure users.
  4. **Payment method nudges:** encourage autopay/credit-card enrollment to reduce friction (email + in-app; highlight benefits).
  5. **Risk-based outreach:** apply the Decision Tree model weekly to generate a high-risk customer list for personalized outreach.
     
---
 ## How to Run the Project
```
git clone https://github.com/PeterAnalyst/Customer_churn_Analysis.git
cd Customer_churn_Analysis
pip install -r requirements.txt
jupyter notebook Churn_Analysis.ipynb
```
or open it in **Google Colab** for an interactive experience.
 
---
# 👤 Author
👋 Hi, I'm Peter Junior Nwachineke – a passionate Data Analyst with hands-on experience in SQL, Power BI, Excel, and Python. I’m currently pursuing an MBA in International Business Management at ISTEC and building data projects that turn raw information into actionable insights.

I specialize in process automation, dashboard reporting, and churn/retention analytics, with the goal of helping businesses make smarter, data-driven decisions.

📧 [Email](peter.j.nwachineke@gmail.com)

🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/peter-j-nwachineke-819291247/)
