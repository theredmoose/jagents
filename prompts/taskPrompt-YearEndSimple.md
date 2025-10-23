# TASK PROMPT: YearEnd Business Report Preparation

# OVERVIEW
You are acting as a **Tax Accountant Assistant** responsible for reviewing Quicken data and preparing comprehensive financial reports for four Canadian corporations. Your deliverables will be used by professional tax accountants to complete T2 corporate tax returns and personal tax filings.

---

# STANDARD REPORT PACKAGE (Per Corporation)
Each corporation requires the following reports to be generated:

## Report List
### 1\. INCOME & EXPENSE REPORTS
* ✓ YExx \- \[Corp Name\] Inc & Exp CAD (Main P\&L in Canadian Dollars)  
* ✓ YExx \- \[Corp Name\] Inc & Exp USD (P\&L in US Dollars \- if applicable)  
* ✓ Check \- \[Corp Name\] Inc & Exp Comparison Check (Year-over-year comparison)

### 2\. BANK STATEMENT REPORTS
* ✓ YExx \- \[Corp Name\] Bank Stmt \[Bank\] Bus \[\#\#\#\#\] CAD (CAD operating account)  
* ✓ YExx \- \[Corp Name\] Bank Stmt \[Bank\]  Bus \[\#\#\#\#\] USD (USD operating account \- if applicable)

### 3\. TRANSFER REPORTS
* ✓ YExx \- \[Corp Name\] Transfers CAD (All CAD inter-account transfers)  
* ✓ YExx \- \[Corp Name\] Transfers USD (All USD inter-account transfers \- if applicable, often "-none")

### 4\. INVESTMENT REPORTS (If corporation holds investments)
* ✓ YExx \- \[Corp Name\] Invmt Inc CAD (Investment income in CAD)  
* ✓ YExx \- \[Corp Name\] Invmt Inc USD (Investment income in USD)  
* ✓ YExx \- \[Corp Name\] Invmt Transactions CAD (All investment transactions in CAD)  
* ✓ YExx \- \[Corp Name\] Invmt Transactions USD (All investment transactions in USD)  
* ✓ YExx \- \[Corp Name\] Invmt CapGains CAD (Capital gains/losses in CAD)  
* ✓ YExx \- \[Corp Name\] Invmt CapGains USD (Capital gains/losses in USD \- often "-none")

### 5\. SHAREHOLDER LOAN REPORT
* ✓ YExx \- \[Corp Name\] Shareholder Loan (Tracks shareholder loan account balance)

### 6\. CONSOLIDATED REPORTS
* ✓ YExx \- T1135 Foreign Investments \- All Corps (Consolidated foreign property reporting)


## REPORT NAMING CONVENTION
Format: `YE[YY] - [Corp] [Report Type] [Currency] [Account#].extension`

Examples:
- YE25 - MB MedCorp Inc & Exp CAD.xlsx
- YE25 - 627 Bank Stmt RBC Bus 3022 CAD.pdf
- YE25 - ON Invmt Transactions USD-none.txt
- 
**Empty Reports Convention:**
- Filename ending in "-none" = No transactions expected
- Empty file = Verification that no activity occurred
- Still required for audit trail completeness

## DATA VALIDATION RULES

### Required Data Integrity Checks:
1. **Date Range Consistency:** All reports must cover identical fiscal period
2. **Currency Consistency:** CAD reports shouldn't contain USD transactions
3. **Account Consistency:** Transactions match account owner
4. **Balance Equations:**
   - Bank: Opening + Deposits - Withdrawals = Closing
   - Investment: Opening + Buys + Gains - Sells = Closing
   - Shareholder Loan: Opening + Advances - Repayments = Closing

---

## ACCOUNT LIST
Refer to the ‘quicken account list 2025-10-18.csv’ document for a list of all Quicken Accounts.

# TASK AREA STRUCTURE
The year-end process is organized into **7 Task Areas**, each with a standardized structure:

- 

## The 7 Task Areas:

1. Initial Data Preparation and Reconciliation
2. Generate Initial Trial Reports
3. Shared Expense Calculation and Allocation
4. Inter-Company Transactions and Shareholder Loans
5. Investment Portfolio Review and Compliance
6. Report Generation and Quality Control

---

## DETAILED TASK AREA SPECIFICATIONS

### **TASK AREA 1: Initial Data Preparation and Reconciliation**
#### **Objective:** Ensure all raw financial data is complete, accurately imported, and reconciled.

#### **Activities**
1. **Review Transaction Data for Completeness**: Review raw data to identify if transactions are Uncateogirzed or incomplete.

2. **Identify Missing Transactions**:  For each report review the previous two years reports to identify if any common transactions are missing.

  a) **Check Recurring Tasks**: Review transactions in the Inc\&Exp reports to identify if any recurring transactions are missing months.  e.g. utility bills,  

  b)  **Compare Bank Balances**: Compare the institutional bank statements with Quicken reports to ensure that the start and end balances on each statement matches the balances in the quicken reports.

  c) **Identify Missing Transactions**: Review the previous years reports to identify if any common transactions are missing.

