# Project Name
> Lending club case study - Loan Default Analysis


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
This project aims to analyze a loan dataset to understand the factors that contribute to loan defaults. The goal is to identify key indicators that can help lenders assess credit risk, make informed lending decisions and develop insights to mitigate credit loss.The analysis covers a wide range of variables including loan amounts, interest rates, borrower income, and credit history, to predict the likelihood of a borrower defaulting on a loan.

**Business problem :**
The business problem addressed by this project is minimizing financial losses due to loan defaults. By identifying high-risk borrowers and understanding the factors associated with defaults, lenders can develop strategies to mitigate risks and improve their loan portfolio performance.

**Dataset :**
The dataset used in this analysis contains information about thousands of loans, including borrower demographics, loan characteristics, and repayment status. The dataset used in this study includes past loan applicants with various attributes such as:
- **Loan Amount:** The principal amount borrowed.
- **Interest Rate:** The annual interest rate charged on the loan.
- **Term:** The length of the loan repayment period.
- **Grade:** A letter grade assigned to the loan based on its risk assessment.
- **Annual Income:** The borrower's annual income.
- **Home Ownership:** Whether the borrower owns, rents, or has a mortgage on their home.
- **Purpose:** The reason for taking the loan (e.g., debt consolidation, home improvement).
- **Loan Status:** Whether the loan was fully paid or charged off (defaulted).

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used
Python libraries used to complete this EDA are:
Pandas,
NumPy,
Matplotlib.Pyplot,
Seaborn.
## Project Work flow

- Importing Libraries.

- Loading the Dataset.

- Explore Dataset.

- Data Cleaning and manipulation.

- Handling Outliers.

- Data Visualization.

## Conclusions
**Univariate Analysis:**

- **Loan Amount:** The majority of loans fall between $5,000 and $15,000, with a mean loan amount of approximately $11,000.

- **Income Distribution:** The annual income distribution is heavily right-skewed with a mean of around $65,000.

- **Interest Rates:** The distribution is bimodal with peaks around 10% and 13%, with the mean rate around 12%.

- **Home Ownership:** Most applicants either rent or have a mortgage.

- **Loan Purpose:** The majority of loans are for debt consolidation.

**Bivariate Analysis:**

- **Income and Interest Rate:** Borrowers with lower income and higher interest rates are more likely to default, indicating a higher risk associated with lending to individuals with limited financial capacity and higher borrowing costs.

- **Home Ownership and Bankruptcies:** Individuals who do not own homes and have a history of bankruptcies exhibit a greater likelihood of default, suggesting that homeownership and past financial behavior are important indicators of creditworthiness.

- **Loan Purpose and Amount:** The purpose of the loan and the loan amount play a significant role in default risk. Small business loans and larger loan amounts tend to be associated with higher default rates, highlighting the need for careful assessment of business viability and borrower repayment capacity.

- **Time and Location:** Loans issued in earlier years (2007-2008) and in certain states (NV, AK, FL) show higher charge-off rates, potentially reflecting the impact of economic conditions and regional variations on loan performance.

**Correlation Analysis:**
Positive correlations were found between loan amount, funded amount, and investor-funded amount.
Interest rate showed a moderate positive correlation with loan amount.
A weak negative correlation was observed between public record bankruptcies and annual income.

The analysis provides valuable insights into the factors affecting loan defaults, which can be used by financial institutions to refine their lending criteria and reduce credit loss.

## Acknowledgements

We acknowlege the dataset provider team.

## Contact

https://github.com/abhilashkdeveloper

https://github.com/komal2

https://github.com/KomalAnalyst777

Created by [@abhilashkdeveloper,@komal2,@KomalAnalyst777] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
