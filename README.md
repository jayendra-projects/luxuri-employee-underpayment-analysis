# Luxuri Employee Underpayment Analysis
### KordaMentha Data Analytics Virtual Experience (Forage)

## Business Problem
Luxuri Australia Pty Ltd, a construction entity accused of underpaying staff, engaged
[simulated] KordaMentha to quantify the underpayment liability across its workforce
ahead of litigation.

## Objective
Cleanse a 171,046-row payroll timesheet dataset, identify and correct data integrity
issues, and calculate the total estimated underpayment owed to staff, agency employees,
and subcontractors.

## Approach
1. **Data profiling** - identified anomalies including a placeholder "Employee 0" cohort,
   mixed date formats causing day/month transposition, and a 3-column rotation error
   affecting 249 payroll transactions.
2. **Data cleansing** - built corrected fields (`zz_` prefix) in Excel, verified against
   source totals to confirm no data was lost or duplicated.
3. **Analysis** - applied the client's underpayment reference rates (by staff type and
   pay category) to calculate liability.
4. **Communication** - translated findings into a one-page executive summary for a
   non-technical client audience.

## Key Findings
- Total estimated underpayment: **$52.09M** across 1,048 employees (11.5% of $453.36M paid)
- Staff employees carried the highest exposure: $32.1M (13.0% of their pay)
- Identified and corrected 4 distinct data quality issues prior to analysis

## Tools
Microsoft Excel (pivot tables, formula-based reconciliation), data cleansing, root-cause
analysis




