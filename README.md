# Superstore_Sales
This project analyzes Superstore sales data to uncover trends in product categories, regions, and customer segments. It explores the impact of discounts and shipping modes on profit, visualizes key insights, and builds a predictive model to estimate profit, supporting data-driven business decisions.
# 1. Introduction Slide / Section
Objective: Understand key sales drivers and forecast profit.

Tools Used: Python, Pandas, Matplotlib/Seaborn, Scikit-learn.

Dataset: Superstore sales data (Orders, Regions, Products, Segments).

# 2. Data Exploration & Cleaning
Checked for missing values and corrected data types.

Performed feature engineering (e.g., extracted month from order date).

Removed outliers from extremely high discounts or losses.

📊 Sample Chart: Boxplot showing profit distribution by category.

# 3. Exploratory Data Analysis (EDA)
Insight	Visualization
Sales peaks during Q4	Line chart with rolling avg
Technology is most profitable	Bar plot by category
Discounts reduce profit	Scatter plot: Discount vs Profit
West performs best regionally	Choropleth map of sales by state

🧠 Business Implication: Refine discounts, stock technology products, focus on West region.

# 4. Predictive Modeling
Model: Random Forest Regressor

Target: Profit

Features: Sales, Discount, Quantity, Month

📈 Result:

RMSE: ~2000

Feature importance shows Discount and Sales most predictive

# 5. Conclusion & Recommendations
✅ Optimize high-discount product offerings
✅ Focus marketing efforts on profitable segments (Tech, Consumer)
✅ Monitor shipping cost and mode (Same Day often reduces profit)
✅ Use forecasting to anticipate low-profit orders in advance


