# Project Name
> Lending club case study - Loan Default Analysis


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- What is the background of your project?
This project focuses on analyzing a loan dataset to identify the factors that contribute to loan defaults. The objective is to pinpoint key indicators that can assist lenders in assessing credit risk, making informed lending decisions, and gaining insights to reduce credit losses. The analysis examines various variables, including loan amounts, interest rates, borrower income, and credit history, to predict the likelihood of a borrower defaulting on a loan.

- What is the business probem that your project is trying to solve?
The project aims to tackle the issue of minimizing financial losses caused by loan defaults. By identifying high-risk borrowers and understanding the factors linked to defaults, lenders can devise strategies to manage risks and enhance the performance of their loan portfolios.

- What is the dataset that is being used?
The dataset used in this analysis includes information on thousands of loans, covering borrower demographics, loan characteristics, and repayment status. Key attributes in the dataset include:
  - **Loan Amount:** The principal amount borrowed.
  - **Interest Rate:** The annual interest rate applied to the loan.
  - **Term:** The duration of the loan repayment period.
  - **Grade:** A letter grade assigned to the loan based on its risk assessment.
  - **Annual Income:** The borrower’s annual income.
  - **Home Ownership:** The borrower’s homeownership status (own, rent, mortgage).
  - **Purpose:** The reason for taking out the loan (e.g., debt consolidation, home improvement).
  - **Loan Status:** The outcome of the loan (e.g., fully paid, charged off/defaulted).


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
**Univariate Analysis:**
- **Loan Amount:** Most loans range between $5,000 and $15,000, with an average loan amount of approximately $11,000.
- **Income Distribution:** The distribution of annual income is heavily right-skewed, with an average income around $65,000.
- **Interest Rates:** The interest rate distribution is bimodal, with peaks around 10% and 13%, and an average rate of about 12%.
- **Home Ownership:** The majority of applicants either rent or have a mortgage.
- **Loan Purpose:** Most loans are taken out for debt consolidation.

**Bivariate Analysis:**
- **Income and Interest Rate:** Borrowers with lower incomes and higher interest rates are more likely to default, indicating a higher risk associated with lending to individuals with limited financial capacity and higher borrowing costs.
- **Home Ownership and Bankruptcies:** Borrowers who do not own homes and have a history of bankruptcies are more prone to default, suggesting that homeownership and past financial behavior are key indicators of creditworthiness.
- **Loan Purpose and Amount:** The purpose and amount of the loan significantly influence default risk. Small business loans and larger loan amounts are more likely to default, underscoring the importance of assessing business viability and the borrower’s repayment capacity.
- **Time and Location:** Loans issued during earlier years (2007-2008) and in certain states (e.g., NV, AK, FL) have higher charge-off rates, possibly reflecting the influence of economic conditions and regional differences on loan performance.

**Correlation Analysis**
- Positive correlations were observed between loan amount, funded amount, and investor-funded amount.
- Interest rates showed a moderate positive correlation with loan amount.
- A weak negative correlation was found between public record bankruptcies and annual income.

## Technologies Used
Python libraries used to complete this EDA:
Pandas
NumPy
Matplotlib.Pyplot
Seaborn


## Project Work flow
Importing Libraries.
Loading the Dataset.
Explore Dataset.
Data Cleaning and manipulation.
Handling Outliers.
Data Visualization.


**Conclusion**
This analysis offers critical insights into the factors influencing loan defaults, which financial institutions can leverage to improve their lending criteria and minimize credit losses.


## Acknowledgements

## Contact
Created by [@[blizwing](https://github.com/blizwing), @[pravingaikar](https://github.com/pravingaikar)] - feel free to contact me!