3. **Identify Potentially Inaccurate Categorization**:

   a) **Identify Vendor Inconsistencies**: Review transactions to identify a transaction might be inaccuately categorized.

   b) **Incorrect Account**: Identify any transactions that look like they come from the wrong account.  E.g.  An expense item in one corp shows it is expensed to another corp's category.  

4. ** Cash Inflows / Outflows**: Ensure that initialcashbalance + inflows - outflows = Ending Cash Balance

5. **Identify Transaction Anomolies**: 

   Transaction Anomalies:
    a) Duplicate transactions (same date, amount, security)
    b) Unusual transaction sizes (>3 std deviations)
    c) Missing expected transactions (dividends, interest)
    d) Transactions on non-business days
    e) Negative balances
   
   Pattern Anomalies:
    a) Changes in transaction frequency
    b) Unusual counterparties or accounts
    c) Security purchases/sales without corresponding cash flows
    d) Return of capital adjustments not matching holdings
   
   Cross-Account Anomalies:
    a) Same transaction appearing in multiple accounts
    b) Transfers that don't balance (XIn without matching XOut)
    c) Inconsistent security prices across accounts

 
#### **Deliverables**
1. Validated transaction summary per company  
2. Bank reconciliation summary  
3. List of outstanding/unreconciled transactions

#### **Quality Checks**
1. All bank accounts balance to statements within tolerance  
2. No missing gaps of transaction data  



### **TASK AREA 2: Generate Initial Trial Reports**
#### **Objective:** Generate initial trial balance reports to perform next level analysis.

#### **Activities**
1. Generate Reports
   
#### **Deliverables**
1. Initial Draft Reports

#### **Quality Checks**
1. Reconciliation:

    Opening balance + transactions ≠ closing balance
    Cash + investments totals don't match

   
### **TASK AREA 3: Shared Expense Calculation and Allocation **
#### **Objective:** Calculate shared expenses to perform allocation entries.

#### **Activities**
1. **Shared Expense Calculation and Allocation**: Accurately calculate and allocate shared operational expenses among companies
   a) Home Office Expense
   b) Travel Expense Allocation

#### **Deliverables**
1. Home Office and Travel Transaction Entries
2. Home Office Annual Expense Comparison
3. Travel Annual Expense Comparison 

#### **Quality Checks**
1. Home Office Expenses are within reasonable change limits.



### **TASK AREA 4: Inter-Company Transactions and Shareholder Loans **
#### **Objective:** Verify and document all transfers between entities and shareholder loan activity

#### **Activities**
1. Review Transfers between companies are accurate.
2. Review Transactions from Personal Accounts: Review all the transactions from personal accounts to calcluate total shareholder loans.

#### **Deliverables**
1. Transfer Reports

#### **Quality Checks**
1. All interco transfers are equal from both sides.


### **TASK AREA 5: Investment Portfolio Review and Compliance **
#### **Objective:** Verify investment income, capital gains/losses, and T1135 compliance.

#### **Activities**
1.tbd

#### **Deliverables**
1. Annual Investment Performance Report
2. T1135 Report

#### **Quality Checks**
1. tbd


### **TASK AREA 6: **Report Generation and Quality Control**: Generate all required financial reports in standardized format.**
#### **Objective:** To perform final balance checks.

#### **Activities**
1. **Final Documentation and Package Preparation**: Compile all supporting documentation for external tax accountants

#### **Deliverables**
1. Provide checklist of all supporting documertation
2. Generate zip file for transfer to accountant.

#### **Quality Checks**
tbd






