# 🛍️ Retail Customer Analytics Project

This project is an end-to-end analytics solution that uncovers deep insights into customer behavior, churn risk, and marketing performance for a retail business. It combines powerful data analysis in **Python** with a dynamic **Power BI dashboard**, making it perfect for data storytelling, stakeholder reporting, and portfolio display.

---

## 📁 Folder Structure
```
retail_analytics_project/
├── data/                      # Raw and processed data files
├── notebooks/                # Python notebooks for EDA, ML
│   ├── 01_eda.ipynb
│   ├── 02_churn_model.ipynb
│   └── 03_customer_segmentation.ipynb
├── retail_dashboard.pbix     # Power BI dashboard file
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

---

## 📊 Features

### Python (Jupyter Notebooks)
- ✅ **EDA**: Income, Age, Spending, Recency trends
- ✅ **Feature Engineering**: Customer tenure, total spend, total purchases
- ✅ **Customer Segmentation**: KMeans clustering into behavioral groups
- ✅ **Churn Prediction**: Random Forest model + Partial Dependence Plots
- ✅ **Export to CSV** for BI tools

### Power BI Dashboard
- 📌 Multi-tab layout:
  - **Overview**: KPIs, churn rate, customer count
  - **Customer Segmentation**: Avg spend, segment size, age distribution
  - **Churn Analysis**: Risk trends by tenure, income, complaints
  - **Campaign Effectiveness**: Response rates and behavior
- 🎛️ Interactive slicers by segment, churn status, demographics
- 📈 Visual storytelling for business decisions

---

## 📦 Setup & Run

### 🔧 1. Clone Repo & Install Requirements
```bash
git clone https://github.com/your-username/retail-analytics-project.git
cd retail-analytics-project
pip install -r requirements.txt
```

### 💡 2. Run Python Notebooks
Use Jupyter or VS Code to run:
- `01_eda.ipynb`
- `02_churn_model.ipynb`

Output: `outputs/customer_churn_segments.csv`

### 📈 3. Open Power BI Dashboard
- File: `retail_dashboard.pbix`
- Make sure `customer_churn_segments.csv` is loaded as a table

---

## 📚 Tech Stack
- **Python**: Pandas, Scikit-learn, Matplotlib, Seaborn
- **Machine Learning**: Random Forest, KMeans
- **Power BI**: Visual Analytics, DAX, Transform Data

---

## 🧠 Use Cases
- 🔍 Analyze churn risk by demographics and behavior
- 🎯 Segment customers for targeted marketing
- 📊 Present business-ready dashboards to stakeholders

---

## 📌 License
This project is for educational and portfolio use.

---

## 🙋‍♂️ Author
**Rahul Ghantasala**  
Passionate about solving real-world problems with data. Let’s connect on [LinkedIn](https://linkedin.com) or check out more projects on [GitHub](https://github.com/your-username).
 
