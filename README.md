# creditEDA
# Credit Risk Analysis

## Project Overview
This project focuses on analyzing credit risk using `application_data.csv` and `previous_application.csv`. The objective is to preprocess the data, handle missing values, perform exploratory data analysis (EDA), and extract meaningful insights to understand credit risk patterns.

## Dataset
- `application_data.csv`: Contains information about loan applicants, including demographic details, credit history, and financial attributes.
- `previous_application.csv`: Contains data on previous loan applications submitted by clients.

## Key Features
### Data Preprocessing
- **Handling Missing Values**: Dropped columns with high missing values, imputed missing values using median/mode.
- **Feature Engineering**: Created new categorical features like `AMT_CREDIT_Category`, `AGE_Category`, and `YEARS_BIRTH`.
- **Data Transformation**: Normalized numerical features and converted categorical variables into appropriate formats.

### Exploratory Data Analysis (EDA)
- **Visualizations**:
  - Boxplots to analyze feature distributions.
  - Bar charts and pie charts for categorical variables.
  - Heatmaps for correlation analysis.
  - Pairplots to examine relationships between numerical features.

- **Segmentation**:
  - Analyzed differences in features based on `TARGET` values (loan repayment status).

## Technologies Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/credit-risk-analysis.git
   cd credit-risk-analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook or Python script to perform data analysis:
   ```bash
   jupyter notebook analysis.ipynb
   ```

## Results and Insights
- Identified key factors contributing to credit risk.
- Segmented applicants based on risk categories.
- Explored correlations between financial attributes and loan default probability.

## Contributing
If you'd like to contribute, please fork the repository and submit a pull request with your improvements.

## License
This project is open-source and available under the MIT License.

