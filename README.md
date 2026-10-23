# DCF-Valuation-Marico-Bangladesh-limited
# Marico Bangladesh Ltd. — Discounted Cash Flow (DCF) Valuation Model

A financial modeling project using the **Discounted Cash Flow (DCF) method** to estimate the intrinsic value of Marico Bangladesh Limited based on historical financial statements, projected unlevered free cash flows, and the Weighted Average Cost of Capital (WACC).

## 📌 Project Overview

This project contains an Excel-based valuation model designed to analyze the financial performance and estimate the intrinsic equity value of Marico Bangladesh Limited.

The model integrates historical financial statements, operating forecasts, capital expenditure assumptions, working capital projections, and discount rate calculations to estimate enterprise value and implied share price.

**Key objectives:**
- Analyze historical financial performance.
- Forecast future revenue and operating profitability.
- Calculate unlevered free cash flow (UFCF).
- Estimate the Weighted Average Cost of Capital (WACC).
- Determine enterprise value and equity value.
- Calculate the implied intrinsic share price.
- Evaluate valuation sensitivity to changes in WACC and terminal growth assumptions.

## 🏢 Company Profile

- **Company:** Marico Bangladesh Limited
- **Industry:** Fast-Moving Consumer Goods (FMCG)
- **Sector:** Consumer Goods
- **Valuation Method:** Discounted Cash Flow (DCF)
- **Model Currency:** Bangladeshi Taka (BDT)
- **Financial Statement Units:** BDT millions, where specified

## 📂 Project Structure

The Excel workbook contains nine interconnected worksheets:

| Worksheet | Purpose |
|---|---|
| `Income Statement` | Historical revenue, operating expenses, depreciation, and taxes |
| `Balance Sheet` | Historical assets, liabilities, cash, debt, and equity-related data |
| `Cash Flow Statement` | Operating, investing, and financing cash flow information |
| `Free Cash Flow` | Forecast operating performance and unlevered free cash flow |
| `Fixed Assets` | Property, plant and equipment, depreciation, and capital expenditure projections |
| `Net Working Capital` | Working capital schedules and operating current asset/liability projections |
| `WACC` | Capital structure, cost of equity, cost of debt, and discount rate calculations |
| `DCF` | Discounted cash flows, terminal value, enterprise value, equity value, and implied share price |
| `Data Source -->` | Intended reference point for documenting data sources |

## 🧮 Valuation Methodology

### 1. Historical Financial Analysis

Historical financial statements provide the foundation for forecasting the company's future performance.

Key financial metrics include:
- Revenue growth
- Cost of goods sold (COGS)
- Gross profit
- Selling, general and administrative expenses (SG&A)
- Earnings before interest, taxes, depreciation and amortization (EBITDA)
- Operating profit (EBIT)
- Capital expenditure (CapEx)
- Operating working capital

### 2. Revenue and Operating Forecasts

Future operating performance is projected using assumptions about revenue growth, operating cost ratios, and the tax rate.

The model includes explicit revenue growth assumptions and forecasts for operating costs and depreciation.

Revenue is forecast using:

\[
Revenue_t=Revenue_{t-1}(1+g_t)
\]

Where:
- \(Revenue_t\) = revenue in the forecast year
- \(g_t\) = assumed annual revenue growth rate

### 3. Unlevered Free Cash Flow (UFCF)

The model estimates the cash flow available to all capital providers before financing payments.

\[
UFCF=EBIT(1-T)+D\&A-CapEx-\Delta NWC
\]

Where:
- \(EBIT\) = earnings before interest and taxes
- \(T\) = applicable operating tax rate
- \(D\&A\) = depreciation and amortization
- \(CapEx\) = capital expenditure
- \(\Delta NWC\) = change in net operating working capital

### 4. Weighted Average Cost of Capital (WACC)

WACC represents the discount rate used to calculate the present value of projected unlevered free cash flows.

\[
WACC=\frac{E}{V}R_e+\frac{D}{V}R_d(1-T)
\]

