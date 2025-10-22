# TASK PROMPT: YearEnd Business Report Preparation

# OVERVIEW
You are acting as a **Tax Accountant Assistant** responsible for reviewing Quicken data and preparing comprehensive financial reports for four Canadian corporations. Your deliverables will be used by professional tax accountants to complete T2 corporate tax returns and personal tax filings.

---

# STANDARD REPORT PACKAGE (Per Corporation)
Each corporation requires the following reports to be generated:

## 1\. INCOME & EXPENSE REPORTS
* ✓ YExx \- \[Corp Name\] Inc & Exp CAD (Main P\&L in Canadian Dollars)  
* ✓ YExx \- \[Corp Name\] Inc & Exp USD (P\&L in US Dollars \- if applicable)  
* ✓ Check \- \[Corp Name\] Inc & Exp Comparison Check (Year-over-year comparison)

## 2\. BANK STATEMENT REPORTS
* ✓ YExx \- \[Corp Name\] Bank Stmt \[Bank\] Bus \[\#\#\#\#\] CAD (CAD operating account)  
* ✓ YExx \- \[Corp Name\] Bank Stmt \[Bank\]  Bus \[\#\#\#\#\] USD (USD operating account \- if applicable)

#### 3\. TRANSFER REPORTS
* ✓ YExx \- \[Corp Name\] Transfers CAD (All CAD inter-account transfers)  
* ✓ YExx \- \[Corp Name\] Transfers USD (All USD inter-account transfers \- if applicable, often "-none")

#### 4\. INVESTMENT REPORTS (If corporation holds investments)
* ✓ YExx \- \[Corp Name\] Invmt Inc CAD (Investment income in CAD)  
* ✓ YExx \- \[Corp Name\] Invmt Inc USD (Investment income in USD)  
* ✓ YExx \- \[Corp Name\] Invmt Transactions CAD (All investment transactions in CAD)  
* ✓ YExx \- \[Corp Name\] Invmt Transactions USD (All investment transactions in USD)  
* ✓ YExx \- \[Corp Name\] Invmt CapGains CAD (Capital gains/losses in CAD)  
* ✓ YExx \- \[Corp Name\] Invmt CapGains USD (Capital gains/losses in USD \- often "-none")

#### 5\. SHAREHOLDER LOAN REPORT
* ✓ YExx \- \[Corp Name\] Shareholder Loan (Tracks shareholder loan account balance)

#### 6\. CONSOLIDATED REPORTS
* ✓ YExx \- T1135 Foreign Investments \- All Corps (Consolidated foreign property reporting)

*Notes*

1) **Empty Reports** : If the quicken generated reports filename ends in ‘-none’, then it means there should be no transactions from the ALL Transactions file.  
   

---

## ACCOUNT LIST
Refer to the ‘quicken account list 2025-10-18.csv’ document for a list of all Quicken Accounts.

# TASK AREA STRUCTURE
The year-end process is organized into **7 Task Areas**, each with a standardized structure:

- 

## The 7 Task Areas:

1. **Initial Data Preparation and Reconciliation** \- Ensure all raw financial data is accurately imported, updated, and reconciled  
2. **Income and Expense Categorization Review** \- Ensure all transactions are correctly categorized for tax purposes  
3. **Shared Expense Calculation and Allocation** \- Accurately calculate and allocate shared operational expenses among companies  
4. **Inter-Company Transactions and Shareholder Loans** \- Verify and document all transfers between entities and shareholder loan activity  
5. **Investment Portfolio Review and Compliance** \- Verify investment income, capital gains/losses, and T1135 compliance  
6. **Report Generation and Quality Control** \- Generate all required financial reports in standardized format  
7. **Final Documentation and Package Preparation** \- Compile all supporting documentation for external tax accountants

---

## DETAILED TASK AREA SPECIFICATIONS

### **TASK AREA 1: Initial Data Preparation and Reconciliation**

#### **Objective:** Ensure all raw financial data is accurately imported, updated, and reconciled.

#### **Activities**
1. **Bank Balance Comparison** : Compare the bank statements with Quicken reports to ensure that the start and end balances on each statement matches the balances in the quicken reports.

2. **Check Recurring Tasks**: Review transactions in the Inc\&Exp reports to identify if any recurring transactions are missing months.  E.g. utility bills,   
     
3. **Incorrect Account**: Review the reports to identify any transactions that look like they come from the wrong account.  E.g.  An expense item in the MB MedCorp report shows it came from the ON MedCorp bank account.  
     
4. **Identify Missing Transactions**:  For each report review the previous two years reports to identify if any common transactions are missing.  


#### **Deliverables**
5. Validated transaction summary per company  
6. Bank reconciliation summary  
7. List of outstanding/unreconciled transactions

#### **Quality Checks**
8. All bank accounts balance to statements within tolerance  
9. No missing gaps of transaction data  
10. All accounts show "reconciled" status in Quicken
