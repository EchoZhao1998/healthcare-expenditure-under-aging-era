# Project: How Population Aging Reshapes Healthcare Financing**

## Overview
This project examines how population aging influences the composition of healthcare financing, rather than the total amount of healthcare spending. Using country-level panel data from the World Bank and the WHO Global Health Expenditure Database (GHED), the analysis explores whether aging societies systematically shift healthcare costs away from households toward collective financing mechanisms such as government funding and health insurance.

## Research Question
How does population aging affect the structure of healthcare financing across countries, and are these effects stronger in countries experiencing faster demographic aging?

## Data Sources
- WHO Global Health Expenditure Database (GHED)
Financing composition of healthcare expenditure (2000–2023)
- World Bank Population Data
Share of population aged 65 and above (SP.POP.65UP.TO.ZS)

Both datasets are publicly available and internationally comparable.

## Methodology
**Fixed-effects panel regression models to analyze within-country changes over time**

### Financing outcomes include:
  - Out-of-pocket expenditure share
  - Government health expenditure share
  - Social health insurance share
  - Voluntary health insurance share
  - An interaction model distinguishes countries with high aging intensity based on the long-run change in the elderly population share

## Key Findings
- Population aging is associated with a decline in out-of-pocket healthcare expenditure
- Aging corresponds to increased reliance on government financing and insurance-based mechanisms
- These effects are stronger in countries experiencing faster demographic aging
- Results suggest that healthcare systems actively reallocate financial responsibility in response to aging, rather than passively allowing costs to fall on households

## Tools
- R (tidyverse, plm, ggplot2)
- R Markdown for reproducible analysis

## Outputs
- Full analytical report (PDF)
- Reproducible R Markdown file
- Summary visualizations
