# 🛒 Blinkit Grocery Sales Data Analysis using Python (NumPy & Pandas)

## 📌 Overview
This project focuses on analyzing **Blinkit’s grocery sales dataset** using **Python**, **NumPy**, and **Pandas**.  
The objective is to explore sales performance, identify key business trends, and extract actionable insights through data cleaning, transformation, and numerical analysis.

By leveraging Python’s data analysis libraries, this project demonstrates how data can be turned into meaningful insights that help understand product performance, outlet efficiency, and revenue distribution.

---

 🎯 Objective
To perform an in-depth analysis of Blinkit’s grocery sales data and derive valuable insights into:
- Product-wise and outlet-wise sales performance  
- Revenue trends and category distribution  
- Factors influencing total sales  

---

## 🧰 Tools & Libraries Used
- **Python** – Programming language used for analysis  
- **NumPy** – For mathematical and statistical computations  
- **Pandas** – For data manipulation and analysis using DataFrames  

---

## 📁 Dataset Description
The dataset represents **Blinkit’s grocery sales records**. It contains key fields such as:
- `Item_Identifier` – Unique product ID  
- `Item_Weight` – Weight of the product  
- `Item_Fat_Content` – Fat content category  
- `Item_Visibility` – Percentage visibility of the item in the store  
- `Item_Type` – Category of grocery item  
- `Item_MRP` – Maximum Retail Price of the product  
- `Outlet_Identifier` – Unique store ID  
- `Outlet_Size` – Size of the outlet (Small, Medium, Large)  
- `Outlet_Location_Type` – Location of the store  
- `Outlet_Type` – Type of outlet (Supermarket, Grocery Store, etc.)  
- `Item_Outlet_Sales` – Total sales value for each product at the outlet  

---

## 🧮 Steps & Analysis Performed
1. **Importing Libraries**  
   Imported essential Python libraries like NumPy and Pandas.  

2. **Loading the Dataset**  
   Loaded the Blinkit dataset into a Pandas DataFrame for structured analysis.  

3. **Data Cleaning**  
   - Handled missing values using mean/median imputation.  
   - Renamed inconsistent column names for clarity.  
   - Removed unnecessary columns if any.  

4. **Exploratory Data Analysis (EDA)**  
   - Computed descriptive statistics (mean, median, mode, etc.) using NumPy.  
   - Explored sales patterns across product types and outlets.  
   - Checked correlations between MRP, outlet size, and total sales.  

5. **Insights Extraction**  
   - Identified top-performing product categories.  
   - Compared sales based on outlet size and location.  
   - Derived average revenue and sales distribution metrics.  

---

## 📊 Key Insights
- 🛒 Outlets located in Tier-1 cities show higher average sales.  
- 📈 Products with higher MRP generally contribute more to revenue.  
- 🧮 Larger outlets have higher overall sales performance.  
- 🍎 Certain grocery categories (e.g., dairy, snacks) consistently perform better.  

---

## 📚 Learnings
- Data handling and cleaning using **Pandas DataFrames**  
- Performing numerical operations and aggregations using **NumPy**  
- Applying statistical techniques for sales pattern discovery  
- Structuring a data analysis project workflow in Python  

---

## 🚀 How to Run the Project

1. clone repo
   ```bash
   git clone https://github.com/ShaikRukhiya/blinkit-grocery-sales-analysis-python-numpy-pandas.git

2.Navigate to the Project Directory

cd blinkit-grocery-sales-analysis-python-numpy-pandas
3.Run Python Script


💡 Future Enhancements

Add data visualization using Matplotlib 

Build a Power BI dashboard for interactive exploration

Perform predictive modeling 

🏁 Conclusion

This project demonstrates how Python, NumPy, and Pandas can be combined to analyze real-world sales data effectively.
Through data cleaning, computation, and structured analysis, the project provides valuable insights into Blinkit’s grocery sales trends and helps in making data-driven business decisions.

Author: Shaik Rukhiya Masthani
github profile: https://github.com/ShaikRukhiya
Developed as part of a data analysis learning project using Python.

