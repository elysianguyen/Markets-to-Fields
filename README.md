## From Markets to Fields: <br/> The Impact of Vietnam’s 1985 Dong Devaluation on Rice Exports 

This repository contains the data, code, and visualizations for the research investigating how the 1985 currency devaluation in Vietnam influenced rice export performance. Using a Structural Vector Autoregressive (SVAR) model identified via the changes in volatility (CV) method, the study quantifies the short-run and long-run dynamics between exchange rate shocks and agricultural trade.

### Project Introduction

This project evaluates whether the 1985 dong devaluation acted as a catalyst for Vietnam’s rice export expansion. The analysis confirms that real exchange rate depreciation produced a statistically significant but transitory increase in rice exports. These findings reinforce that currency policy alone is insufficient to sustain export growth, underscoring the importance of structural reforms.

### *Data & Code* Directory

- AnnualExchangeRate.csv: Annual nominal exchange rates in standard Vietnam dong (VND) per United States dollar (USD).

- MonthlyExchangeRate.csv: Monthly exchange rates in VND per USD.

- ExportQuantity.csv: Annual export quantities of "Rice, milled."

- RealGDP.csv: Real GDP values in standard VND with 2015 prices as the baseline.

- USDGDPDeflator.csv: GDP deflator values in USD with 2015 prices as the baseline.

- VNDGDPDeflator.csv: GDP deflator values in VND with 2015 prices as the baseline.

- Code.Rmd: Main R Markdown file for data transformation, visualization, modeling, and diagnostics.

### *Figures* Directory

- MonthlyExchangeRate.pdf: Plot of monthly VND per USD exchange rates from August to December, 1985

- NominalExchangeRate.pdf: Plot of annual nominal VND per USD exchange rates 1975-2023.

- RealExchangeRate.pdf: Plot of annual real VND per USD exchange rates 1975-2023.

- RiceExport.pdf: Plot of rice export quantities in tons 1975-2023.

- IRF.pdf: Plot of impulse response function (IRF) results.

- FEVD.pdf: Plot of forecast error variance decomposition (FEVD) results.

- HistoricalDecomposition.pdf: Plot of historical decomposition results.

- Counterfactual.pdf: Plot of counterfactual analysis results.

### *Paper* File

Final paper.

### Analysis Reproduction

- Clone this repository.

- Open *Code.Rmd* in RStudio.

- Ensure required packages are installed.

- Knit the R Markdown file to generate figures and results.

### License
This project is licensed under the MIT License – see the *LICENSE* file for details.

### Citation

If you use this work, please cite the associated paper. The example below is in APA style:

Nguyen, E. (2025). From Markets to Fields: The Impact of Vietnam’s 1985 Dong Devaluation on Rice Exports.

### Acknowledgement

I would like to thank my mentor Dr. Alexandre Scarcioffolo for his guidance throughout the research.

### Contact Information

Please contact <u>nguyen_d4@denison.edu</u> regarding any further questions, comments, and concerns.
