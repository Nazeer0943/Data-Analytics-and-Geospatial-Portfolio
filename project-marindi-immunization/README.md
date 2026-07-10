# 📊 Public Health Outbreak Response: Operational Campaign Audit

## 📌 Project Overview
This project evaluates the operational performance and community resistance patterns during a two-round Oral Nyala Vaccine (ONV) immunization campaign in Marindi State. Acting as the Lead Monitoring & Evaluation (M&E) Officer, I engineered an analytical framework in Microsoft Excel to audit multi-tier field data (State > LGA > Ward) and translated complex metrics into an executive strategic briefing for the State Director of Disease Control.

---

## 📋 Case Study Requirements & Scope

The analysis addresses the following core technical and strategic evaluation prompts:

1. **Vaccination Coverage by Round:** Calculate vaccine coverage rates at the state level and for each individual LGA for both Round 1 and Round 2, computing the absolute net change to isolate improving and declining sectors.
2. **Non-Compliance & Resolution Forensics:** Quantify the total population of non-compliant children per round and determine the precise proportion of refusal cases remaining "pending" at the close of field execution windows.
3. **Socio-Behavioral Reason Analysis:** Implement programmatic lookups to dynamically map shorthand localized field codes to descriptive operational and structural barriers without hardcoding text.
4. **Strategic Translation:** Synthesize findings into a high-level executive presentation providing targeted field adjustments, micro-level operational audits, and future community outreach criteria.

---

## 🛠️ Data Audit & Excel Methodology
The analysis was executed strictly through deterministic Excel functions to ensure reproducible auditing logic across two comprehensive data dimensions:

*   **Epidemiological Coverage Metrics:** Automated coverage tracking by mapping localized vaccinations against true demographic target populations across 12 distinct Local Government Areas (LGAs):
    $$\text{Vaccine Coverage} = \frac{\text{Children Vaccinated}}{\text{Target Population}}$$
*   **Non-Compliance & Resolution Forensics:** Programmed a dynamic text-parsing loop using `XLOOKUP` combined with logical error-trapping (`IF`, `ISBLANK`) to seamlessly decode socio-behavioral field boundaries while systematically suppressing blank record errors.

---

## 📈 Key Analytical Insights & Executive Deliverables

### 1. Macro-Level Expansion vs. Micro-Vulnerability
* **The Finding:** Marindi State achieved an overall coverage growth of **+3.66%**, expanding from **92.62%** in Round 1 to **96.28%** in Round 2.
* **The Operational Catch:** While 8 out of 12 LGAs expanded coverage (led by Falpani at **+8.78%**), a critical operational drop was isolated in **Doriga (-8.56%)**, signaling severe localized field execution gaps or cold-chain dropouts despite state-level success.

### 2. Behavioral Shift in Vaccine Hesitancy
* Systematic inter-round household revisits proved highly effective. Field teams achieved a dramatic reduction in pending refusals, dropping the state's pending rate from **30.27%** down to **11.73%**.
* Institutional barriers declined significantly (Religious beliefs dropped **-28.4%**), but **micro-level domestic resistance rose**, with father-led vaccine refusals expanding by **+39.6%** (moving from 106 to 148 cases).

---

## 📂 Repository Deliverables

* 📁 **[Download Fully Formulated Analytical Model (Excel)](./Nazir_Sani_Sol.xlsx)** — *Features comprehensive cell-referencing formulas, XLOOKUP integrations, and data validation layers.*
* 📁 **[View Executive Strategic Briefing (PDF Layout)](./Operational_Campaign_Review_Marindi.pdf)** — *The 5-slide C-suite presentation delivering data-driven field recommendations to senior health directors.*

---
[⬅️ Back to Main Portfolio](../)
