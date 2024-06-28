# Finance Project

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset Description](#dataset-description)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Analysis](#analysis)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)
9. [Contact](#contact)

## Introduction
This project involves analyzing financial data to understand various factors influencing creditworthiness and default rates. The analysis focuses on credit amounts, incomes, occupations, regional influences, and other key financial attributes to identify patterns and correlations that are crucial for risk management in credit lending.

## Dataset Description
The dataset consists of three main files:

1. **Column Description**: Provides descriptions of the various columns in the dataset.
2. **Application Data**: Contains information about applicants, including their demographic details, income, credit amounts, and employment information.
3. **Previous Data**: Includes historical data on previous loans taken by the applicants.

### Key Insights from the Dataset

- **Income and Credit Amount Distribution**: The distribution of total income is heavily skewed towards the lower end for most occupation types, with very few individuals having high income. Credit amounts are more uniformly distributed but also show a skew towards lower amounts.
- **Occupation Type and Financial Attributes**: Certain occupations, like laborers, drivers, and sales staff, dominate the lower credit and income brackets, while higher credit and income brackets include more professionals such as accountants, managers, and IT staff.
- **Target Outcomes by Occupation**: Default rates appear relatively higher in occupations associated with lower economic stability. High-skill occupations generally show fewer defaults.
- **Regional Influence and Payment Difficulty**: Regional variables such as REGION_POPULATION_RELATIVE, REGION_RATING_CLIENT, and REGION_RATING_CLIENT_W_CITY significantly influence payment behaviors.
- **Credit and Employment Information**: Key financial and employment metrics such as AMT_CREDIT and DAYS_EMPLOYED show important correlation patterns with other variables.
- **Flags (Document and Social Circle Variables)**: Many FLAG_DOCUMENT variables show little to no correlation with payment difficulties.
- **Credit Bureau Information**: Variables related to the amount requested from the credit bureau show patterned correlations among themselves but are less correlated with payment difficulties.
- **Age and Income**: Age alone is not a strong predictor of payment behavior, and income level shows low correlation with payment difficulties.

## Installation
To get started with this project, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/finance-project.git
    cd finance-project
    ```

2. Set up a virtual environment (optional but recommended):
    ```sh
    python -m venv env
    source env/bin/activate  # On Windows, use `env\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
1. Ensure you have the datasets available in the appropriate directories "data\".
2. Install Jupyter if you haven't already:
    ```sh
    pip install jupyter
    ```
3. Run the Jupyter Notebook:
    ```sh
    jupyter notebook financeproject.ipynb
    ```
4. This will open the Jupyter Notebook interface in your web browser. From there, you can run the cells in the notebook to perform the analysis.

## Analysis
The analysis focuses on several key areas:

- **Credit Amount and Income Distribution**: Analyzing the distribution of credit amounts and incomes across different occupation types and default groups.
- **Occupation Type and Financial Attributes**: Examining the financial attributes associated with different occupations and their correlation with default rates.
- **Regional Influence**: Investigating how regional variables affect payment behaviors and financial stability.
- **Credit and Employment Information**: Understanding the interplay between employment duration, loan amounts, and other financial behaviors.
- **Flags and Social Circle Variables**: Analyzing the impact of document flags and social circle variables on payment difficulties.
- **Credit Bureau Information**: Evaluating the correlation between credit bureau inquiries and payment behaviors.
- **Age and Income**: Assessing the predictive power of age and income on payment difficulties.

## Results
The results of the analysis are documented in the `results/` directory and include:

- Visualizations (charts, graphs)
- Summary reports
- Detailed analysis notebooks

## Contributing
Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit them (`git commit -m 'Add your feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or inquiries, please contact Ritik Sunil Khapre, emial- ritik.khapre5202@gmail.com.