Where:
- \(E\) = market value of equity
- \(D\) = market value of interest-bearing debt
- \(V=E+D\)
- \(R_e\) = cost of equity
- \(R_d\) = pre-tax cost of debt
- \(T\) = applicable tax rate

The workbook includes assumptions for the risk-free rate, equity market risk premium, beta, cost of debt, and capital structure.

### 5. Terminal Value

Terminal value estimates the value of cash flows beyond the explicit forecast period using the perpetual growth method.

\[
TV_n=\frac{UFCF_{n+1}}{WACC-g}
\]

Where:
- \(TV_n\) = terminal value at the end of the forecast period
- \(UFCF_{n+1}\) = free cash flow in the first year after the forecast period
- \(g\) = perpetual growth rate

The calculation requires \(WACC>g\).

### 6. Enterprise Value and Equity Value

Enterprise value is estimated by adding the present value of forecast free cash flows to the present value of terminal value.

\[
EV=PV(\text{Forecast UFCF})+PV(TV)
\]

Equity value is then derived by adjusting enterprise value for cash, debt, and minority interests:

\[
Equity\ Value=EV+Cash-Debt-Minority\ Interest
\]

Finally, the implied share price is calculated as:

\[
\text{Implied Share Price}
=\frac{\text{Equity Value}}{\text{Diluted Shares Outstanding}}
\]

The valuation model uses diluted shares outstanding expressed in millions.

## 📊 Sensitivity Analysis

The DCF worksheet includes a sensitivity analysis examining how the implied valuation changes under alternative assumptions for:
- WACC
- Perpetual growth rate

Sensitivity analysis is useful because DCF valuations depend heavily on assumptions about future cash flows and the discount rate.

The sensitivity table can help identify how changes in these assumptions affect estimated enterprise and equity value.

## 🛠️ Tools and Skills Demonstrated

**Tools**
- Microsoft Excel
- Financial statement analysis
- Spreadsheet-based financial modeling

**Financial and analytical skills**
- Corporate valuation
- Discounted cash flow analysis
- Financial forecasting
- Free cash flow modeling
- WACC estimation
- Capital expenditure forecasting
- Net working capital modeling
- Terminal value calculation
- Valuation sensitivity analysis

## ▶️ How to Use the Model

1. Download the Excel workbook from this repository.
2. Open it in Microsoft Excel with formula calculation enabled.
3. Review the historical financial statements and their underlying sources.
4. Validate the revenue, operating expense, tax, CapEx, and working capital assumptions.
5. Review the WACC inputs and confirm that the discount rate is appropriate for the valuation.
6. Examine the DCF worksheet for enterprise value, equity value, and implied share price.
7. Adjust forecast assumptions and analyze the resulting sensitivity.

## ⚠️ Assumptions and Limitations

- The valuation depends on forecast assumptions and should not be interpreted as a guaranteed market price.
- Historical financial figures and source references should be verified against the company's published financial statements.
- The cost of equity, beta, risk-free rate, equity risk premium, and cost of debt require appropriate supporting evidence.
- The terminal growth rate should be economically reasonable and lower than WACC.
- Cash, interest-bearing debt, minority interests, and diluted shares outstanding should be reconciled with the latest available information.
- All formulas and linked worksheets should be checked for consistency before relying on the valuation.
- The workbook is an analytical and educational financial modeling project, not investment advice.

## 📚 Data Sources

The analysis should be supported by reliable company and market information, including:

- Marico Bangladesh Limited's published annual reports and financial statements.
- Official company disclosures and investor information.
- Relevant market data for share price and outstanding shares.
- Appropriate sources for risk-free rates, market risk premiums, beta, and borrowing costs.

**Note:** Specific source documents, publication dates, page references, and data retrieval dates should be documented in the workbook's `Data Source -->` worksheet.

## 👤 Author

**Financial Modeling Project — Marico Bangladesh Limited**

This project demonstrates the application of corporate finance principles to company valuation through an integrated Excel-based DCF model.

---

*Disclaimer: This model is intended for educational and analytical purposes only. It does not constitute investment advice or a recommendation to buy or sell securities.*
