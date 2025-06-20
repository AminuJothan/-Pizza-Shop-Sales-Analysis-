## -Pizza-Shop-Sales-Analysis-
* A year's worth of sales from a fictitious pizza place, including the date and time of each order and the pizzas served, with additional details on the type, size, quantity, price, 


## 📁Dataset Description
* The dataset is composed of 4 CSV files:
orders.csv – Contains the order ID, date, and time.
* order_details.csv – Contains order_id, pizza_id, and quantity.
* pizzas.csv – Contains pizza_id, size, price, and pizza_type_id.
* pizza_types.csv – Contains pizza_type_id, name, category, and ingredients.
* A data dictionary is also provided for reference.


## 🔧 Tools Used

* Python 🐍
* Pandas 📊
* Matplotlib 📈
* Seaborn 🎨
* Jupyter Notebook 📒


## 🧼 Data Cleaning Steps
* Merged all four datasets into a single DataFrame.
* Converted date and time columns to datetime format.
* Handled missing values and removed duplicates.
* Created a new column for total_price = quantity × price.


## 📊 Key Insights
* 💵 Total Revenue: $817,860.05
* 🔢 Total Pizzas Sold: 49574 unit
* 📦 Total Orders: 21350 Orders
* 🍕 Top 5 Bestselling Pizzas
* 🕒 Peak Hour for Sales
* 🗓️ Most Profitable Day of the Week
* 📉 Underperforming Pizza Types
* 📅 Sales Trends Across Months


Visualizations including bar charts, line chart, pie chart and heatmaps were created to support the analysis.
