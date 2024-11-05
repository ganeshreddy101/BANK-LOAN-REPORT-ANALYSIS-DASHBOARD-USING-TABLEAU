# BANK LOAN REPORT ANALYSIS USING TABLEAU


In this project, I developed a comprehensive Bank Loan Report using Tableau Public, structured across three distinct dashboards—Summary, Overview, and Details. Each dashboard serves a specific purpose in analyzing and visualizing key loan-related metrics, enabling data-driven decision-making and performance monitoring.
## Summary Dashboard

**Purpose:**  
This dashboard provides a comprehensive overview of the bank's loan performance by leveraging key performance indicators (KPIs). The main objective is to track and analyze various aspects of the bank's loan portfolio over time.

**Details:**  
- **Key Performance Indicators (KPIs):**
  - **Total Loan Applications:** The total number of loan applications received.
  - **Total Funded Amount:** The total amount of money disbursed for loans.
  - **Total Amount Received:** The total amount of money collected from loan repayments.
  - **Average Interest Rate:** The average interest rate applied to the loans.
  - **Debt-to-Income Ratio (DTI):** A metric that assesses the borrower’s ability to manage monthly debt payments and repay loans.

- **Performance Segmentation:**
  - **Month-to-Date (MTD):** The KPIs are segmented by Month-to-Date metrics, allowing for real-time tracking of the bank's loan performance.
  - **Month-over-Month (MoM):** The dashboard includes Month-over-Month comparisons to analyze trends and changes in performance over time.

- **Loan Categorization:**
  - **Good Loans:** Loans that are either fully paid or current, reflecting positive loan quality.
  - **Bad Loans:** Loans that have been charged off, indicating potential losses and areas for improvement in loan quality.

This dashboard serves as a valuable tool for evaluating the bank's loan performance, identifying trends, and making informed decisions to optimize financial outcomes.


