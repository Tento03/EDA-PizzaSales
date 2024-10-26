# Pizza Sales Exploratory Data Analysis (EDA)

## Overview
This project performs **Exploratory Data Analysis (EDA)** on a pizza sales dataset to explore sales trends, customer preferences, and revenue patterns. Through EDA, we aim to uncover insights into pizza sizes, categories, and ingredients that drive sales, as well as the performance of different pizzas over time.

### Key Objectives:
- Understand sales patterns based on date and time.
- Identify popular pizza types, sizes, and categories.
- Analyze revenue trends and peak sales periods.
- Investigate customer preferences for different ingredients and pizza combinations.

## Dataset
The dataset contains the following columns:

| Column Name          | Description                                    |
|----------------------|------------------------------------------------|
| `order_details_id`    | Unique identifier for each order detail        |
| `order_id`           | Identifier for each order                      |
| `pizza_id`           | Unique identifier for each pizza               |
| `quantity`           | Number of pizzas ordered                       |
| `order_date`         | Date of the order                              |
| `order_time`         | Time of the order                              |
| `unit_price`         | Price per pizza unit                           |
| `total_price`        | Total price of the order (quantity * unit_price)|
| `pizza_size`         | Size of the pizza (e.g., small, medium, large)  |
| `pizza_category`     | Pizza category (e.g., vegetarian, non-vegetarian)|
| `pizza_ingredients`  | Ingredients of the pizza                       |
| `pizza_name`         | Name of the pizza                              |

## Steps Involved in the Analysis

### 1. **Data Preprocessing**
   - Handling missing values.
   - Converting `order_date` and `order_time` to appropriate datetime format.
   - Extracting features such as day, month, and hour from `order_date` for time-based analysis.
   - Cleaning and categorizing `pizza_size` and `pizza_category`.

### 2. **Sales Trends Over Time**
   - Analyzing sales over time based on `order_date`.
   - Visualizing daily, weekly, and monthly sales trends.
   - Identifying peak sales hours using `order_time`.

### 3. **Pizza Preferences**
   - Finding the most popular pizzas using `pizza_name`.
   - Analyzing the sales distribution by `pizza_size` and `pizza_category`.
   - Investigating customer preferences for specific `pizza_ingredients`.

### 4. **Revenue Analysis**
   - Calculating total revenue per order using `total_price`.
   - Visualizing revenue trends by pizza type, size, and category.

### 5. **Time-Based Sales Patterns**
   - Analyzing sales based on the day of the week and time of day.
   - Finding correlations between `order_time`, `pizza_size`, and revenue.

## Key Findings
- **Popular Pizza Types**: Certain pizza names and ingredient combinations are ordered more frequently, influencing sales.
- **Revenue Drivers**: Pizza size and category significantly affect overall revenue generation.
- **Peak Sales Times**: Lunch and dinner hours see the highest sales, with specific trends on weekends.

## Visualizations
- Line plots for sales trends over time.
- Bar charts for pizza size and category preferences.
- Heatmaps for correlations between sales metrics.
- Pie charts for revenue distribution by pizza type.



## Conclusion
This EDA provides valuable insights into pizza sales trends, customer preferences, and factors driving revenue. These insights can guide marketing strategies, menu adjustments, and operational improvements.

---

