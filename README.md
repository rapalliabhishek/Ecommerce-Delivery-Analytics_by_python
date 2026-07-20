# 📦 E-Commerce Delivery Analytics

## 📖 Project Overview

This project analyzes an E-Commerce Delivery dataset using **Python, Pandas, and Matplotlib** to uncover business insights related to delivery performance, customer satisfaction, product sales, and platform performance.

The objective is to transform raw delivery data into meaningful insights through data cleaning, feature engineering, exploratory data analysis (EDA), visualizations, and a dashboard.

---

# 🎯 Objectives

* Analyze delivery performance across different platforms.
* Identify the fastest delivery platform.
* Find the platform with the highest order value.
* Analyze customer feedback and service ratings.
* Identify delivery delays and refund patterns.
* Discover the most sold product categories.
* Build an analytical dashboard using Python.

---

# 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Google Colab
* GitHub

---

# 📂 Project Structure

```text
Ecommerce-Delivery-Analytics/
│
├── README.md
├── LICENSE
├── requirements.txt
├── .gitignore
│
├── data/
│   └── Ecommerce_Delivery_Analytics_New.csv
│
├── notebooks/
│   └── Ecommerce_Delivery_Analytics.ipynb
│
├── python/
│   └── ecommerce_delivery_analytics.py
│
├── screenshots/
│   ├── dashboard.png
│   ├── chart1_avg_order_value.png
│   ├── chart2_service_rating.png
│   ├── chart3_feedback_breakdown.png
│   ├── chart4_delay_vs_rating.png
│   ├── chart5_correlation_heatmap.png
│   └── business_summary.png
│
└── outputs/
    ├── business_summary.csv
    ├── most_selling_products.csv
    └── platform_order_values.csv
```

---

# 📊 Dataset

The dataset contains information related to:

* Platform
* Customer ID
* Product Category
* Order Value (INR)
* Delivery Time (Minutes)
* Delivery Delay
* Refund Requested
* Customer Feedback
* Service Rating

---

# 🧹 Data Cleaning

The following preprocessing steps were performed:

* Checked dataset information
* Identified missing values
* Checked duplicate records
* Removed duplicate records
* Generated descriptive statistics

---

# ⚙ Feature Engineering

Two new features were created:

### Feedback Category

Customer feedback was classified into:

* Excellent
* Good
* Average
* Worst

### Rating Category

Service ratings were categorized as:

* High
* Medium
* Low

---

# 📈 Business Questions Answered

This project answers the following business questions:

* Which platform delivers orders the fastest?
* Which platform generates the highest order value?
* Which platform receives the best customer feedback?
* Which platform experiences the most delivery delays?
* Which platform has the highest refund requests?
* Which platform has the highest and lowest service ratings?
* What is the most sold product category?
* Which customer places the most orders?
* Which product category is most frequently purchased by the most active customer?

---

# 📊 Dashboard

The project includes a Python dashboard displaying:

* Total Orders
* Total Revenue
* Average Service Rating
* Average Delivery Time
* Average Order Value by Product Category
* Average Service Rating by Platform
* Feedback Distribution by Platform
* Delivery Delay vs Rating Heatmap
* Correlation Heatmap

> **Dashboard Screenshot**

Add your dashboard image here after uploading it to the `screenshots` folder.

```markdown
![Dashboard](screenshots/dashboard.png)
```

---

# 📉 Visualizations

The project contains the following visualizations:

### 1. Average Order Value by Product Category

```markdown
![Chart 1](screenshots/chart1_avg_order_value.png)
```

---

### 2. Average Service Rating by Platform

```markdown
![Chart 2](screenshots/chart2_service_rating.png)
```

---

### 3. Feedback Breakdown by Platform

```markdown
![Chart 3](screenshots/chart3_feedback_breakdown.png)
```

---

### 4. Delivery Delay vs Service Rating

```markdown
![Chart 4](screenshots/chart4_delay_vs_rating.png)
```

---

### 5. Correlation Heatmap

```markdown
![Chart 5](screenshots/chart5_correlation_heatmap.png)
```

---

# 📄 Business Summary

Business summary files are available in the `outputs` folder.

These include:

* Business Summary
* Most Selling Products by Platform
* Platform Order Values

---

# 💡 Key Insights

* Identified the fastest delivery platform based on average delivery time.
* Determined the platform generating the highest total order value.
* Analyzed customer feedback distribution across platforms.
* Measured the impact of delivery delays on customer ratings.
* Identified the most sold product category.
* Detected the most active customer and purchasing behavior.
* Explored correlations between delivery time, order value, and service ratings.

---

# 📌 Recommendations

Based on the analysis:

* Reduce delivery delays to improve customer satisfaction.
* Investigate refund-heavy platforms to identify operational issues.
* Promote top-performing product categories.
* Improve service quality on low-rated platforms.
* Monitor delivery performance using dashboard KPIs.

---

# ▶ How to Run the Project

1. Clone the repository.

```bash
git clone https://github.com/<your-username>/Ecommerce-Delivery-Analytics.git
```

2. Install dependencies.

```bash
pip install -r requirements.txt
```

3. Run the notebook or Python script.

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Rapalli Abhishek**

GitHub: https://github.com/rapalliabhishek

