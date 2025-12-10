# Cafe-Sales-Analytics-Modeling-Power-BI-Visualization
This project provides a practical analytics dashboard for a local cafe, combining machine learning models to predict sales and identify key revenue factors. It uses Power BI to visualize trends, track performance over time, and make the data easy to explore.
# ☕ Cafe Sales Forecasting & BI Analysis (Python & Power BI)

## 📌 Project Overview
This project presents an **end-to-end analytics solution** for a local café's transactional data. It integrates advanced **Machine Learning (ML)** techniques for predictive sales forecasting with **Power BI** for interactive data visualization and historical performance analysis.

The aim is to transform raw sales data into actionable business intelligence, helping the café understand revenue drivers, seasonality, and customer behavior.

## 🛠️ Technology Stack
* **Data Cleaning & Modeling:** Python (Google Colab, Pandas, NumPy)
* **Predictive Models:** Scikit-learn, **XGBoost**, Linear Regression, K-Nearest Neighbors (KNN)
* **Visualization & BI:** Microsoft Power BI Desktop (DAX, Power Query)

## 🚀 Key Objectives & Insights

The analysis successfully addressed critical business questions and provided the following actionable insights:

| Focus Area | Key Finding |
| :--- | :--- |
| Sales Forecasting | Utilized XGBoost to develop a high-accuracy model for predicting future revenue and identifying key feature importance. |
| Seasonality | Confirmed strong sales seasonality with peaks in **Q4** and the month of **June**, which is vital for planning and inventory management. |
| Revenue Drivers | **Salad, Smoothie, and Sandwich** are the top three items driving revenue contribution. |
| Customer Behavior | **Takeaway** orders dominate total sales volume, and the **Digital Wallet** is the most preferred payment method across transactions. |

## 📁 Repository Structure & Files

The repository contains the following core files, enabling full project reproducibility:

| File Name | Description |
| :--- | :--- |
| **`cafe_sales.ipynb`** | **Python Notebook (Google Colab):** Contains all steps for data cleaning, feature engineering, ML model building, comparison, and forecasting. |
| **`cafe_sales.pbix`** | **Power BI Dashboard:** The final interactive report with calculated DAX measures, time dimensions, and visualizations. |
| `cafe_sales_data.csv` | (The original cleaned dataset used for both the ML model and the BI analysis). |
| `dashboard_screenshot.png` | (A visual snapshot of the final Power BI dashboard for quick viewing). |

## 📊 Dashboard Visuals (Snapshot)

*(Place your main dashboard image here)*

![Dashboard Snapshot](dashboard_screenshot.png)
*Figure 1: Main Dashboard Overview showing KPIs, Quarterly Trends, and Revenue Breakdown.*

## ⚙️ How to Run the Project

1.  **Clone the repository:**
    ```bash
    git clone [Insert Your GitHub Repo URL Here]
    ```
2.  **Run the ML Model:**
    * Open the `cafe_sales.ipynb` file in Google Colab or Jupyter Notebook.
    * Run all cells to execute the data processing, train the ML models (KNN, LR, XGBoost), and view the prediction metrics.
3.  **View the Dashboard:**
    * Open the `cafe_sales.pbix` file using Power BI Desktop to interact with the final visualizations and analysis.

---

### 📧 Contact
Created by **[Your Name]** - Connect with me on [Insert Your LinkedIn or Email Link Here]!
