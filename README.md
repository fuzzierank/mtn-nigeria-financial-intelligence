# MTN Nigeria Financial Intelligence Analysis (2021–2025)

## Overview

This project analyses MTN Nigeria's financial and operating performance from 2021 to 2025.

The analysis focuses on a central business question:

> **How did MTN Nigeria's business model evolve during 2021–2025, and why did strong operating performance coexist with major swings in reported profitability?**

The project combines financial statement data with operating indicators to examine revenue transformation, the growth of the data business, profitability, cash generation, and the 2023–2024 foreign-exchange and cost pressures.

## Key findings

- Total revenue increased from **₦1.654tn in 2021 to ₦5.203tn in 2025**.
- Data revenue increased from **₦520.5bn to ₦2.782tn**.
- Data revenue's share of service revenue increased from approximately **31.5% to 53.8%**.
- Data subscribers increased from **34.3m to 53.2m**.
- Data usage per active user increased from **4.7GB to 13.1GB**.
- EBITDA increased from **₦877.1bn to ₦2.744tn**.
- Profit after tax was negative in **2023 and 2024**, before recovering to approximately **₦1.113tn in 2025**.
- The 2024 result was heavily affected by foreign-exchange losses and higher finance costs.
- Free cash flow recovered strongly in 2025 to approximately **₦1.225tn**.

## 2023–2024 financial stress

A major finding is the divergence between operating performance and reported bottom-line performance.

In 2024, revenue increased by approximately **36.1%**, while operating expenses increased by approximately **76.6%**. EBITDA nevertheless increased by 9.2%.

Below EBITDA, the financial result was affected by:

- Net finance costs of approximately **₦403.2bn**
- Net foreign-exchange loss of approximately **₦925.4bn**
- Profit after tax of approximately **−₦400.4bn**

The analysis also examines the sharp improvement between H1 and H2 2024.

## Data transformation

The data-business analysis asks whether MTN's transformation was driven only by subscriber growth or also by deeper customer usage.

The evidence shows both:

- Data subscribers: **34.3m → 53.2m**
- Data usage per active user: **4.7GB → 13.1GB**

This makes data revenue one of the central structural changes examined in the project.

## Repository structure

```text
mtn-nigeria-financial-intelligence/
│
├── data/
│   └── mtn_nigeria_financial_intelligence_2021_2025.csv
│
├── notebooks/
│   └── 01_mtn_financial_intelligence.ipynb
│
├── analysis/
│   └── 2023_2024_financial_stress.md
│
├── outputs/
│   ├── charts/
│   ├── financial_stress_analysis.csv
│   └── key_findings.csv
│
├── README.md
└── requirements.txt
```

## Methodology

The working dataset combines reported financial and operating indicators for 2021–2025 and calculates analytical metrics including:

- Revenue growth
- Data revenue share
- Voice revenue share
- EBITDA margin
- Profit margin
- Capex intensity
- Free-cash-flow margin
- Subscriber growth
- Data-usage growth
- 2021–2025 CAGR

The analysis separates operating indicators from financial items that can materially affect reported profit, particularly foreign-exchange effects and finance costs.

## Data sources

Primary source material is MTN Nigeria's annual reporting.

The five-year financial series used in the first version is taken from MTN Nigeria's **2025 Annual Report**, with selected 2023–2024 stress analysis cross-checked against the 2023 and 2024 Annual Reports.

The source PDFs are not included in this repository in Version 1. Users should consult MTN Nigeria's investor-relations archive for the original reports.

## Limitations

This is a portfolio analysis and not an investment recommendation.

Version 1 uses the five-year series presented in the 2025 Annual Report as its principal structured dataset. A future version should add source-page references to individual observations and perform a full line-by-line reconciliation against each year's audited financial statements.

## Next development steps

1. Add source-page references to the dataset.
2. Expand the FX and finance-cost bridge.
3. Add balance-sheet and debt analysis.
4. Add Nigeria macroeconomic indicators.
5. Build an interactive dashboard.
6. Add automated data-quality checks.
7. Refine the README with selected charts and a formal data dictionary.