![alttext](https://github.com/Saichandu19/BANK-LOAN-REPORT-ANALYSIS-DASHBOARD-USING-TABLEAU/blob/main/SUMMARY_DASHBOARD.png?raw=true)

# Bank Loan Report Analysis

## 1. Total Loan Applications
- **Total**: 38.6k (Good: 33.2k, Bad: 5.3k)
- **Month-to-Date**: 4,314
- **Previous Month-to-Date**: 4,035
- **Possible Reasons**:
  - The increase in loan applications from 4,035 to 4,314 month-to-date suggests a growing interest in loans or an increase in marketing efforts.
  - A large portion of applications is categorized as 'Good,' indicating a strong portfolio quality. The 'Bad' loans make up a smaller percentage, which is positive for the bank's risk management.

## 2. Total Funded Amount
- **Total**: $435.8 million (Good: $370.2 million, Bad: $65.5 million)
- **Total Amount Received**: $473.1 million (Good: $370.2 million, Bad: $65.5 million)
- **Possible Reasons**:
  - The funded amount and received amount are closely aligned, suggesting effective loan disbursement and repayment processes.
  - The significant difference between 'Good' and 'Bad' funded amounts shows that most of the funds are being disbursed to higher-quality loans, which could imply prudent lending practices.

## 3. Average Interest Rate
- **Rate**: 12%
- **Possible Reasons**:
  - This average rate reflects the overall cost of borrowing for the bank's loan portfolio. If the rate is relatively high, it could be a strategy to compensate for the risk associated with lending or to cover operational costs.

## 4. Average Debt-to-Income Ratio
- **Ratio**: 13.3%
- **Possible Reasons**:
  - A lower average DTI ratio indicates that borrowers are relatively less leveraged, which reduces the risk for the bank and suggests that the borrowers are in a good financial position to manage their loans.

## 5. Regional Analysis
- **Most Applications from California**: 6,894
- **Possible Reasons**:
  - California’s high number of applications could be due to its large population, economic activity, or targeted marketing efforts in that state. This indicates a potential focus area for expansion or increased marketing.

## 6. Trends Over Time
- **Observation**: Increase from January to December
- **Possible Reasons**:
  - The steady increase in applications throughout the year might be related to seasonal factors, changing economic conditions, or year-end financial planning by borrowers.

## 7. Loan Application by Employee Length
- **More for 10+ Years of Experience**
- **Possible Reasons**:
  - Borrowers with longer employment history may be perceived as more stable and reliable, leading to a higher number of applications from this group. This reflects a preference or better qualification among more experienced employees.

## 8. Loan Purpose Breakdown
- **Majority for Debt Consolidation**: 18.2k
- **Possible Reasons**:
  - The high number of applications for debt consolidation suggests borrowers are seeking to manage or reduce existing debt, possibly due to financial strain or high interest rates on current debts.

## 9. Home Ownership Analysis
- **Rent Type and Mortgage Type Almost Equal**
- **Possible Reasons**:
  - The near-equal distribution between renters and those with mortgages suggests a balanced approach to lending across different home ownership statuses, indicating the bank's inclusive lending strategy.

## 10. Loan Term Analysis
- **60 Months**: 73.2%
- **30 Months**: 26.8%
- **Possible Reasons**:
  - A higher percentage of long-term loans (60 months) indicates borrowers may prefer extended repayment periods for lower monthly payments. This could also reflect favorable terms or financial planning preferences.

## 11. Filters Used
- **Verification Status**: Ensures data reliability and accuracy in assessing borrower credibility.
- **Purpose**: Helps segment loans based on borrower intentions, allowing for customized loan offerings.
- **Grade**: Provides a risk classification to manage and assess the risk associated with loans.


  ![alttext](https://github.com/Saichandu19/BANK-LOAN-REPORT-ANALYSIS-DASHBOARD-USING-TABLEAU/blob/main/OVERVIEW_DASHBOARD.png?raw=true)



## Overview Dashboard

**Purpose:**  
The Overview Dashboard visually represents critical loan metrics and trends using a variety of chart types, providing a detailed look at lending activities from multiple angles.

**Key Charts:**

- **Monthly Trends by Issue Date (Line Chart):**
  - **Details:** This line chart tracks Total Loan Applications, Total Funded Amount, and Total Amount Received over time, with the X-axis representing months and the Y-axis showing metric values.
  - **Insights:** It reveals seasonal patterns and long-term trends, allowing the bank to understand fluctuations in lending activity and adjust strategies accordingly.

- **Regional Analysis by State (Filled Map):**
  - **Details:** This map is color-coded by state, showing lending metrics like Total Loan Applications, Total Funded Amount, and Total Amount Received across different regions.
  - **Insights:** It highlights regional disparities, helping the bank identify high-performing areas and potential markets for expansion.

- **Loan Term Analysis (Donut Chart):**
  - **Details:** The donut chart segments loans by term length (e.g., 36 months, 60 months), with each segment representing the proportion of Total Loan Applications, Total Funded Amount, and Total Amount Received.
  - **Insights:** This chart provides insights into borrower preferences for loan terms, which can inform the bank’s product offerings.

- **Employee Length Analysis (Bar Chart):**
  - **Details:** This bar chart displays lending metrics based on borrowers' employment length categories, such as 1 year, 5 years, and 10+ years.
  - **Insights:** It helps the bank understand how employment stability influences loan applications and repayments.

- **Loan Purpose Breakdown (Bar Chart):**
  - **Details:** The bar chart categorizes loans by their stated purposes, such as debt consolidation or credit card refinancing.
  - **Insights:** It shows the primary reasons borrowers seek loans, aiding in targeted marketing and product development.

- **Home Ownership Analysis (Tree Map):**
  - **Details:** This tree map categorizes loans by home ownership status (e.g., own, rent, mortgage), with each segment’s size reflecting lending metrics.
  - **Insights:** It helps in understanding the relationship between home ownership and borrowing behavior, which can be useful for risk assessment and product segmentation.


![alttext](https://github.com/Saichandu19/BANK-LOAN-REPORT-ANALYSIS-DASHBOARD-USING-TABLEAU/blob/main/DETAILS_DASHBOARD.png?raw=true)


## Details Dashboard

**Purpose:**  
The Details Dashboard serves as a comprehensive view of all essential loan data, allowing users to access critical information efficiently.

**Details:**  
- It includes a grid view categorized by loan status, showing metrics such as:
  - **Total Loan Applications**
  - **Funded Amounts**
  - **Amounts Received**
  - **Month-to-Date (MTD) metrics**
  - **Average Interest Rates**
  - **Debt-to-Income Ratios**

- This dashboard provides an in-depth analysis of the bank's loan portfolio, helping users drill down into specific aspects of loan performance.



