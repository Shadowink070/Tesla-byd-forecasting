# Tesla vs BYD Stock Forecast (R)

This repository contains the R code and knitted HTML output for my project on
comparative time-series forecasting of **Tesla (TSLA)** and **BYD (1211.HK)**.

## Files
- `analysis/stock-forecast.Rmd` — main analysis (data processing + modelling + plots)
- `docs/stock-forecast.html` — knitted report output (viewable via GitHub Pages)

## Data
- Source: Yahoo Finance (retrieved in-script)
- Period: Jan 2015 – Dec 2024 (as used in the report)
- Working frequency: monthly series (daily → monthly aggregation)
- Primary series: Adjusted Close

> Note: Raw data is not necessarily stored in this repo; the script can download it again.

## How to run (R)
Open `analysis/stock-forecast.Rmd` in RStudio and click **Knit**.

If you are using `renv`:
```r
install.packages("renv")
renv::restore()
