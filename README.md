# BANKRUPTCY_PREDICTION
# Problem Statement
The goal of this machine learning project is to develop a predictive model that can assess the financial health of companies and predict the likelihood of bankruptcy based on various financial attributes. The dataset contains a wide range of financial indicators for different companies, including profitability ratios, liquidity ratios, leverage ratios, and operational efficiency metrics. The prediction of bankruptcy is a phenomenon of increasing interest in firms that stand to lose money because of unpaid debts.
# Goal & Objectives
You need to use machine learning algorithms, and aim to analyze these financial attributes and build a predictive model that can classify companies as either financially healthy or at risk of bankruptcy. By leveraging historical financial data and company performance metrics, this model will help investors, financial analysts, and stakeholders identify early warning signs of financial distress and make informed decisions to mitigate risks.
# Data Dictionary
ROA(C) %before interest and depreciation after-tax: Return On Total Assets(C)  
ROA(A) % before interest and depreciation after-tax: Return On Total Assets(A)
ROA(B) % before interest and depreciation after tax: Return On Total Assets(B)
Operating Gross Margin: Gross Profit/Net Sales
Realized Sales Gross Margin: Realized Gross Profit/Net Sales
Operating Profit Rate: Operating Income/Net Sales
Pre-tax net Interest Rate: Pre-Tax Income/Net Sales 
After-tax net Interest Rate: Net income/Net Sales
Non-industry Income and expenditure/revenue: Net Non-operating Income Ratio
Continuous interest rate (after tax): Net Income-Exclude Disposal Gain or Loss/Net Sales
Operating Expense Rate: Operating Expenses/Net Sales
Research and development expense rate: (Research and Development Expenses)/Net Sales
Cash flow rate Cash Flow from Operating/Current Liabilities
Interest-bearing debt interest rate: Interest-bearing Debt/Equity
Tax rate (A): Effective Tax Rate
16. Net Value Per Share (B): Book Value Per Share(B)
Net Value Per Share (A): Book Value Per Share(A)
Net Value Per Share (C): Book Value Per Share(C)
Persistent EPS(Earning Per share) in the Last Four quarters : EPS-Net Income
Cash Flow (Movement of money in and out)Per Share
Revenue Per Share (Euro): Sales Per Share
Operating Profit Per Share (Euro): Operating Income Per Share 
Per Share Net profit before tax (Euro): Pretax Income Per Share
Realized Sales Gross Profit Growth Rate (%)
Operating Profit Growth Rate: Operating Income Growth(%)
After-tax Net Profit Growth Rate: Net Income Growth.(%)
Regular Net Profit Growth Rate: Continuing Operating Income after Tax Growth(%)
Continuous Net Profit Growth Rate(%): Net Income-Excluding Disposal Gain or Loss Growth
Total Asset Growth Rate(%). Total Asset Growth
Net Value Growth Rate(%): Total Equity Growth 
Total Asset Return Growth Rate Ratio%: Return on Total Asset Growth
Cash Reinvestment %: Cash Reinvestment Ratio(is a valuation ratio used to measure the  percentage of annual cash flow that the company invests back into the business as a new investment.)
Current Ratio- CAssest/CLiabilities(a liquidity ratio that measures a company's ability to pay short-term obligations or those due within one year.)(>1.5 is a good ratio)
Quick Ratio: Acid Test (CAssets-Inventory/CLiabilities)
Interest Expense Ratio: Interest Expenses/Total Revenue
Total debt/Total net worth: Total Liability/Equity Ratio
Debt ratio %: Liability/Total Assets
Net worth/Assets: Equity/Total Assets
Long-term fund suitability ratio (A): (Long-term Liability+ Equity)/Fixed Assets
Borrowing dependency. Cost of Interest-bearing Debt
Contingent liabilities/Net worth: Contingent Liability/Equity (Loss may be in the future due to the current situation
Operating profit/Paid-in capital: Operating Income/Capital 

Net profit before tax/Paid-in capital: Pretax Income/Capital (profit obtained by the current core operations)
Inventory and accounts receivable/Net value: (Inventory Accounts Receivables)/Equity- (Inventory consists of the products you sell to customers. Receivables, or accounts receivable, are the outstanding balances you have yet to collect for sales made on credit.)
Total Asset Turnover. how effectively banks are using their assets to generate sales.
Accounts Receivable Turnover
Average Collection Days: Days Receivable Outstanding
Inventory Turnover Rate (times) -Cost of Goods Sold (COGS) / Average Inventory
Fixed Assets Turnover Frequency-Revenue / Average Fixed Assets
Net Worth Turnover Rate (times): Equity Turnover -Revenue / Average Shareholders' Equity
Revenue per person: Sales Per Employee-Total Revenue / Number of Employees
Operating profit per person: Operation Income Per Employee-Operating Income / Number of Employees
Allocation rate per person: Fixed Assets Per Employee–Total Fixed Assets / Number of Employees
Working Capital to Total Assets-Working Capital / Total Assets
Quick Assets/Total Assets - assets that can be quickly converted into cash, relative to its total assets.
Current Assets/Total Assets-assets expected to be converted into cash or used up within one year.
Cash/Total Assets-This ratio measures the proportion of a company's total assets that are held in the form of cash.
Quick Assets/Current Liability-This ratio measures the company's ability to cover its current liabilities using its quick assets.
Cash/Current Liability-This ratio measures the company's ability to cover its current liabilities using its cash reserves.
Current Liability to Assets-This ratio measures the proportion of a company's total assets that are financed by its current liabilities
Operating Funds to Liability-This ratio measures the company's operating funds relative to its total liabilities.
Inventory/Working Capital-This ratio measures the proportion of a company's working capital that is tied up in inventory.
Inventory/Current Liability-This ratio measures the proportion of a company's current liabilities that are covered by its inventory.
Current Liabilities/Liability-This ratio measures the proportion of a company's total liabilities that are classified as current liabilities.
Working Capital/Equity-This ratio measures the proportion of a company's equity that is represented by its working capital.
Current Liabilities/Equity-This ratio measures the proportion of a company's equity that is represented by its current liabilities.
Long-term Liability to Current Assets-This ratio measures the proportion of a company's current assets that are financed by its long-term liabilities.
Retained Earnings to Total Assets-This ratio measures the proportion of a company's total assets that are financed by its retained earnings.
Total income/Total expense-This ratio, often referred to as the income-to-expense ratio, measures the relationship between total income and total expenses
Total expense/Assets-This ratio measures the proportion of a company's assets that are used to cover its total expenses.
Current Asset Turnover Rate: Current Assets to Sales-This ratio measures how efficiently a company uses its current assets to generate sales revenue.
Quick Asset Turnover Rate: Quick Assets to Sales-This ratio measures how efficiently a company uses its quick assets to generate sales revenue
Working Capital Turnover Rate: Working Capital to Sales -This ratio measures how efficiently a company uses its working capital to generate sales revenue.
Cash Turnover Rate: Cash to Sales-This ratio measures how efficiently a company uses its cash to generate sales revenue.
Cash Flow to Sales-This ratio measures the proportion of sales revenue that is converted into cash flow.
Fixed Assets to Assets-This ratio measures the proportion of a company's total assets that are represented by fixed assets.
Current Liability to Liability-This ratio measures the proportion of a company's total liabilities that are classified as current liabilities.
Current Liability to Equity-This ratio measures the proportion of a company's equity that is represented by its current liabilities
Equity to Long-term Liability-This ratio measures the proportion of a company's long-term liabilities that are covered by its equity.
Cash Flow to Total Assets-This ratio measures the proportion of a company's total assets that are generated as cash flow.
Cash Flow to Liability-This ratio measures the proportion of a company's total liabilities that are covered by its cash flow.
CFO to Assets (calculated by dividing cash flows from operations by the average total assets.)-This ratio measures the efficiency of a company in generating cash flows from its operations relative to its total assets.
Cash Flow to Equity (Free cash flow to equity is composed of net income, capital expenditures, working capital, and debt)-This ratio, specifically Free Cash Flow to Equity (FCFE), measures the cash flow available to the equity holders of the company after accounting for all expenses, reinvestments, and debt obligations.
Current Liability to Current Assets-This ratio measures the proportion of a company's current assets that are financed by its current liabilities.
Liability-Assets Flag: 1 if Total Liability exceeds Total Assets, otherwise 0
Net Income to Total Assets
Total assets to GNP price ratio- Gross National Product(GNP is an economic indicator that measures the size and health of a country's economy.)
No-credit interval
Gross Profit to Sales
Net Income to Stockholder's Equity ratio
Liability to Equity ratio-This ratio measures the proportion of a company's total liabilities to its shareholders' equity.
Degree of Financial Leverage (DFL) ratio(It shows how much a percentage change in EBIT will result in a percentage change in EPS.)-DFL is an important metric for investors and analysts to assess a company's financial risk and understand how changes in operating performance can affect its profitability.
IInterest Coverage Ratio (Interest expense to EBIT)-The Interest Coverage Ratio measures the company's ability to meet its interest obligations on outstanding debt.
Equity to Liability.The Equity to Liability Ratio, also known as the Equity Ratio, measures the proportion of a company's total assets that are financed by its shareholders' equity.
# Bankrupt Class label 1: Yes, 0: No – Target Column

# Data Structure
No_of_columns – 92 Nos
No_of_Rows – 6819 Nos

# Applying Models
1) RandomForest
2) XGBoost
3) LogisticRegression
4) DECISION_TREE_MODEL










