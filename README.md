# Discounted-Cash-Flow-MSFT

## 📊 Microsoft DCF Valuation Summary

This model aims to conduct a **Discounted Cash Flow (DCF) valuation** for **Microsoft Corporation (MSFT)** as of **May 2025**, forecasting **free cash flows to the firm (FCFF)** over a 5-year period. A **terminal value** is applied to estimate the company's **intrinsic share price**.

The underlying company data — including the **income statement**, **balance sheet**, and **cash flow statement** — was sourced directly from Microsoft’s **SEC 10-K annual reports** for fiscal years **2022–2024**.

---

### 🔢 Methodology

- Historical values including **Revenue**, **EBIT**, **Net Income**, **Depreciation**, **CapEx**, and **Change in NWC** were manually input.
- A set of **key assumptions** (editable in the “Assumptions” tab) was created based on historical trends:
  - Revenue Growth
  - EBIT Margin
  - Tax Rate
  - Depreciation & Amortization
  - Capital Expenditures
  - Change in Working Capital

- The **Weighted Average Cost of Capital (WACC)** was calculated using:
  - Cost of Equity (via CAPM)
  - Cost of Debt
  - Historical capital structure  
  This produced a **WACC of 8.4%**, which was used as the discount rate.

![image](https://github.com/user-attachments/assets/1b26c1d2-249e-43b9-ac14-25b16e5df611)


- A **terminal growth rate of 2.5%** was selected, reflecting a conservative long-term assumption for a stable, mature company like Microsoft.

---

### 💰 Results

- The **present value of FCFF** and the **discounted terminal value** were used to compute:
  - **Enterprise Value**
  - **Equity Value**
  - **Implied Share Price: `$178.84`**

- Compared to the actual market share price of **$454.27**, the model’s implied price reflects a **conservative valuation**. This suggests the market is pricing in:
  - Anticipated growth in **AI infrastructure** and **cloud computing**
  - A premium for **brand strength**, **scalability**, and **global reach**

---

### 📈 Sensitivity Analysis

A two-variable sensitivity table was built to examine how the **implied share price** changes with variations in:
- **WACC**
- **Terminal Growth Rate**

![image](https://github.com/user-attachments/assets/002133a2-9b92-435d-977e-949b7ec56abf)


This is presented in the **“Summary and Sensitivity”** worksheet to help users evaluate valuation sensitivity under different macro and strategic conditions.


---
