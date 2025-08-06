# 🍕 Analyzing Pizza Sales Data with Python
## 📌 Project  Overview
This Python project focuses on cleaning, merging, and analyzing pizza sales data for a takeout restaurant. The business had a part-time analyst who began initial cleaning, but left you a task list and raw files to complete the job. Your work involved performing data wrangling, integrating additional sources, and visualizing key insights.

✅ **Goal:** Deliver a final clean dataset with a visual breakdown of sales by pizza category.

## 📁 Data Sources
pizza_sales.xlsx — Main transaction-level sales data

pizza_size.csv — Pizza size reference

pizza_category.csv — Pizza category reference

another_pizza_sales.xlsx — Manually captured sales during system downtime

pizza_sales_voucher.xlsx — Voucher sales data

## 🧠 Key Tasks Completed
### 🧹 Data Cleaning
* Displayed top/bottom rows and descriptive statistics

* Counted null values and checked for duplicates

* Filtered rows where unit_price > 20 (example) and by specific pizza name/date

* Dropped invalid and null rows using index values

* Removed unnecessary columns: unit_price, order_time, pizza_id

* Converted order_date to date format

* Changed text to title case and replaced "Feta Cheese" with "Mozzarella" in ingredients

* Removed extra whitespace in pizza_name

### 🔁 Data Transformation
* Created a discount column (10% of unit price)

* Grouped data by pizza size for sales summaries

* Sorted data on multiple conditions (e.g., by category and price)

* Merged pizza_sales_df with size and category data

* Created a pizza_full_name column from name and ingredients (planned but not shown in current script)

### ➕ Data Augmentation
Appended new sales data from:

* another_pizza_sales.xlsx

* pizza_sales_voucher.xlsx

Inserted one row at the start and one at the end of the dataset manually (as per instructions)

### 📊 Visualization
Created a box plot showing the distribution of total_price by pizza category using Seaborn and Matplotlib.

### 📤 Export (Planned or Pending in Script)
Cleaned dataset and box plot are ready for export (not shown in script but implied in task list).

## 📸 Example Output
<p align="center"> <img src="Boxplot showing distribution of sales by category.png" width="600" alt="Boxplot by Pizza Category"> </p>

## 🛠 Technologies Used
* Python 3.x

* pandas

* matplotlib

* seaborn

* openpyxl

## 🧠 Skills Demonstrated
* Data wrangling and preprocessing

* Merging and aggregating datasets

* Text normalization and feature engineering

* Data visualization and storytelling

* Working with .xlsx and .csv formats

## 🚀 Getting Started
Clone this repo:

    git clone https://github.com/your-username/pizza-sales-analysis.git
    cd pizza-sales-analysis
    
Install dependencies:

    pip install pandas matplotlib seaborn openpyxl
    
Run the script:

    python pizza_cleaning_script.py

## 📬 Contact
If you have any questions or suggestions, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/keegan-murphy-3a3b99218) or check out my [Portfolio](https://keegan-murphy-portfolio.notion.site/Keegan-Murphy-Portfolio-191c89a2d2f380f4a3e7f98aeb368139).
