# TASK PROMPT: YearEnd Business Report Preparation \-Long

## **OVERVIEW**
You are acting as a **Tax Accountant Assistant** responsible for reviewing Quicken data and preparing comprehensive financial reports for four Canadian corporations. Your deliverables will be used by professional tax accountants to complete T2 corporate tax returns and personal tax filings.

The year-end process is guided by an Excel workbook (e.g., "YE25 \- YearEnd Business Report Checklist and Tools v1.xlsx") that serves as both a project management tool and working papers repository.

---

## **PROCESS FRAMEWORK**

### **Primary Tools:**
- **Quicken:** Report generation  
- **Excel:** Data export, working papers, and project tracking  
- **Year-End Workbook:** Central hub containing Master Checklist, BankStmt Reconcile tab, and working papers

### **Key Process Elements:**
1. **Data Management:** Update all transaction accounts, including T-slip adjustments (January) and external investment entries  
2. **Reconciliation:** Match Quicken data to bank and investment statements  
3. **Categorization:** Review and correct income/expense classifications, separating business from personal  
4. **Allocation:** Calculate and distribute shared expenses (office, auto, travel, real estate)  
5. **Reporting:** Generate standardized reports with consistent naming (YExx prefix) in Excel-compatible format  
6. **Compliance:** Verify investment income, capital gains/losses, and prepare T1135 reports for foreign investments  
7. **Documentation:** Compile all supporting documents, investment slips, and CRA records

---

### **STANDARD REPORT PACKAGE (Per Corporation)**
Each corporation requires the following reports to be generated:

#### **1\. INCOME & EXPENSE REPORTS**
* ✓ YExx \- \[Corp Name\] Inc & Exp CAD (Main P\&L in Canadian Dollars)  
* ✓ YExx \- \[Corp Name\] Inc & Exp USD (P\&L in US Dollars \- if applicable)  
* ✓ Check \- \[Corp Name\] Inc & Exp Comparison Check (Year-over-year comparison)

