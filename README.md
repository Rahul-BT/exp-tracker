# exp-tracker
This is for my expenses analysis project where I look at my expense data for meaningful insights.

### Expense_Analysis.ipynb

This notebook has the analysis of my spending. The data for this notebook is made from my personal expenses using Expense Manager app. I recorded almost all my expense transactions to manage my finances and also for this project. I used the entire data for analysis but since the data has personal information about my finances, I am reducing the no of observations to 500 in the csv file uploaded here.

### Motivation

I made this notebook to get a better understanding of python for Data Science. I was auditing the course "Introduction to Data Science in Python" and I wanted to test the skills that I learnt in the course. Since I was already tracking my expenses, I started this project with learning as the main goal. 

### Dataset

The dataset **expense_tracker.csv** has 500 entries and 17 columns. The uploaded file is the smaller version of the original file since the data is personal. 
This file has data recorded for almost all my expenses for the period 2017 to 2020. There are a total of 500 entries and 17 columns.

**Column Information**

* Date: The date when the expense/income occured.
* Amount: The amount of the transaction. Income is '+' and Expense is '-'.
* Category: The transaction is categorized into 17 categories based on the nature of the transaction.
* Subcategory: The transaction is categorized into 49 subcategories based on the nature of the transaction.
* Payment method: The type of payment used to complete the transaction
* Description: Description of the transaction, if any
* Ref/Check no: Not used
* Status: Cleared/Uncleared, this is for credit card transactions I did not use this.
* Receipt Nature: Not Used.
* Account: "Personal Expense" is the type used for all.
* Tag: Tags used (most NaN) -> Vacation, Sports, Masters, Loans
* Tax: Not Used
* Quantity: By default, 1 PCS but Not Used.
* Split Total: Not Used.
* Row Id: Not Used. This Id is created automatically by the app.


* Type Id: Not Used.
