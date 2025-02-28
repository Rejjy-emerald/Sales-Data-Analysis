# Sales Data Analysis

## 📌 Overview
This project analyzes sales data to uncover trends, visualize revenue distribution, and build a predictive model for revenue forecasting. The dataset contains sales-related information such as revenue, unit cost, unit price, and cost across various products and countries. This is a data analysis project that examines sales data to uncover insights, trends, and potential predictive models. The project involves data cleaning, exploratory data analysis (EDA), visualization, and machine learning modeling.

## 🎯 Objective
The objective of this project is to analyze sales data to:
- Identify key sales trends.
- Understand customer purchasing behavior.
- Develop predictive models to forecast future sales.

## 📊 Key Insights
- Seasonal trends significantly impact sales performance.
- High correlation exists between promotional discounts and increased sales volume.
- Machine learning models provide reliable forecasts for future sales based on historical data.

## 🛠️ Technologies Used
The following Python libraries and tools are used in this project:
- pandas for data manipulation
- matplotlib and seaborn for data visualization
- scikit-learn for machine learning modeling
- Jupyter Notebook for analysis and documentation
- SQL for data cleaning

## Files in Repository
- super sales project.ipynb: Jupyter Notebook with full data analysis and model training
- cleaned_sales_data.csv: Processed dataset after cleaning
- sales data.xlsx: cleaned dataset with SQL
- salesforcourse-4fe2kehu.xlsx: Original Dataset

## Dataset
- The dataset is a raw Excel file named **salesforcourse-4fe2kehu.xlsx**
- The SQl cleaned Excel file named **sales data.xlsx**
- The analysis focuses on the cleaned sheet: **cleaned sales file**.

## Project Workflow
#### 1. Data Loading
- The dataset is loaded from an Excel file using pandas.read_excel().
- Initial exploration includes checking descriptive statistics and missing values.

#### 2. Exploratory Data Analysis (EDA)
- Summary statistics are computed.
- Missing values are analyzed and handled.
- Visualizations include:
  - Histograms and bar charts for sales distribution.
  - Scatter plots for correlations.
  - Heatmaps for correlation analysis.
  - Line plots to analyze trends over time.

#### 3. Data Preprocessing
-Handling missing values.
-Encoding categorical variables.
-Feature engineering for better model performance.

#### 4. Machine Learning Model

- The dataset is split into training and testing sets using train_test_split().
- A predictive model is trained using:
  -Linear Regression
  -Decision Trees
  -Random Forest
- Model performance is evaluated using accuracy metrics such as MAE, MSE, RMSE.

#### 5. Results & Insights
- Key trends and patterns in sales data are highlighted.
- Model performance is compared across different algorithms.
- Business insights and recommendations are provided.

## How to Use
- Ensure you have Python installed along with the required libraries.
-Download the dataset and place it in the project directory.
-Run the Jupyter Notebook step by step to reproduce the analysis.

## Future Improvements
- Incorporate deep learning models.
- Improve feature selection and engineering.
- Automate report generation with interactive dashboards.

## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

## How to Run
#### 1. Clone the repository:
git clone https://github.com/Rejjy-emerald/sales-data-analysis.git
cd sales-data-analysis


#### 2. Install dependencies:
pip install pandas numpy matplotlib seaborn scikit-learn

#### 3. Run the Jupyter Notebook to execute the analysis:
jupyter notebook super_sales_project.ipynb

## Conclusion
This project provides key insights into sales trends and demonstrates the use of machine learning for revenue prediction. The analysis showcases the importance of data preprocessing, visualization, and model evaluation in real-world sales forecasting scenarios.

## Author
Nwawuisi Rejoice Mmesomachukwu (LinkedIn)
[GitHub Profile](https://github.com/Rejjy-emerald)

## License
This project is licensed under the MIT License 

## Contact
For any questions or contributions, feel free to reach out!