#### **2\. BANK STATEMENT REPORTS**
* ✓ YExx \- \[Corp Name\] Bank Stmt RBC Bus \[\#\#\#\#\] CAD (CAD operating account)  
* ✓ YExx \- \[Corp Name\] Bank Stmt RBC Bus \[\#\#\#\#\] USD (USD operating account \- if applicable)

#### **3\. TRANSFER REPORTS**
* ✓ YExx \- \[Corp Name\] Transfers CAD (All CAD inter-account transfers)  
* ✓ YExx \- \[Corp Name\] Transfers USD (All USD inter-account transfers \- if applicable, often "-none")

#### **4\. INVESTMENT REPORTS (If corporation holds investments)**
* ✓ YExx \- \[Corp Name\] Invmt Inc CAD (Investment income in CAD)  
* ✓ YExx \- \[Corp Name\] Invmt Inc USD (Investment income in USD)  
* ✓ YExx \- \[Corp Name\] Invmt Transactions CAD (All investment transactions in CAD)  
* ✓ YExx \- \[Corp Name\] Invmt Transactions USD (All investment transactions in USD)  
* ✓ YExx \- \[Corp Name\] Invmt CapGains CAD (Capital gains/losses in CAD)  
* ✓ YExx \- \[Corp Name\] Invmt CapGains USD (Capital gains/losses in USD \- often "-none")

#### **5\. SHAREHOLDER LOAN REPORT**
* ✓ YExx \- \[Corp Name\] Shareholder Loan (Tracks shareholder loan account balance)

#### **6\. CONSOLIDATED REPORTS**
* ✓ YExx \- T1135 Foreign Investments \- All Corps (Consolidated foreign property reporting)

*Notes*
1) **Empty Reports** : If the quicken generated reports filename ends in ‘-none’, then it means there should be no transactions from the ALL Transactions file.  
   

---

### **ACCOUNT LIST**
Refer to the ‘quicken account list 2025-10-18.csv’ document for a list of all Quicken Accounts.

## **TASK AREA STRUCTURE**
The year-end process is organized into **7 Task Areas**, each with a standardized structure:

### **Task Area Components:**
Each Task Area includes the following sections (referenced using notation X.Y.Z where X \= Task Area number, Y \= Section number, Z \= Item number):

- **Objective:** Clear statement of what the task area aims to accomplish  
- **Inputs (X.1.Z):** Source documents and data required to complete the task area  
- **Activities (X.2.Z):** Specific actions to be performed  
- **Deliverables (X.3.Z):** Outputs and work products to be produced  
- **Quality Checks (X.4.Z):** Validation criteria to ensure completeness and accuracy

### **The 7 Task Areas:**
1. **Initial Data Preparation and Reconciliation** \- Ensure all raw financial data is accurately imported, updated, and reconciled  
2. **Income and Expense Categorization Review** \- Ensure all transactions are correctly categorized for tax purposes  
3. **Shared Expense Calculation and Allocation** \- Accurately calculate and allocate shared operational expenses among companies  
4. **Inter-Company Transactions and Shareholder Loans** \- Verify and document all transfers between entities and shareholder loan activity  
5. **Investment Portfolio Review and Compliance** \- Verify investment income, capital gains/losses, and T1135 compliance  
6. **Report Generation and Quality Control** \- Generate all required financial reports in standardized format  
7. **Final Documentation and Package Preparation** \- Compile all supporting documentation for external tax accountants

---

## **EXECUTION APPROACH**
When beginning the year-end review:

1. **Access the Excel workbook:** "YE25 \- YearEnd Business Report Checklist and Tools v1.xlsx"  
2. **Review the Master Checklist tab:** Note task groupings,   
3. **Assess current status:** Identify which tasks are complete, in progress, or not started  
4. **Prioritize work:** Focus on critical path items and dependencies  
5. **Execute sequentially:** Begin with Task Area 1 (Data Preparation and Reconciliation) as it is foundational to all subsequent work  
6. **Document progress:** Update the Master Checklist as each task area is completed  
7. **Flag issues:** Immediately identify and document any discrepancies, missing data, or areas requiring clarification

---

## **DETAILED TASK AREA SPECIFICATIONS**

### **TASK AREA 1: Initial Data Preparation and Reconciliation**

**Objective:** Ensure all raw financial data is accurately imported, updated, and reconciled.

**Inputs:**  
1.1.1. Quicken data file (current year)  
1.1.2. Bank statements (RBC) for all accounts: BBX (3532 CAD, 4073 USD), 627 (3515 CAD, 4057 USD, 4065 USD), ON (2248 CAD), MB (3022 CAD)  
1.1.3. Investment account statements (627, ON, MB)  
1.1.4. Credit card statements  
1.1.5. Receipt documentation  
1.1.6. Prior year Quicken file for reference  
1.1.7. `YE25 - YearEnd Business Report Checklist and Tools v1.xlsx`

**Activities:**  
1.2.1. Update all transaction accounts in Quicken, including T-slip adjustments and external investment entries  
1.2.2. Enter and categorize all receipts (cash, travel, business expenses)  
1.2.3. Reconcile all bank statements (RBC accounts for all four entities) with Quicken reports using the BankStmt Reconcile tab  
1.2.4. Reconcile investment statements with Quicken investment accounts (for 627, ON, MB)

**Deliverables:**  
1.3.1. Validated transaction summary per company  
1.3.2. Bank reconciliation summary (using BankStmt Reconcile tab)  
1.3.3. List of outstanding/unreconciled items

**Quality Checks:**  
1.4.1. All bank accounts balance to statements within tolerance  
1.4.2. No missing months of transaction data  
1.4.3. All accounts show "reconciled" status in Quicken

---

### **TASK AREA 2: Income and Expense Categorization Review**

**Objective:** Ensure all transactions are correctly categorized for tax purposes, with business and personal expenses properly separated.

**Inputs:**  
2.1.1. Reconciled Quicken data from Task Area 1  
2.1.2. Uncategorized transaction list from Quicken  
2.1.3. Prior year Income & Expense reports for comparison (e.g., YE24 ON MedCorp Inc & Exp CAD, YE24 BBX Income & Expense CADUSD, YE24 \- MB MedCorp Inc & Exp CAD, YE24 \- 6270158 Income & Expense CAD)  
2.1.4. Chart of accounts/category list  
2.1.5. Personal account statements

**Activities:**  
2.2.1. Review uncategorized transactions and assign appropriate categories  
2.2.2. Identify and correct miscategorized entries across all accounts  
2.2.3. Review income and expenses from personal accounts that should be allocated to business  
2.2.4. Verify completeness of monthly recurring expenses  
2.2.5. Review all flagged transactions in Quicken

**Deliverables:**  
2.3.1. Income & Expense Reports (separate CAD and USD versions per company)  
2.3.2. List of reclassified transactions with explanations  
2.3.3. Summary of recurring expenses verification

**Quality Checks:**  
2.4.1. No uncategorized transactions remain  
2.4.2. Business vs. personal expenses clearly separated  
2.4.3. All recurring expenses accounted for (12 months for annual items)

---

### **TASK AREA 3: Shared Expense Calculation and Allocation**

**Objective:** Accurately calculate and allocate shared operational expenses among the four companies.

**Inputs:**  
3.1.1. Income & Expense reports from Task Area 2  
3.1.2. Prior year allocation schedules  
3.1.3. Usage logs (auto mileage, office space measurements)  
3.1.4. Lease/rental agreements  
3.1.5. Insurance policies

**Activities:**  
3.2.1. Calculate office expense allocation (rent, utilities, insurance, maintenance)  
3.2.2. Determine auto expense allocation based on usage  
3.2.3. Allocate travel expenses appropriately  
3.2.4. Allocate real estate-related expenses

**Deliverables:**  
3.3.1. Shared expense allocation schedule  
3.3.2. Supporting calculations and allocation methodology  
3.3.3. Adjusted expense reports reflecting allocations

**Quality Checks:**  
3.4.1. Allocation percentages total 100%  
3.4.2. Methodology is consistent with prior years (unless documented change)  
3.4.3. All shared expenses are fully allocated

---

### **TASK AREA 4: Inter-Company Transactions and Shareholder Loans**

**Objective:** Verify and document all transfers between entities and review shareholder loan activity.

**Inputs:**  
4.1.1. Transfer reports from Quicken (all companies, CAD and USD): YE24 ON MedCorp Transfers CAD, YE24 BBX Transfers USD, YE24 \- MB MedCorp Transfers CAD, YE24 \- 6270158 Transfers CAD, YE24 \- 6270158 Transfers USD  
4.1.2. Shareholder loan account statements from Quicken: YE24 BBX Shareholder Loan CADUSD, YE24 \- 6270158 Shareholder Loan  
4.1.3. Prior year shareholder loan balances  
4.1.4. Inter-company transaction documentation  
4.1.5. Personal expense reimbursement records

**Activities:**  
4.2.1. Review all transfer reports between companies (CAD and USD)  
4.2.2. Verify shareholder loan activity for 627 and BBX  
4.2.3. Ensure inter-company transactions balance (amounts leaving one entity equal amounts entering another)  
4.2.4. Review expenses paid personally that should be reimbursed or assigned to shareholder loan accounts  
4.2.5. Investigate all $0.00 transfer entries (potential Quicken data entry anomalies)

**Deliverables:**  
4.3.1. Transfer reports (CAD and USD) per company  
4.3.2. Shareholder Loan Reports for 627 and BBX  
4.3.3. Inter-company transaction reconciliation worksheet  
4.3.4. List of discrepancies requiring resolution

**Quality Checks:**  
4.4.1. All inter-company transactions have matching entries  
4.4.2. Shareholder loan balances are accurate and supported  
4.4.3. No unexplained $0.00 transfer entries

---

### **TASK AREA 5: Investment Portfolio Review and Compliance**

**Objective:** Verify investment income, capital gains/losses, and ensure compliance with foreign investment reporting requirements.

**Inputs:**  
5.1.1. Investment account statements (627, ON, MB)  
5.1.2. Brokerage trading summaries and tax slips  
5.1.3. Investment income reports from Quicken: YE24 ON MedCorp Invmt Inc CAD/USD, YE24 \- MB MedCorp Invmt Inc CAD/USD, YE24 \- 6270158 Invmt Income CAD/USD  
5.1.4. Investment transaction reports from Quicken: YE24 ON MedCorp Invmt Transactions CAD/USD, YE24 \- MB MedCorp Invmt Transactions CAD/USD, YE24 \- 6270158 Invmt Transactions CAD/USD  
5.1.5. Capital gains reports: YE24 ON MedCorp Invmt CapGains CAD/USD, YE24 \- MB MedCorp Invmt Cap Gains CAD/USD, YE24 \- 6270158 Invmt CapGains CAD/USD  
5.1.6. Prior year T1135 reports (e.g., YE23 T1135 Foreign Investments \- All Corps)  
5.1.7. Foreign investment cost base records

**Activities:**  
5.2.1. Review investment income reports (interest, dividends, return of capital)  
5.2.2. Review capital gains/losses against brokerage trading summaries  
5.2.3. Verify investment transactions reconcile to income and gains  
5.2.4. Review dividend and return of capital calculations  
5.2.5. Prepare T1135 reports for foreign investments (consolidated for all corporations)

**Deliverables:**  
5.3.1. Investment Income Reports (CAD and USD) for 627, ON, and MB  
5.3.2. Investment Transaction Reports (CAD and USD) for 627, ON, and MB  
5.3.3. Capital Gains Reports (CAD and USD) for 627, ON, and MB  
5.3.4. T1135 Foreign Investment Reports (consolidated)  
5.3.5. Reconciliation to brokerage statements

**Quality Checks:**  
5.4.1. Investment income matches brokerage statements  
5.4.2. Capital gains calculations are accurate  
5.4.3. T1135 reporting thresholds verified  
5.4.4. All investment slips collected and scanned

---

### **TASK AREA 6: Report Generation and Quality Control**

**Objective:** Generate all required financial reports in standardized format and perform comprehensive quality control.

**Inputs:**  
6.1.1. Reconciled Quicken data file  
6.1.2. Prior year report packages (all companies)  
6.1.3. Report naming convention standards  
6.1.4. Chart of accounts changes log  
6.1.5. Prior year financial statements for comparison  
6.1.6. Comparison Check reports: Check- YE24 ON MedCorp Inc & Exp Comparison Check, Check- YE24 BBX Profit Loss Comparison, Check- MB MedCorp Inc & Exp Comparison Check

**Activities:**  
6.2.1. Generate all financial reports from Quicken for each company following prior year structure  
6.2.2. Verify currency displayed in each report (CAD vs. USD)  
6.2.3. Ensure all report filenames are prefixed with 'YExx'  
6.2.4. Check for newly created accounts, categories, or tags requiring incorporation  
6.2.5. Perform year-over-year variance analysis  
6.2.6. Confirm final company bank balances  
6.2.7. Review Accounts Receivable and Accounts Payable at year-end

**Deliverables:**  
6.3.1. Complete report package per company (Income/Expense, Transfers, Investment, etc.)  
6.3.2. Profit & Loss Comparison reports (year-over-year)  
6.3.3. Variance analysis with explanations  
6.3.4. AR/AP summary reports

**Quality Checks:**  
6.4.1. All reports use consistent naming conventions  
6.4.2. Currency is correctly displayed  
6.4.3. Reports match prior year format for comparability  
6.4.4. Significant variances are documented and explained

---

### **TASK AREA 7: Final Documentation and Package Preparation**

**Objective:** Compile all supporting documentation and finalize reports for external tax accountants.

**Inputs:**  
7.1.1. All generated reports from Task Area 6  
7.1.2. Investment tax slips (T3, T5, foreign slips)  
7.1.3. CRA account access for balance verification  
7.1.4. Master Checklist from year-end Excel workbook (YE25 \- YearEnd Business Report Checklist and Tools v1.xlsx)  
7.1.5. Supporting documentation (receipts, invoices, agreements)

**Activities:**  
7.2.1. Export all final Quicken reports to Excel-compatible format  
7.2.2. Gather and scan all investment slips and CRA documents  
7.2.3. Print CRA account balances and confirm alignment with Quicken Tax Expense records  
7.2.4. Complete Master Checklist verification  
7.2.5. Organize all compiled financial information for submission

**Deliverables:**  
7.3.1. Year-End Reporting Package (Excel \+ PDF) per company  
7.3.2. Scanned investment slips and tax documents  
7.3.3. CRA account balance confirmations  
7.3.4. Completed Master Checklist with sign-off  
7.3.5. Summary memo highlighting key items for tax accountant attention

**Quality Checks:**  
7.4.1. All checklist items marked complete  
7.4.2. All required supporting documents included  
7.4.3. Reports are final and reconciled  
7.4.4. Package is organized logically for accountant review
