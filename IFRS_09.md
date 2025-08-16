# IFRS 9 – Financial Instruments

<!-- In Confluence: wrap this table inside {page-properties} macro -->

| Field                        | Details                                                                                                                                                                                                                                                                    |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Standard**                 | IFRS 9 – Financial Instruments                                                                                                                                                                                                                                             |
| **Links**                    | [IFRS 9 – IFRS.org](https://www.ifrs.org/issued-standards/list-of-standards/ifrs-9-financial-instruments/) <br> [AASB 9 – AASB.gov.au](https://standards.aasb.gov.au/aasb-9-dec-2022)                                                                                      |
| **Effective Date**           | 1 January 2018 (replaced IAS 39)                                                                                                                                                                                                                                           |
| **Objective**                | Establish principles for classification, measurement, impairment, and hedge accounting of financial instruments.                                                                                                                                                           |
| **Background**               | Replaced IAS 39 in response to the 2008 financial crisis, aiming to simplify financial instrument classification, require earlier recognition of credit losses through an Expected Credit Loss (ECL) model, and better align hedge accounting with actual risk management. |
| **Relevance to Credit Risk** | Governs Expected Credit Loss (ECL) recognition, staging of exposures, and affects PD/LGD/EAD inputs in capital and provisioning models.                                                                                                                                    |
| **Key Areas**                | Classification & Measurement, Impairment (ECL Model), Hedge Accounting                                                                                                                                                                                                     |
| **Last Updated**             | 15 Aug 2025                                                                                                                                                                                                                                                                |

# Overview

IFRS 9 sets the principles for recognising, measuring, and presenting financial instruments. It replaced IAS 39 to simplify classification rules, introduce a forward-looking impairment model, and align hedge accounting with risk management.

The standard covers:

- **Classification & Measurement** – Determines how assets/liabilities are categorised and measured (Amortised Cost, FVOCI, FVTPL).
- **Impairment** – Introduces the Expected Credit Loss (ECL) model, replacing the incurred loss model.
- **Hedge Accounting** – Brings hedge accounting closer to entities’ risk management practices.

## Objective

Provide useful information to users of financial statements regarding the amounts, timing, and uncertainty of an entity’s future cash flows.

This is achieved by:

- Classifying and measuring financial assets/liabilities appropriately.
- Recognising impairment losses earlier via a forward-looking model.
- Providing transparency on hedging activities.

## Background

- **Origin:** IFRS 9 was introduced in the aftermath of the 2008 Global Financial Crisis, which exposed weaknesses in IAS 39’s _“incurred loss”_ impairment model. Under IAS 39, credit losses were only recognised when there was objective evidence of impairment, often resulting in late recognition of losses.
- **Issues with IAS 39:** The standard was considered overly complex, rules-heavy, and difficult to apply consistently across industries and jurisdictions. It also had multiple overlapping classification categories (Held-to-Maturity, Loans and Receivables, Available-for-Sale), which created confusion and inconsistency.
- **IFRS 9 Improvements:**
  - **Simplified Classification & Measurement** – Reduced the number of asset categories to three, based on the business model and the contractual cash flow characteristics.
  - **Forward-Looking Impairment** – Introduced the Expected Credit Loss (ECL) model, requiring earlier recognition of credit losses using forward-looking information, addressing the procyclical delays seen under IAS 39.
  - **Aligned Hedge Accounting with Risk Management** – Made hedge accounting more principles-based to better reflect real-world risk management strategies.
  - **Improved Global Consistency** – Established a clearer, more principles-based framework to reduce divergence in practice.

## Banking / Credit Risk Lens

- **Provisioning impact:** Directly drives the size and timing of impairment charges.
- **Capital adequacy:** ECL provisions feed into regulatory capital calculations under Basel/APS.
- **Risk metrics:** Staging decisions affect PD/LGD inputs and stress testing.
- **Covenants & ratios:** Loan loss allowances influence borrower leverage and coverage ratios.

# Accounting Standard Details

## Scope

IFRS 9 applies to:

- All financial assets and liabilities except:
  - Investments in subsidiaries (IFRS 10)
  - Insurance contracts (IFRS 17)
  - Share-based payments (IFRS 2)
- Derivatives, debt instruments, equity investments, loan commitments, and financial guarantee contracts.

## Recognition and derecognition

An entity shall recognise a financial asset or a financial liability in its statement of financial position
when, and only when, the entity becomes party to the contractual provisions of the instrument.

## Classification

### Classification for Financial Assets

The classification is based on two tests:

- **Business Model Test** – How the company manages the asset (e.g., hold to collect, hold to sell, trade).
- **SPPI Test** (_Solely Payments of Principal and Interest_) – Whether the contractual cash flows are only principal and interest on the principal outstanding.

| Category                                                  | Business Model                                                                                                                                                                                       | SPPI Test | Accounting                                                                                                                                                                                | Examples                                                                                                                                                                                                                                                          | Why This Makes Sense                                                                                                                                                                                                                             |
| --------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Amortised Cost**                                        | Hold the asset to collect contractual cash flows only (no regular selling).                                                                                                                          | Passes    | Measured at amortised cost using the effective interest method (spread income over the life of the asset).<br><br>Changes in fair value aren’t recognised in P&L unless impaired or sold. | - Bank loans to customers (e.g., mortgages, personal loans).<br>- Trade receivables.<br>- Corporate bonds held to maturity.                                                                                                                                       | The entity intends to earn the contractual interest and principal repayments over time, so recognising the value steadily matches the cash flow pattern and avoids volatility from temporary market value changes.                               |
| **Fair Value through Other Comprehensive Income (FVOCI)** | Both collect contractual cash flows and sell the asset.                                                                                                                                              | Passes    | Measured at fair value.<br><br>Unrealised gains/losses go to OCI (equity) until the asset is sold; on sale, the cumulative OCI amount is recycled to P&L.                                 | - Debt securities that a bank might sell for liquidity management (e.g., government bonds in a liquidity buffer).<br>- High-grade corporate bonds held for yield but available for sale if funding needs change.                                                  | The business model involves both collecting interest and occasionally selling. Fair value is relevant because sales are part of the strategy, but unrealised changes don’t hit P&L immediately to avoid distorting ongoing performance measures. |
| **Fair Value through Profit or Loss (FVTPL)**             | Asset is held for trading; or SPPI test fails (cash flows include non-basic features like equity-linked returns or leveraged interest rates); or designated at FVTPL to avoid accounting mismatches. | Fails     | Measured at fair value.<br><br>All gains/losses (realised and unrealised) go directly to P&L.                                                                                             | - Equity investments (unless irrevocably designated as FVOCI under the equity option).<br>- Structured notes with embedded derivatives.<br>- Loans with interest linked to commodity prices.<br>- **Derivative assets** (e.g., interest rate swaps, FX forwards). | When assets are held to profit from short-term price movements or have complex cash flows, fair value changes are relevant to current performance, so gains/losses are recognised immediately in P&L.                                            |

### Classification of Financial Liabilities

Most financial liabilities are measured at **Amortised Cost**, except in specific cases where FVTPL is required or elected.

| Category                                      | Criteria                                                                                                       | Accounting                                                                                                                                                                              | Examples                                                                                                                                          | Why This Makes Sense                                                                                                                                                                                                                   |
| --------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Amortised Cost**                            | Default classification for financial liabilities unless they meet FVTPL criteria.                              | Measured at amortised cost using the effective interest method.                                                                                                                         | - Bank borrowings.<br>- Trade payables.<br>- Lease liabilities (IFRS 16).                                                                         | The entity’s objective is to settle the liability over time according to contractual terms, so amortised cost reflects the actual interest expense and repayment pattern without short-term market value volatility.                   |
| **Fair Value through Profit or Loss (FVTPL)** | 1. Held for trading; or<br>2. Designated at FVTPL to eliminate or significantly reduce an accounting mismatch. | Measured at fair value; all gains/losses in P&L.<br><br>For liabilities designated at FVTPL, changes in own credit risk are recognised in OCI (unless it creates/increases a mismatch). | - Derivative liabilities (e.g., interest rate swaps, FX forwards).<br>- Structured debt with embedded derivatives.<br>- Debt designated at FVTPL. | When liabilities are actively traded, have complex cash flows, or are designated to match assets measured at fair value, recognising fair value changes in P&L gives a more accurate picture of current performance and risk exposure. |
| **Other Specific Liabilities**                | Special cases covered by other standards.                                                                      | Measurement and disclosure under relevant standards.                                                                                                                                    | - Financial guarantee contracts (IFRS 9).<br>- Loan commitments at below-market rates (IFRS 9).                                                   | These liabilities have unique risk and cash flow profiles, so specific measurement rules are needed to reflect the underlying economic substance and potential obligations.                                                            |

### Reclassification

- **Financial Assets** – Reclassification is required _only_ when an entity changes its business model for managing those assets. This is expected to be **very rare** and must be applied prospectively from the reclassification date.
- **Financial Liabilities** – Reclassification is **not permitted** under IFRS 9. Once a liability is classified, it remains in that category until derecognition.

## Measurement

The measurement of financial instruments under IFRS 9 is determined by their classification at initial recognition.  
The two main measurement bases are **Amortised Cost** and **Fair Value** (through either OCI or P&L).  
Some specific instruments have their own measurement requirements.

**Key items to note**:

- **Initial measurement**: An entity shall measure a financial asset or financial liability at its fair value plus or minus, in the case of a financial asset or financial liability not at fair value through profit or loss, transaction costs that are directly attributable to the acquisition or issue of the financial asset or financial liability.
- **Subsequent measurement**:
  - Financial assets at:
    - (a) amortised cost;
    - (b) fair value through other comprehensive income; or
    - (c) fair value through profit or loss.
  - Financial liabilities at: <TBD>
- **Impairment**: ECL shall be recognised on financial assets. An entity shall measure expected credit losses of a financial instrument in a way that reflects:
  - (a) an unbiased and probability-weighted amount that is determined by evaluating a range of possible outcomes;
  - (b) the time value of money; and
  - (c) reasonable and supportable information that is available without undue cost or effort at the reporting date about past events, current conditions and forecasts of future economic conditions.

### Additional notes on Impairment – Expected Credit Loss (ECL) Model

There are three measurement outcomes that IFRS 9 notes:

- **No significant increase in credit risk since origination** → 12-month ECL (often called **Stage 1**)
- **Significant increase in credit risk (SICR)** → lifetime ECL (**Stage 2**)
- **Credit-impaired** → lifetime ECL and interest on the **net** carrying amount (**Stage 3**)

> **Terminology note:** IFRS 9 doesn’t use “Stage 1/2/3” wording. These labels are common shorthand used by banks, auditors, and regulators to describe the three outcomes the standard requires (12-month ECL, lifetime ECL, and credit-impaired/net interest). We use the shorthand for clarity and consistency with market practice. The reason for the use of stages is because:
>
> - During IASB/FASB development, the impairment model was discussed as a **“three-bucket” approach**. Although the final standard avoided the “bucket/stage” labels, the underlying mechanics remained. Practice kept the labels because they’re operationally useful.
> - Auditors, regulators, and banks needed a **common operational language** for systems, policies, and disclosures. “Stage” terminology gives a quick mapping to **(i) allowance basis** and **(ii) interest recognition**.
> - It supports required **movement reconciliations** (opening → closing loss allowance) and **credit risk migration** tracking, which many firms present internally and externally.

**Backstops & indicators (common in policies/guidance):**

- Quantitative: PD deterioration beyond policy thresholds; **>30 DPD** often used as a SICR backstop (rebuttable).
- Credit-impaired backstop: **>90 DPD** (also rebuttable) or objective evidence of impairment.
- Qualitative: watchlist status, forbearance, covenant breaches, sector stress, etc.

**Important nuance — POCI/Purchased Credit-Deteriorated (PCD):**

- **POCI/PCD** assets are **not** “Stage 3” at initial recognition. Their **lifetime expected losses are built into the credit-adjusted EIR** on day one; thereafter, the loss allowance reflects **changes** in lifetime ECL since purchase. Many banks present POCI separately from Stages 1–3.

**The Three-Stage Model**

| Stage       | Condition                                                                                       | Allowance     | Interest Revenue Recognition                   |
| ----------- | ----------------------------------------------------------------------------------------------- | ------------- | ---------------------------------------------- |
| **Stage 1** | Performing; no significant increase in credit risk since origination.                           | 12-month ECL. | On gross carrying amount.                      |
| **Stage 2** | Significant increase in credit risk (SICR) since initial recognition (but not credit-impaired). | Lifetime ECL. | On gross carrying amount.                      |
| **Stage 3** | Asset is credit-impaired.                                                                       | Lifetime ECL. | On net carrying amount (after loss allowance). |

**Significant increase in credit risk (SICR) Indicators**

- Quantitative: PD movement beyond threshold, days past due (often >30 days).
- Qualitative: Watchlist status, sectoral downturns, covenant breaches.
- Backstop: >30 days past due = Stage 2; >90 days = Stage 3 (unless rebuttable).

**Forward-Looking Information**

- Incorporate macroeconomic scenarios and weightings.
- Model overlays allowed where data limitations exist.

---

### Measurement for Financial Assets

#### Amortised Cost Measurement for a Financial Asset - Fixed interest loan

**Scenario:**  
A bank issues a 5-year fixed-rate loan of $1,000,000 to a corporate customer at an interest rate of 5% per annum, payable annually. The loan passes the **SPPI test** and the bank’s business model is to hold the loan to collect contractual cash flows.

##### Year 1

**Step 1 – Initial Recognition**  
The bank recognises the loan at its fair value on day one (usually the principal advanced, unless there’s a premium/discount or transaction costs):

    Dr Loan Receivable          1,000,000
       Cr Cash                               1,000,000

**Step 2 – Subsequent Measurement (Interest Recognition)**  
Interest income is recognised using the **Effective Interest Method (EIR)**. If the EIR equals the contractual rate (5%), annual interest income is $50,000:

    Dr Cash                     50,000
       Cr Interest Income (P&L)              50,000

**Step 3 – Impairment Adjustment**  
Under IFRS 9’s ECL model, even performing assets (Stage 1) require a 12‑month Expected Credit Loss (ECL) allowance. Suppose the ECL is $8,000 at year‑end:

    Dr Impairment Loss (P&L)     8,000
       Cr Loss Allowance                        8,000

**Step 4 – Carrying Amount at Year‑End**  
Carrying amount = $1,000,000 (principal) − $8,000 (loss allowance) = **$992,000**.

##### Year 2

If there are **no changes to credit risk** (still Stage 1), the loan continues to be measured at amortised cost with the same ECL allowance.

**1. Interest Income Recognition**

    Dr Cash                     50,000
       Cr Interest Income (P&L)              50,000

**2. Maintain Loss Allowance**  
If the ECL remains at $8,000:

- **No journal** if the allowance balance is unchanged; **or**
- Some entities reverse and re‑recognise the allowance for presentation:

_Reversal of prior allowance:_

    Dr Loss Allowance            8,000
       Cr Impairment Loss (P&L)                 8,000

_Recognition of current‑year allowance:_

    Dr Impairment Loss (P&L)     8,000
       Cr Loss Allowance                        8,000

(Net effect: **zero** in P&L if the ECL has not changed.)

**3. Year‑End Carrying Amount**  
Still: $1,000,000 − $8,000 = **$992,000**.

**Key Point:** If risk hasn’t changed, the ECL stays at the same level and the only recurring P&L effect is interest income (unless re‑presenting provisions).

##### Year 5 (Final Year – Maturity)

If there are **no changes to risk** and the borrower repays in full at maturity:

**1. Final Year’s Interest Income**

    Dr Cash                     50,000
       Cr Interest Income (P&L)              50,000

**2. Reverse Loss Allowance**

    Dr Loss Allowance            8,000
       Cr Impairment Loss (P&L)                 8,000

**3. Derecognise the Loan on Repayment**

    Dr Cash                  1,000,000
       Cr Loan Receivable                  1,000,000

---

#### Amortised Cost Measurement for a Financial Asset – Loan with Principal & Interest (P&I) Payments

**Scenario:**  
A bank issues a 30-year fixed-rate loan of AUD 300,000 to a customer at an interest rate of 4% per annum, with **annual P&I repayments** of 17,343 (this is the annuity amount that fully repays the loan over 30 years).

The loan passes the **SPPI test** and the bank’s business model is to hold the loan to collect contractual cash flows.  
For simplicity, we’ll assume no fees, no prepayments, and the loan remains Stage 1 with a constant ECL allowance of $2,000.

### Year 1

**Step 1 – Initial Recognition**

    Dr Loan Receivable          300,000
       Cr Cash                               300,000

**Step 2 – Subsequent Measurement (Interest & Principal)**

- Interest income for Year 1 = 4% × $300,000 = $12,000
- Annual repayment = $17,343
- Principal portion = $17,343 − $12,000 = $5,343

_Interest income:_

    Dr Cash                     17,343
       Cr Interest Income (P&L)              12,000
       Cr Loan Receivable                     5,343

**Step 3 – Impairment Adjustment**  
Loss allowance at year-end = $2,000

    Dr Impairment Loss (P&L)     2,000
       Cr Loss Allowance                        2,000

**Step 4 – Carrying Amount at Year-End**  
Loan receivable balance after principal repayment = $300,000 − $5,343 = $294,657  
Net carrying amount after ECL allowance = $294,657 − $2,000 = **$292,657**

### Year 2

Loan receivable opening balance = $294,657

**1. Interest & Principal**

- Interest = 4% × $294,657 = $11,786
- Annual repayment = $17,343
- Principal portion = $17,343 − $11,786 = $5,557

Entry:

    Dr Cash                     17,343
       Cr Interest Income (P&L)              11,786
       Cr Loan Receivable                     5,557

**2. Maintain Loss Allowance**  
ECL remains at $2,000:

- If unchanged, no journal entry; OR reverse/rebook for presentation:

_Reversal of prior allowance:_

    Dr Loss Allowance            2,000
       Cr Impairment Loss (P&L)                 2,000

_Recognition of current-year allowance:_

    Dr Impairment Loss (P&L)     2,000
       Cr Loss Allowance                        2,000

**3. Year-End Carrying Amount**  
Loan receivable balance after principal repayment = $294,657 − $5,557 = $289,100  
Net carrying amount after ECL = $289,100 − $2,000 = **$287,100**

### Final Year (Year 30 – Maturity)

By the final year, the loan receivable balance will have reduced to a small final principal portion.

**1. Interest & Principal**

- Final interest = 4% × opening balance (small amount in last year)
- Final repayment = remaining principal + final interest

Example (final year opening balance $16,600):

- Interest = 4% × $16,600 = $664
- Repayment = $17,264 (includes $664 interest + $16,600 principal)

_Final loan payment:_

    Dr Cash                     17,264
       Cr Interest Income (P&L)                 664
       Cr Loan Receivable                    16,600

**2. Reverse Loss Allowance**
Since the loan is repaid in full and derecognised, the allowance is released:

    Dr Loss Allowance            2,000
       Cr Impairment Loss (P&L)                 2,000

**3. Derecognise the Loan**
Loan balance is now zero; no further entry is needed after repayment.

**Key Points:**

- The **Effective Interest Method** allocates each repayment between interest income and principal reduction.
- Interest income decreases over time as the principal balance reduces.
- The ECL allowance remains until the asset is derecognised, then it is reversed through P&L.

---

#### Fair Value through Other Comprehensive Income (FVOCI) – Practical Example

**Scenario:**  
A bank purchases a government bond for $5,000,000 with a fixed coupon rate of 5% per annum, payable annually.

- The bond passes the **SPPI test** (only principal and interest payments).
- Business model: **Hold to collect contractual cash flows and sell** (e.g., as part of a liquidity buffer).
- Bond matures in 5 years.
- At the end of Year 1, the fair value of the bond rises to $5,200,000.
- We assume no credit impairment in this example.

##### Year 1

**Step 1 – Initial Recognition**  
At purchase, the bond is recognised at fair value (usually the purchase price):

    Dr Debt Investment – FVOCI      5,000,000
       Cr Cash                                      5,000,000

**Step 2 – Interest Income (Effective Interest Method)**  
Annual coupon = 5% × $5,000,000 = $250,000:

    Dr Cash                           250,000
       Cr Interest Income (P&L)                   250,000

**Step 3 – Fair Value Adjustment**  
At year-end, the fair value increases from \$5,000,000 to \$5,200,000, an unrealised gain of \$200,000.  
For FVOCI debt instruments:

- **Unrealised gains/losses go to OCI**, not P&L.
- The carrying amount is updated to fair value.

_Journal:_

    Dr Debt Investment – FVOCI        200,000
       Cr OCI – FVOCI Reserve                      200,000

**Step 4 – Carrying Amount at Year-End**  
Debt investment is now carried at $5,200,000.

OCI reserve contains an unrealised gain of $200,000.

##### Year 2 (Price Drop Example)

Opening carrying amount = $5,200,000

**1. Interest Income**
Annual coupon = 5% × $5,000,000 (nominal) = $250,000:

    Dr Cash                           250,000
       Cr Interest Income (P&L)                   250,000

**2. Fair Value Adjustment**  
At year-end, fair value falls to $5,050,000:

- Change = $5,050,000 − $5,200,000 = **$150,000 loss**
- Loss is recognised in OCI (reducing the FVOCI reserve).

_Journal:_

    Dr OCI – FVOCI Reserve            150,000
       Cr Debt Investment – FVOCI                  150,000

**3. Year-End Carrying Amount**  
Debt investment = $5,050,000

OCI reserve = $50,000 gain (200,000 − 150,000)

##### Year 5 (Maturity – Sale or Redemption)

**Case A – Redemption at Par**  
If held to maturity and redeemed at $5,000,000:

1. **Final Interest Payment** (Year 5 coupon):

   Dr Cash 250,000
   Cr Interest Income (P&L) 250,000

2. **Reverse OCI Reserve**  
   Cumulative OCI gains/losses are **recycled** to P&L at maturity:

If OCI reserve at maturity = $50,000 gain:

    Dr OCI – FVOCI Reserve             50,000
       Cr Gain on Debt Investment (P&L)            50,000

3. **Derecognise the Investment**:

   Dr Cash 5,000,000
   Cr Debt Investment – FVOCI 5,000,000

**Key Points:**

- FVOCI for debt instruments shows interest in P&L, unrealised fair value changes in OCI.
- Upon disposal or maturity, cumulative OCI is recycled to P&L.
- Useful when assets may be sold before maturity but are also held to earn interest income.

---

#### Fair Value through Profit or Loss (FVTPL) – Practical Example

**Scenario:**  
A bank purchases a corporate bond for $2,000,000 with a fixed coupon rate of 6% per annum, payable annually.

- The bond **fails the SPPI test** because its interest payments are linked to a commodity price index.
- Business model: Managed and evaluated on a fair value basis.
- Bond matures in 3 years.
- At the end of Year 1, fair value rises to $2,050,000.
- At the end of Year 2, fair value falls to $1,980,000.
- At the end of Year 3, the bond is redeemed at $2,000,000.

##### Year 1

**Step 1 – Initial Recognition**  
At purchase, the bond is recognised at fair value (purchase price):

    Dr Debt Investment – FVTPL      2,000,000
       Cr Cash                                     2,000,000

**Step 2 – Interest Income**  
Annual coupon = 6% × $2,000,000 = $120,000.  
Under FVTPL, interest is recognised directly in P&L as part of total fair value movements or separately (policy choice).

    Dr Cash                           120,000
       Cr Interest Income (P&L)                   120,000

**Step 3 – Fair Value Adjustment (Gain)**  
Fair value increases to $2,050,000:  
Unrealised gain = $50,000 → recognised in P&L immediately.

    Dr Debt Investment – FVTPL         50,000
       Cr Fair Value Gain (P&L)                     50,000

**Year-End Carrying Amount:** $2,050,000

##### Year 2

Opening carrying amount = $2,050,000

**1. Interest Income**  
Annual coupon = $120,000:

    Dr Cash                           120,000
       Cr Interest Income (P&L)                   120,000

**2. Fair Value Adjustment (Loss)**  
Fair value decreases to $1,980,000:  
Unrealised loss = $70,000 → recognised in P&L.

    Dr Fair Value Loss (P&L)            70,000
       Cr Debt Investment – FVTPL                   70,000

**Year-End Carrying Amount:** $1,980,000

##### Year 3 (Maturity)

Opening carrying amount = $1,980,000

**1. Interest Income**  
Annual coupon = $120,000:

    Dr Cash                           120,000
       Cr Interest Income (P&L)                   120,000

**2. Fair Value Adjustment Before Redemption**  
Redemption value = $2,000,000:  
Gain = $20,000 → recognised in P&L.

    Dr Debt Investment – FVTPL         20,000
       Cr Fair Value Gain (P&L)                     20,000

**3. Redemption – Derecognise the Bond**:

    Dr Cash                         2,000,000
       Cr Debt Investment – FVTPL               2,000,000

**Key Points:**

- All changes in fair value (realised and unrealised) go directly to P&L.
- FVTPL provides timely recognition of changes in market value for instruments managed on a fair value basis.
- Suitable for trading portfolios, derivatives, and instruments with complex or non-basic cash flows.

---

## Measurement for Financial Liabilities

---

### Amortised Cost Measurement – Fixed Rate Loan Payable

**Scenario:**  
A company borrows $1,000,000 from a bank at a fixed interest rate of 5% per annum, repayable in full at the end of 5 years (interest paid annually).  
The liability does not meet the FVTPL criteria and is therefore measured at **amortised cost**.

#### Year 1

**Step 1 – Initial Recognition**  
The loan is initially recognised at the proceeds received:

    Dr Cash                           1,000,000
       Cr Loan Payable                              1,000,000

**Step 2 – Subsequent Measurement (Interest Expense)**  
Interest expense is recognised using the **Effective Interest Method (EIR)**. If the EIR equals the contractual rate (5%), annual interest expense is $50,000:

    Dr Interest Expense (P&L)            50,000
       Cr Cash                                          50,000

**Step 3 – Year-End Carrying Amount**  
Since there are no fees or discounts, the carrying amount remains $1,000,000 until repayment.

#### Year 5 (Final Year – Maturity)

**1. Final Year’s Interest Expense**

    Dr Interest Expense (P&L)            50,000
       Cr Cash                                          50,000

**2. Derecognise the Loan on Repayment**

    Dr Loan Payable                  1,000,000
       Cr Cash                                        1,000,000

---

### Amortised Cost Measurement – Loan Payable with P&I Payments

**Scenario:**  
A company borrows 300,000 from a bank at an interest rate of 4% per annum, repayable over 30 years via **annual P&I payments** of $17,343.

The liability is measured at amortised cost.

#### Year 1

**Step 1 – Initial Recognition**

    Dr Cash                           300,000
       Cr Loan Payable                              300,000

**Step 2 – Subsequent Measurement (Interest & Principal)**

- Interest expense for Year 1 = 4% × $300,000 = $12,000
- Principal portion = $17,343 − $12,000 = $5,343

_Journal:_

    Dr Interest Expense (P&L)            12,000
    Dr Loan Payable                        5,343
       Cr Cash                                          17,343

**Step 3 – Year-End Carrying Amount**  
Loan payable balance after principal repayment = $300,000 − $5,343 = **$294,657**

#### Year 2

Opening balance = $294,657

- Interest = 4% × $294,657 = $11,786
- Principal = $17,343 − $11,786 = $5,557

_Journal:_

    Dr Interest Expense (P&L)            11,786
    Dr Loan Payable                        5,557
       Cr Cash                                          17,343

Closing balance = **$289,100**

#### Final Year (Year 30 – Maturity)

Example (final year opening balance = $16,600):

- Interest = 4% × $16,600 = $664
- Principal = $16,600
- Total final payment = $17,264

_Journal:_

    Dr Interest Expense (P&L)               664
    Dr Loan Payable                       16,600
       Cr Cash                                          17,264

Loan is now fully repaid (carrying amount = 0).

---

### Fair Value through Profit or Loss (FVTPL) – Practical Example

**Scenario:**  
A company issues a structured note for $2,000,000 with interest linked to a commodity index (fails SPPI test).  
Business purpose: liability is managed on a fair value basis.  
Interest is 6% fixed + variable commodity-linked adjustment (cash coupon shown separately here).  
Maturity: 3 years.

- End of Year 1: fair value decreases to $1,950,000.
- End of Year 2: fair value increases to $2,020,000.
- End of Year 3: redeemed at $2,000,000.

#### Year 1

**Step 1 – Initial Recognition**

    Dr Cash                           2,000,000
       Cr Structured Note Payable – FVTPL           2,000,000

**Step 2 – Interest Expense (Cash Coupon)**  
Annual coupon = 6% × $2,000,000 = $120,000:

    Dr Interest Expense (P&L)           120,000
       Cr Cash                                         120,000

**Step 3 – Fair Value Adjustment (Loss)**  
FV drop = $2,000,000 − $1,950,000 = $50,000 loss (liability increases):

    Dr Fair Value Loss (P&L)              50,000
       Cr Structured Note Payable – FVTPL             50,000

Closing carrying amount = **$1,950,000**

#### Year 2

Opening balance = $1,950,000

**1. Interest Expense**

    Dr Interest Expense (P&L)           120,000
       Cr Cash                                         120,000

**2. Fair Value Adjustment (Gain)**  
FV increase = $2,020,000 − $1,950,000 = $70,000 gain (liability decreases):

    Dr Structured Note Payable – FVTPL   70,000
       Cr Fair Value Gain (P&L)                         70,000

Closing carrying amount = **$2,020,000**

#### Year 3 (Maturity)

Opening balance = $2,020,000

**1. Interest Expense**

    Dr Interest Expense (P&L)           120,000
       Cr Cash                                         120,000

**2. Fair Value Adjustment Before Redemption**  
FV change = $2,000,000 − $2,020,000 = $20,000 loss (liability increases):

    Dr Fair Value Loss (P&L)              20,000
       Cr Structured Note Payable – FVTPL             20,000

**3. Redemption**

    Dr Structured Note Payable – FVTPL 2,000,000
       Cr Cash                                         2,000,000

---

### Other Specific Liabilities – Financial Guarantee Contract Example

**Scenario:**  
A company issues a financial guarantee to a bank for a subsidiary’s loan.  
Under IFRS 9, the guarantee is initially recognised at fair value (e.g., $30,000).  
Subsequently, it is measured at the higher of:

- The amount of the loss allowance under IFRS 9’s ECL model; and
- The amount initially recognised less cumulative income recognised.

**Initial Recognition**

    Dr Cash / Receivable                30,000
       Cr Financial Guarantee Liability               30,000

**Year-End Adjustment** (if ECL estimate increases to $40,000):

    Dr Loss on Financial Guarantee (P&L) 10,000
       Cr Financial Guarantee Liability               10,000

---

**Key Points**

- **Amortised cost** liabilities recognise interest using EIR, with the carrying amount reduced as repayments are made.
- **FVTPL** liabilities remeasure the carrying amount to fair value each period, with **all gains and losses** in P&L (own credit risk changes go to OCI **only** when the liability is **designated** at FVTPL to avoid mismatch).
- **Financial guarantees and certain loan commitments** follow specific IFRS 9 measurement rules that reflect expected losses and the pattern of income recognition.

---

## Hedge Accounting (IFRS 9)

### Purpose (why hedge accounting exists)

- **Problem:** Without hedge accounting, derivatives hit **P&L at fair value** each period, while the hedged item (forecast sales/purchases, floating-rate interest, foreign net investment) may affect **P&L later** or sit in **OCI/equity**. This creates **timing mismatches** and volatility that **don’t reflect risk management**.
- **IFRS 9 solution:** If specific conditions are met, align the **accounting profile** of the hedging instrument and the hedged item so that financial statements **reflect the economic hedge**.

---

### What changed from IAS 39 (in practice terms)

- No more **80–125% bright-line test**; instead, IFRS 9 asks whether there’s:
  1. an **economic relationship** between hedged item and hedging instrument,
  2. **no domination by credit risk**, and
  3. a **hedge ratio** aligned with risk management (with **rebalancing** allowed).
- **Risk components** of non-financial items can be hedged if **separately identifiable and reliably measurable** (e.g., jet fuel price linked to Brent).
- **Cost of hedging** (time value of options, forward points, currency basis) can be parked in **OCI** and released systematically.

---

### Hedge types (quick map)

| Hedge Type               | What you’re hedging                                                                                                     | Where effective portion goes                                                                                                                                        | Why this makes sense                                                                                   |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| **Fair Value Hedge**     | Change in **fair value** of a **recognised** item (e.g., fixed-rate debt’s interest rate risk) or a **firm commitment** | **P&L** for both: derivative FV change **and** the hedged item’s **FV adjustment**                                                                                  | You’re hedging current value changes; both sides should hit P&L now to reflect risk being neutralised. |
| **Cash Flow Hedge**      | Variability in **future cash flows** (e.g., FX on a forecast purchase, variable interest on floating-rate debt)         | **OCI (cash flow hedge reserve)** for effective portion; later **recycle** to P&L when the hedged cash flows affect P&L (or **basis adjust** a non-financial asset) | You’re hedging future volatility; defer in OCI and release when earnings are affected to align timing. |
| **Net Investment Hedge** | FX exposure of a **net investment** in a foreign operation                                                              | **OCI** (foreign currency translation reserve); recycle to P&L on **disposal**                                                                                      | Mirrors cash flow hedge logic for long-term FX investment exposures.                                   |

---

### Eligibility & designation (what must be documented at inception)

- **Hedged item:** A recognised asset/liability, a **firm commitment**, a **highly probable forecast** transaction, or a **net investment** in a foreign operation. Can be **risk components** if separately identifiable/measurable.
- **Hedging instrument:** Generally **derivatives** (no written options unless they offset purchased options); **non-derivative** instruments allowed **only for FX risk**.
- **Documentation:** Risk management **objective/strategy**, **hedged risk**, **hedged item**, **hedging instrument**, **how effectiveness will be assessed** (methodology, sources of ineffectiveness).
- **Effectiveness (prospective):** Economic relationship; no credit risk dominance; hedge ratio reflects actual risk management (rebalancing if needed).

---

## Accounting mechanics with practical examples

### 1) Fair Value Hedge (fixed-rate debt hedged with an IRS)

**Scenario:**  
Entity A issued **$10,000,000** fixed-rate bonds (5-year, 5% coupon). It uses a **pay-fixed/receive-float interest rate swap** to hedge **interest rate risk** (changes in the debt’s fair value due to rates).

**Period-end result (illustrative):**

- Swap **gain** this period: **$90,000** (rates fell; swap asset up)
- **Fair value change of the hedged risk** on the debt: **$(90,000)** (debt’s value rose; recognise **loss** on hedged item in P&L and **increase the carrying amount** via a **hedge adjustment**)

**Journals:**

_E1. Recognise swap gain in P&L and derivative asset increase_

    Dr Derivative asset (IRS)                 90,000
       Cr Fair value gain on hedge (P&L)                  90,000

_E2. Recognise fair value loss on hedged item in P&L and adjust carrying amount_

    Dr Fair value loss on hedged item (P&L)   90,000
       Cr Bond liability – hedge adjustment                 90,000

> Net P&L effect ≈ 0 if perfectly effective. The bond’s carrying amount now includes a **cumulative hedge adjustment** that will be **amortised** back to profit using EIR (or unwind on derecognition).

**Interest each period:** continue to accrue **coupon** on the bond and **swap net settlements** in P&L; the hedge adjustment amortises over remaining life.

**Why P&L for both?** You’re hedging _current fair value_ volatility; both sides belong in P&L **now**.

---

### 2) Cash Flow Hedge (floating-rate debt fixed with an IRS)

**Scenario:**  
Entity B has **$20,000,000** of **3-month BBSW + 150 bps** debt. It enters a **receive-float/pay-fixed IRS** to **fix** future interest **cash flows**.

**Period-end result (illustrative):**

- Swap fair value **gain**: **$300,000** (effective portion)
- Ineffective portion (e.g., curve basis, timing): **$10,000 loss**

**Journals:**

_C1. Effective portion to OCI (cash flow hedge reserve)_

    Dr Derivative asset (IRS)                300,000
       Cr OCI – cash flow hedge reserve                    300,000

_C2. Ineffective portion to P&L_

    Dr Hedge ineffectiveness (P&L)            10,000
       Cr Derivative asset (IRS)                              10,000

**When the hedged interest cash flows affect P&L (e.g., next quarter):**

_C3. Reclassify OCI to P&L to offset floating interest expense_

    Dr OCI – cash flow hedge reserve         XXX
       Cr Interest expense (P&L)                            XXX

> This **aligns timing**: OCI stores the effective hedge result until the related cash flows hit P&L.

**If hedging a **forecast purchase** of inventory (FX or commodity risk):**  
When the purchase occurs, you may **basis-adjust**:

_C4. Basis adjustment at purchase_

    Dr Inventory / PPE                        YYY
       Cr OCI – cash flow hedge reserve                      YYY

> Then the hedge result flows through **COGS/depreciation** rather than a one-time P&L recycle.

---

### 3) Net Investment Hedge (FX exposure to a foreign subsidiary)

**Scenario:**  
Parent has a **EUR-functional** subsidiary. Parent borrows in **EUR** (or uses a EUR forward) to hedge the **net investment**.

**Period-end result (illustrative):**

- Effective hedge portion (FX gain on borrowing) **$120,000**
- Ineffective portion **$5,000 loss**

**Journals:**

_N1. Effective portion to OCI (FCTR)_

    Dr Borrowing (or Derivative)              120,000
       Cr OCI – foreign currency translation reserve        120,000

_N2. Ineffective portion to P&L_

    Dr Hedge ineffectiveness (P&L)              5,000
       Cr Borrowing (or Derivative)                            5,000

**On disposal of the foreign operation:** reclassify cumulative OCI to P&L.

---

## Cost of hedging (options, forwards, basis)

IFRS 9 allows **separate designation** of certain costs to reduce P&L noise:

- **Time value of options:**
  - If hedging a **transaction-related** item (e.g., a forecast purchase), recognise time value changes in **OCI** and **basis-adjust** the asset on recognition (or amortise to P&L over the hedge period if time-period related).
- **Forward points / currency basis spread:**
  - Account similarly via **OCI (cost of hedging reserve)** and release systematically to match the hedged item.

_Example (option used to hedge a forecast USD purchase):_

    Dr Derivative asset (option)              40,000
       Cr OCI – cost of hedging reserve                     40,000
    (…on purchase of inventory…)
    Dr Inventory                               40,000
       Cr OCI – cost of hedging reserve                     40,000

**Why?** These costs are often viewed as **insurance-like premiums** to achieve protection, better reflected in OCI and matched to the hedged item rather than hitting P&L immediately.

---

## Rebalancing, discontinuation, and ineffectiveness

- **Rebalancing:** If the hedge ratio drifts (e.g., volume changes, basis shifts), adjust the ratio prospectively to maintain an **economic relationship** (avoid intentional imbalance/over-hedging).
- **Discontinuation:** Stop hedge accounting **only** when the **qualifying criteria** are no longer met or the hedge strategy changes; don’t discontinue solely due to temporary ineffectiveness.
- **Ineffectiveness:** Always recognise **ineffective portions in P&L** (FV hedge: via the two P&L legs; CF/NI hedge: ineffectiveness goes directly to P&L when identified).

---

## Common pitfalls (practical)

- **No clear risk component** identification for non-financial items (must be **separately identifiable & reliably measurable**).
- **Hedge ratio ≠ risk management**, creating systematic ineffectiveness (fix via **rebalancing**).
- **Forgetting OCI recycling** (cash flow hedge) or **basis adjustment** when the hedged transaction materialises.
- **Using written options** as hedging instruments (prohibited unless part of a **net purchased option**).
- **Credit risk dominates** (breaks the economic relationship test).
- **Poor documentation** at inception (audits focus here).

---

## Quick policy checklist (for your Confluence page)

- **Document at inception:** objective/strategy, item & risk, instrument, effectiveness methodology.
- **Test prospectively:** economic relationship; no dominance of credit risk; hedge ratio consistent with RM.
- **Measure & record:**
  - **FV hedge:** P&L for derivative and hedged item’s FV change; maintain **hedge adjustment**.
  - **CF hedge:** Effective to **OCI**; **recycle** to P&L or **basis-adjust**; ineffectiveness to **P&L**.
  - **Net investment:** Effective to **FCTR (OCI)**; recycle on **disposal**.
- **Cost of hedging:** Use **OCI** reserve; release to P&L/basis as policy dictates.
- **Rebalance** when needed; **discontinue** only when criteria fail or strategy changes.

---

## Hedge Accounting

- **Objective:** Align hedge accounting with risk management.
- Qualifying relationships:
  - Fair value hedge
  - Cash flow hedge
  - Net investment hedge
- More principles-based hedge effectiveness requirements than IAS 39.

## Disclosure Requirements

Entities must disclose:

- Methods, assumptions, and information used in estimating ECL.
- Credit risk management practices and definitions.
- Quantitative ECL reconciliations (movements between stages).
- Credit quality breakdowns of financial assets.

## Worked Example – ECL Movement

**Scenario:**  
A bank grants a $1m loan at 5% p.a., initially Stage 1. At year-end, borrower credit risk increases significantly (Stage 2).

**Initial Recognition:**

Dr Loan Receivable 1,000,000
Cr Cash 1,000,000

**Stage 1 ECL (12-month expected loss = $10k):**

Dr Impairment Loss (P&L) 10,000
Cr Loss Allowance 10,000

**Stage 2 ECL (Lifetime expected loss = $40k):**
Dr Impairment Loss (P&L) 30,000
Cr Loss Allowance 30,000

## Common Pitfalls

- Using arrears alone for staging decisions.
- Ignoring qualitative risk factors.
- Failing to incorporate forward-looking macroeconomic data.
- Overly simplistic SPPI testing.

---

## Further Reading

- [YouTube: Silvia of CPDbox, IFRS 9 Financial Instruments summary](https://www.youtube.com/watch?v=qFOyyP_po3I&ab_channel=SilviaofCPDbox)
- [YouTube: Nhyira Premium, IFRS 9 Explained: Everything You Need To Know in 10 MINUTES](https://www.youtube.com/watch?v=PDff8SZAQgw&ab_channel=NhyiraPremium)
- [IFRS 9 – IFRS.org](https://www.ifrs.org/issued-standards/list-of-standards/ifrs-9-financial-instruments/)
