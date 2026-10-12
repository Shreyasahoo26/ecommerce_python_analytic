# E-Commerce Sales & Customer Analytics (Python)

## 📌 Project Overview
An end-to-end Exploratory Data Analysis (EDA) and data cleaning project built using Python. This project simulates an e-commerce dataset to uncover actionable business insights regarding product category performance, sales trends, and customer purchasing behaviors.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

## 🔄 Project Workflow
1. **Data Simulation & Messy Data Generation:** Created a dataset with intentional missing values, duplicates, and unformatted strings to simulate real-world data challenges.
2. **Data Cleaning & Preprocessing:** 
   * Removed duplicate rows to ensure data integrity.
   * Handled missing values using median imputation and categorical defaults.
   * Cast data types correctly (dates, integers).
3. **Feature Engineering:**
   * Calculated Gross and Net Sales (accounting for quantity and discounts).
   * Extracted temporal features (Year-Month, Day of Week, Hour of Day).
   * Segmented customers into VIP vs. Regular tiers based on total spend.
4. **Exploratory Data Analysis (EDA):**
   * Aggregated data to find top-performing product categories by revenue.
   * Analyzed order distribution across days of the week.
5. **Data Visualization:** Generated professional bar plots and count plots using Seaborn and Matplotlib to communicate findings visually.

## 📊 Key Business Insights
* **Category Dominance:** Electronics and Clothing generate the highest gross and net sales, accounting for over 50% of total revenue.
* **Discount Impact:** Higher discount percentages (15-20%) significantly drive volume in lower-priced categories like Beauty and Home & Kitchen.
* **Ordering Patterns:** Order volume peaks during mid-week days, helping optimize targeted email marketing schedules.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)