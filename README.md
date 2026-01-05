# week3_hw
# Homework 3: CIA World Factbook Data Cleaning

## Overview
This project downloads, cleans, and formats three health datasets from the CIA World Factbook. Each dataset is cleaned to keep only 3 columns: **country**, **variable**, and **region**.

## Data Sources
- [Maternal Mortality Ratio](https://www.cia.gov/the-world-factbook/field/maternal-mortality-ratio/country-comparison/)
- [Infant Mortality Rate](https://www.cia.gov/the-world-factbook/field/infant-mortality-rate/country-comparison/)
- [Life Expectancy at Birth](https://www.cia.gov/the-world-factbook/field/life-expectancy-at-birth/country-comparison/)

## Files Created
| Dataset | RDS File | CSV File |
|---------|----------|----------|
| Maternal Mortality Ratio | maternal_mortality.rds | maternal_mortality.csv |
| Infant Mortality Rate | infant_mortality.rds | infant_mortality.csv |
| Life Expectancy at Birth | life_expectancy.rds | life_expectancy.csv |

## How It Was Done
1. Created data frames in Google Colab (R kernel) with data from CIA World Factbook
2. Saved each dataset as RDS and CSV using `saveRDS()` and `write.csv()`
3. Verified data types using `str()` for both formats
4. Converted `.ipynb` to `.Rmd` using `rmarkdown::convert_ipynb()`
5. Knitted to HTML using `rmarkdown::render()`

## Repository Contents
- `HW3_CIA_World_Factbook.ipynb` - Original Colab notebook
- `HW3_CIA_World_Factbook.Rmd` - Converted RMarkdown file
- `index.html` - Knitted HTML output
- 6 data files (3 RDS + 3 CSV)
