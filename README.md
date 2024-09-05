# Financial_Loan_data_Management

## Table of contents 
- [INTRODUCTION](#INTRODUCTION)
- [PROBLEM STATEMENT](#PROBLEM-STATEMENT)
- [DATA SOURCE](#DATA-SOURCE)
- [TOOLS USED](#TOOLS-USED)
- [DATA ANALYSIS](#DATA-ANALYSIS)
- [IMAGE](#IMAGE)
- [RESULT](#RESULT)
- [RECOMMENDATIONS](#RECOMMENDATIONS)
### INTRODUCTION
This is a financial system that provides loan to it's customers and based on the type of loan needed it determines the interest rate to be paid by the customer.
### PROBLEM STATEMENT
- Fetch customers with the same loan amount.
- Find the second highest loan amount and the customer and branch associated with it.
- Get the maximum loan amount per branch and the customer name.
### DATA SOURCE
Financial institution
### TOOLS USED
- SSMS
- PROBLEM SOLVING SKILL
### DATA ANALYSIS
- To fetch customers with same loan filtering of the data was done using "GROUP BY and HAVING clause". 
-	To obtain the second highest loan amount, combinations of many data such as the customer data,state and branch data was used to obtain the desired result.
-	To obtain the maximun loan amount per branch ,Joining of different data also needed.
### IMAGE
 ![FINANCIAL_PORT](https://github.com/user-attachments/assets/3cc8c4cd-b973-4caa-8ab4-028c895d1886)

### RESULT
-	From the analysis it shows that none has the same loan amount even though they belong to same loan category.
-	The analysis shows that 'dave williams' has the second highest loan amount of 8,500 with location at Delta
-	Maximun loan amount differs per branch,customers from 'auto loan and business loan' do have the maximun loan amount for their department.
### RECOMMENDATIONS
-	Revisitation of interest rate so as to encourage more customers to obtain loan.
-	Creation of more branch and locations.

