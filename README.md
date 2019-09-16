# Life-Insurance-Recommendation-Project

## Introduction
* Sample data & policy sources:
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
* `Cost_Index_Sensitivity_Analysis.pdf` contains 9 pages in total.
  * First 5 pages: raw data of five policies and cost indices calculation.
  * Last 4 pages: sensitivity analysis of indices w.r.t. dividend compound rate, annual dividends, maturity dividends, annual premium respectively.
  * Same content as `Cost_Index_Sensitivity_Analysis.xlsx`. The pdf file is more readable, whereas the excel file shows calculation details.
* `Life_Insurance_Recommendation_by_Cost_Analysis.pdf` is the final report for life insurance recommendation. Besides cost indices analysis, companies' financial capacity and policy coverage are also taken into account. In the end of the report, specific recommendations are given based on several assumptions like the insurer's age and health condition. 
* Key skills used:
  * Built-in functions: `SUMPRODUCT()`, `VLOOKUP()`, `COUNTIF()`
  * Data analysis tool: Senario Manager, Data Table
