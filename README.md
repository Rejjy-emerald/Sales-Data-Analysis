# Sales Data Analysis

## 📌 Overview
This project analyzes sales data to uncover trends, visualize revenue distribution, and build a predictive model for revenue forecasting. The dataset contains sales-related information such as revenue, unit cost, unit price, and cost across various products and countries.

## 🎯 Objective
The objective of this project is to analyze sales data to:
- Identify key sales trends.
- Understand customer purchasing behavior.
- Develop predictive models to forecast future sales.

## 📊 Key Insights
- **Revenue Trends:** Identified periods of high sales revenue across different countries.
- **Product Performance:** Determined top-selling products and their contribution to total revenue.
- **Cost vs. Revenue Relationship:** Analyzed the impact of unit cost and price on revenue generation.
- **Predictive Model Performance:** Achieved an RMSE of 36.41, demonstrating the model's ability to predict revenue.

## 🛠️ Technologies Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Tools:** Jupyter Notebook, SQL for data cleaning, Power BI for dashboard visualizations

## Files in Repository
- super sales project.ipynb: Jupyter Notebook with full data analysis and model training
- cleaned_sales_data.csv: Processed dataset after cleaning
- sales data.xlsx: cleaned dataset with SQL
- salesforcourse-4fe2kehu.xlsx: Original Dataset

## 🔍 Dataset
- **Source:** Provided sales data (Excel format)
- **Key Columns:**
  - Date: Sales date
  - Country: Country where the sale occurred
  - Product Category: Category of the product sold
  - Revenue: Total revenue generated
  - Unit Cost: Cost per unit
  - Unit Price: Selling price per unit
  - Cost: Total cost

## 📊 Analysis & Visualizations
#### 1. Data Cleaning
- Checked for missing values and duplicates.
 Converted Date column to datetime format.
- Removed outliers based on the 95th percentile.

#### 2. Exploratory Data Analysis (EDA)
- **Revenue Trends**: Visualized sales revenue over time.
- **Revenue Distribution**: Histogram of revenue.
- **Revenue by Country**: Bar chart showing total revenue by country.
- **Revenue by Product Category**: Pie chart representation.
- **Top-Selling Products**: Bar chart for the highest revenue-generating products.
- **Correlation Matrix**: Heatmap to identify relationships between numerical variables.

#### 3. Predictive Modeling
- **Model Used**: Ridge Regression with Polynomial Features.
- **Feature Selection**: Unit Cost, Unit Price, Cost.
- **Hyperparameter Tuning**: Grid Search applied to optimize polynomial degree and Ridge alpha value.
- **Model Evaluation:**
   - **Mean Absolute Error (MAE)**: Measures average prediction error.
   - **Mean Squared Error (MSE)**: Measures variance of prediction errors.
   - **R2 Score**: Evaluates model performance.
- **Final RMSE on Test Set: 36.41.**

## How to Run
#### 1. Clone the repository:
git clone https://github.com/Rejjy-emerald/sales-data-analysis.git
cd sales-data-analysis

## Future Improvements
- Incorporate deep learning models.
- Improve feature selection and engineering.
- Automate report generation with interactive dashboards.

## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

## Conclusion
This project provides key insights into sales trends and demonstrates the use of machine learning for revenue prediction. The analysis showcases the importance of data preprocessing, visualization, and model evaluation in real-world sales forecasting scenarios.

## Author
Nwawuisi Rejoice Mmesomachukwu (LinkedIn)
[GitHub Profile](https://github.com/Rejjy-emerald)

## License
This project is licensed under the MIT License 

## Contact
For any questions or contributions, feel free to reach out!
