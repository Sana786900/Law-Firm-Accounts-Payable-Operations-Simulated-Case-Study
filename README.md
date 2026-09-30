# Law-Firm-Accounts-Payable-Operations-Simulated-Case-Study
A simulated law-firm accounts payable case study focused on invoice review, AP aging, vendor reconciliation, exception detection, and financial controls.
# Law Firm Accounts Payable Operations: Simulated Case Study

## Project Overview

This portfolio project demonstrates an accounts payable workflow for a fictional law firm. The project uses simulated invoice and vendor data to track outstanding obligations, review invoice activity, identify exceptions, reconcile vendor balances, and organize accounts payable information for reporting.

The purpose of this project is to show how I review financial records, identify potential payment and data-quality issues, monitor outstanding invoices, perform reconciliation procedures, and use Excel to create controls that make accounts payable activity easier to review.

## Business Problem

Accounts payable involves more than recording invoices and issuing payments. A business must also verify that invoices are valid, properly approved, accurately recorded, paid on time, and associated with legitimate vendors.

Without consistent controls, accounts payable records may contain duplicate invoices, missing approvals, overdue balances, invalid vendor information, or discrepancies between internal records and vendor statements.

For this simulated law firm, the goal was to create an organized AP workflow that could identify these issues while also providing a clear view of outstanding obligations and invoice aging.

## Project Objectives

- Organize and review a simulated accounts payable invoice dataset
- Track invoice amounts, payments, and outstanding balances
- Identify duplicate invoice records
- Detect invoices with missing approvals
- Validate vendors against an approved vendor list
- Identify overdue invoices requiring review
- Calculate invoice aging based on outstanding balances and due dates
- Create an Accounts Payable Aging report
- Reconcile internal AP records to vendor statement balances
- Document invoice and vendor exceptions for further review
- Build automated quality-control checks
- Present AP activity and exceptions through a financial dashboard

## Tools Used

- Microsoft Excel
- Accounts payable procedures
- Invoice and vendor review
- AP aging analysis
- Vendor reconciliation
- Excel formulas and tables
- Conditional logic and exception flags
- Financial data-quality checks
- Dashboard reporting

## Project Deliverables

- Vendor master list
- Accounts payable invoice register
- Automated invoice exception checks
- AP aging schedule
- Vendor reconciliation worksheet
- Exception and review tracking
- Accounts payable dashboard
- Automated reconciliation and quality-control checks
- Project notes and findings summary

## Skills Demonstrated

- Accounts payable analysis
- Invoice review
- Vendor validation
- Outstanding-balance tracking
- AP aging
- Vendor reconciliation
- Duplicate-invoice detection
- Missing-approval detection
- Overdue-invoice identification
- Exception management
- Financial data validation
- Reconciliation and control procedures
- Excel reporting
- Financial operations analysis

## Excel Skills & Formulas Used

The workbook uses formula-driven controls so that invoice-level information flows into the AP aging, reconciliation, exception, and dashboard reporting.

### IF Logic

`IF` statements are used to evaluate invoice information and return different results depending on whether specific conditions are met.

For example, conditional logic is used to determine whether an invoice should be flagged for review based on payment status, approval information, due dates, or vendor validation.

This allows potential AP issues to be identified automatically instead of reviewing every invoice manually.

### COUNTIF and COUNTIFS

`COUNTIF` and `COUNTIFS` are used to count records that meet specific criteria.

These functions support controls such as:

- Duplicate-invoice detection
- Missing-approval counts
- Overdue-invoice counts
- Vendor-validation exceptions
- Total invoices requiring review

For duplicate detection, the workbook checks how many times an invoice identifier appears in the invoice data. Records appearing more than once can then be flagged for investigation.

### SUMIFS

`SUMIFS` is used to summarize financial amounts according to specific conditions.

In the AP aging analysis, outstanding invoice balances are grouped according to aging categories. This allows the report to calculate how much unpaid AP falls into each aging bucket without manually totaling individual invoices.

### Date Calculations

Invoice due dates are compared with the reporting date to determine the age and status of unpaid invoices.

This logic is used to separate outstanding AP into aging categories such as:

- Current
- 1–30 days
- 31–60 days
- 61+ days

This makes it easier to identify older obligations that may require immediate attention.

### Cross-Sheet References

The workbook connects invoice-level data to the AP aging report, vendor reconciliation, exception reporting, and dashboard.

This reduces repeated manual entry and allows reporting sections to update when the underlying invoice information changes.

### Reconciliation Controls

Formula-based controls compare independently calculated totals to confirm that reports agree with their underlying data.

The workbook includes controls for:

- Outstanding AP
- Invoice review counts
- Vendor reconciliation
- Missing vendor information
- Invalid or unusual invoice values

PASS/FAIL checks make discrepancies easier to identify during review.

### Additional Excel Techniques

- Excel tables
- Structured financial data
- Sorting and filtering
- Conditional formatting
- Currency and date formatting
- Formula-driven exception flags
- Automated summary calculations
- Cross-sheet reporting
- Dashboard presentation
- Reconciliation and audit checks

## Project Results

The simulated AP dataset contains 72 invoice records with a total invoice value of **$176,940.50**.

The completed analysis identified **$56,518.75 in outstanding accounts payable** and **21 invoice records requiring additional review**.

The automated controls identified:

- 2 duplicate-invoice flags
- 3 missing-approval flags
- 16 overdue-invoice flags
- 1 invalid-vendor flag

The AP aging schedule reconciles to the underlying outstanding AP balance of **$56,518.75**.

The project also includes vendor reconciliation and automated control checks designed to confirm that the reporting outputs agree with the underlying invoice data.

These exceptions are intentionally included in the simulated dataset so the project demonstrates both routine AP reporting and the investigation of records that may require additional review.

## Project Status

This project is complete. The final workbook includes a simulated accounts payable environment, invoice-level exception controls, vendor validation, AP aging, vendor reconciliation, automated quality checks, and dashboard reporting.

## Disclosure

This is a simulated portfolio case study created to demonstrate practical accounts payable, reconciliation, Excel, and financial-operations skills.

The law firm, vendors, invoices, payments, balances, and financial results are fictional. No confidential client, employer, banking, vendor, or tax information was used.
