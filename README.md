# Life-Insurance-Recommendation-Project

## Introduction
* Sample data & policy source:
  * AIA, AXA, BOC, Manulife, Prudential
* Cost indices used:
  * NPCI (Net Payment Cost Index): indicates the cost of a policy if the insured is diagnosed with at least one conditions covered in the critical illness coverage or dies in a specified year.
  * SCI (Surrender Cost Index): indicates the cost of a policy if the insurant surrenders the policy in a specific year.
* Factor considered in sensitivity analysis:
  * Dividend compound rate
  * Annual dividends
  * Maturity dividends
  * Annual premium
  * Interest rate

## Data Processing and Analysis
* `Cost_Index_Sensitivity_Analysis.pdf` contains nine pages in total.
  * First five pages: raw data of five policies and cost indices calculation
  * Last four pages: sensitivity analysis of indices w.r.t. dividend compound rate, annual dividends, maturity dividends, annual premium respectively
* Key skills used:
  * Built-in functions: `VLOOKUP()`, `COUNTIF`, `SUMPRODUCT()`
  * Data analysis tool: Senario Manager, Data Table
