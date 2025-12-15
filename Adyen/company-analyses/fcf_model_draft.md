# Adyen — Free Cash Flow Model (Draft)

This document converts Adyen’s operating forecast into Free Cash Flow
through an EBIT-to-FCF bridge. It builds upon the base-case operating
assumptions established in Phase 2.

The model focuses on:
- Depreciation & amortisation
- Capital expenditures
- Working capital dynamics
- Cash taxes
- Resulting Free Cash Flow

## Historical Context (2024)

FY 2024 represents a transition year for Adyen, marked by margin
normalisation and operational refocus. While not used as the base
year for forecasting, 2024 provides context for the current run-rate.

## 1. EBITDA to EBIT Bridge

Depreciation & amortisation (D&A) is assumed at a flat 5% of revenue,
reflecting Adyen’s asset-light business model and historical capital intensity.

### Depreciation & Amortisation Assumptions

| Year | Revenue | D&A (% of Revenue) | D&A |
|------|---------|--------------------|-----|
| 2025E | 2,187 | 5% | 109 |
| 2026E | 2,521 | 5% | 126 |
| 2027E | 2,848 | 5% | 142 |
| 2028E | 3,158 | 5% | 158 |

### EBIT Calculation

| Year | EBITDA | D&A | EBIT |
|------|--------|-----|------|
| 2025E | 1,094 | 109 | 985 |
| 2026E | 1,286 | 126 | 1,160 |
| 2027E | 1,481 | 142 | 1,339 |
| 2028E | 1,673 | 158 | 1,515 |

## 2. Capital Expenditures (CapEx)

Capital expenditures are assumed at 6% of revenue, reflecting ongoing
investments in Adyen’s platform infrastructure and Unified Commerce
terminal deployment.

### CapEx Assumptions

| Year | Revenue | CapEx (% of Revenue) | CapEx |
|------|---------|----------------------|-------|
| 2025E | 2,187 | 6% | 131 |
| 2026E | 2,521 | 6% | 151 |
| 2027E | 2,848 | 6% | 171 |
| 2028E | 3,158 | 6% | 189 |

## 3. Working Capital Assumptions

Adyen’s business model involves limited structural working capital
requirements, as merchant balances and settlement flows do not
represent operating working capital.

In the base case, changes in net working capital are assumed to be neutral
over the forecast period.

### Working Capital Impact

| Year | Change in Net Working Capital |
|------|-------------------------------|
| 2025E | 0 |
| 2026E | 0 |
| 2027E | 0 |
| 2028E | 0 |

## 4. Cash Taxes

Cash taxes are calculated using a flat effective tax rate of 25%,
applied to EBIT. This reflects Adyen’s geographic revenue mix and
historical effective tax levels.

### Cash Tax Calculation

| Year | EBIT | Tax Rate | Cash Taxes |
|------|------|----------|------------|
| 2025E | 985 | 25% | 246 |
| 2026E | 1,160 | 25% | 290 |
| 2027E | 1,339 | 25% | 335 |
| 2028E | 1,515 | 25% | 379 |

## 5. Free Cash Flow Calculation

Free Cash Flow is derived by adjusting EBIT for cash taxes, non-cash
charges, capital expenditures, and working capital movements.

### Free Cash Flow Bridge

| Year | EBIT | Cash Taxes | D&A | CapEx | ΔWC | Free Cash Flow |
|------|------|------------|-----|-------|-----|---------------|
| 2025E | 985 | (246) | 109 | (131) | 0 | 717 |
| 2026E | 1,160 | (290) | 126 | (151) | 0 | 845 |
| 2027E | 1,339 | (335) | 142 | (171) | 0 | 975 |
| 2028E | 1,515 | (379) | 158 | (189) | 0 | 1,105 |

---
Appendix: Source of Key Assumptions
---

## Source of Key Assumptions

The table below summarises the origin of each key modelling assumption used
in the operating forecast and Free Cash Flow model.

| Item | Value / Treatment | Source Type | Rationale |
|-----|------------------|------------|-----------|
| **2025E Revenue** | €2,187m | Company disclosure (H1 2025 run-rate) | Annualised H1 2025 segment revenues; conservative ×2 normalisation |
| **Segment mix (Digital / UC / Platforms)** | 58% / 31% / 11% | Company disclosure | Segment revenue breakdown from H1 2025 report |
| **Revenue growth (2026–2028)** | Segment-specific | Analyst assumption (Base case) | Based on observed H1 2025 growth trends and expected normalisation |
| **EBITDA margin (2025E)** | 50% | Company disclosure | Reported H1 2025 EBITDA margin |
| **EBITDA margin (2026–2028)** | 51% → 53% | Management guidance + analyst judgement | Management target of >50% margin by 2026, gradual operating leverage |
| **Depreciation & Amortisation** | 5% of revenue | Analyst assumption (normalised) | Asset-light model; historical D&A range ~4–6% of revenue |
| **Capital Expenditures (CapEx)** | 6% of revenue | Analyst assumption (conservative) | Ongoing platform investment and Unified Commerce terminal rollout |
| **Working Capital (ΔWC)** | 0 | Analyst assumption | Payments model with limited operating working capital requirements |
| **Effective cash tax rate** | 25% | Analyst assumption | Long-term effective tax rate reflecting geographic revenue mix |
| **EBIT** | EBITDA − D&A | Model-derived | Mechanical result of operating assumptions |
| **Free Cash Flow (FCF)** | EBIT − taxes + D&A − CapEx − ΔWC | Model-derived | Standard cash flow construction methodology |
