# SFR PD&LGD&RWA Project 

## Introduction
The primary goal of this project is to assess the credit risk and capital adequacy of the personal retail loan products portfolio of a financial institution via the calculation of PD, LGD, and ultimately RWA.

## Highlights of Project Steps
1. Data cleaning<br/>Data quality was assessed for model implementation and abnormal values of TDS and GDS smaller than '0' were detected, which were inconsistent with their definition. '0' was set to replace the incorrect TDS and GDS values. '0' was set to 'Arrears days' which shows null

2. Exploratory Data Analysis
   <br/>PD (Profitability of Default) Calculation:
    * Aggregated relevant fields for required 7 input model drivers
    * Implemented data transformation based on model specification and fit WOE (weight of evidence) to each model driver
    * Applied regression model to calculate PD core

   <br/>LGD (Loss Given Default) Calculation:
    * Aggregated relevant fields for required 6 input model drivers
    * Implemented data transformation based on model specification and fit WOE (weight of evidence) to each model driver
    * Applied regression model to calculate LGD core


   <br/>RWA (Risk of Assessts) Calculation:
    * categorized into 2 scenarios: defaulted loans and not defaulted loans
    * capital requirement calculation

  ## Tools Used
   * MySQL (Stored Procedure, CTE, Join, Variables etc. )
   * Python (Pandas, Numpy, SciPy)
   * Jupyter Notebook
   
   

