# KiranaIQ – AI-Powered Startup Idea Validation

A structured validation of one startup idea: **should it be launched, modified, tested further, or rejected?**

> **Status: Stage 1 – desk research complete. Customer evidence NOT yet collected.**
> Interview and survey rows in the workbook are **DEMO DATA** (structure only, not real research). The current recommendation is **TEST FURTHER** by design, because fewer than 10 real interviews exist.

![KiranaIQ validation dashboard]<img width="1035" height="2076" alt="Dashboard_Full_LinkedIn" src="https://github.com/user-attachments/assets/397af821-3de0-42e7-b925-82e7fa45464c" />


*Dashboard overview. Survey charts use illustrative demo data.*

---

## 🎥 Demo video


https://github.com/user-attachments/assets/7dc2c665-773d-42ba-a5fb-67ecac595ced


**▶ [Watch the 2–3 minute walkthrough](REPLACE_WITH_YOUR_VIDEO_LINK)**

What the video shows: the assumption sheet, sourced market research, TAM–SAM–SOM, competitor positioning, the live dashboard filters, a change to one assumption flowing through unit economics and the 12-month projection, and the final decision logic.

---

## The idea
**KiranaIQ** is a WhatsApp-based AI assistant for kirana (neighbourhood grocery) owners in Tier 2–3 Hindi-belt cities. It tracks udhar (credit), flags likely stock-outs and dead stock, suggests weekly reorders, and sends payment reminders in Hindi.

*We help kirana store owners in Tier 2–3 cities solve stock-outs and uncollected udhar through a Hindi WhatsApp AI assistant.*

## Screenshots

| Overview and market | Customers and competitors | Financials and decision |
|---|---|---|
| <img width="1035" height="771" alt="Dashboard_Slide1" src="https://github.com/user-attachments/assets/d3510a7e-c3d9-4cfc-8b30-ce6644c48d86" />
 | <img width="1035" height="570" alt="Dashboard_Slide2" src="https://github.com/user-attachments/assets/efaa376d-348c-47f9-b09d-6504aeafc144" />
| <img width="1035" height="735" alt="Dashboard_Slide3" src="https://github.com/user-attachments/assets/e023811f-0ca1-4a41-a946-2b385646aadf" />
## Methodology
1. Founder assumption sheet written before research
2. Secondary market research, with every statistic logged with source, year, link and geography
3. TAM–SAM–SOM, bottom-up with a top-down cross-check
4. Competitor analysis, positioning map and gap analysis
5. Feature prioritization (MoSCoW) and a concierge-MVP design
6. Pricing hypotheses, unit economics, break-even (3 scenarios) and a 12-month projection
7. Risk register and a 100-point validation score with an **evidence gate**
8. Excel dashboard with a segment filter and a competitor selector

## Key findings so far
- The segment is large (estimates of 12–20M kirana stores) and ledger apps already exist.
- Core ledgers are largely **free** at incumbents, so ₹0 is the price anchor. Willingness to pay is the biggest open question.
- The differentiator (AI reorder advice) is a **hypothesis**, not a finding.
- Under the base assumptions the model does **not** break even within 12 months (peak cash need ≈ ₹24.3 lakh). These are assumptions, not forecasts.
- Validation score: **37/100** (judgement scores, low confidence). Decision: **TEST FURTHER**.

## Repository structure
```
kiranaiq-startup-validation/
├── README.md
├── KiranaIQ_Startup_Validation_Workbook.xlsx
└── dashboard/
    ├── Dashboard_Full_LinkedIn.png
    ├── Dashboard_Slide1.png
    ├── Dashboard_Slide2.png
    ├── Dashboard_Slide3.png
    
```

## How to use the workbook
1. Open `https://1drv.ms/x/c/1790eeaed48175a5/IQBgvJ6YTUK7QZo8GofbW0JFARYbPFLmUqBrEFIrXhvQiRE?e=RpebcL` in Excel (the charts, dropdowns and formulas work best there).
2. Read the **README** sheet first for the colour legend: blue = editable assumption, black = formula, green = link to another sheet.
3. Change any blue cell (for example churn on `Unit_Economics`) and the projection, break-even and dashboard recalculate.
4. To use it for real: replace the `DEMO` rows in `Customer_Interviews` and `Survey_Data` with your own data and mark them `REAL`. The decision on `Validation_Score` only unlocks GO / MODIFY / NO-GO once 10+ real interviews are logged.

## Workbook sheets
`Founder_Assumptions` · `Customer_Interviews` · `Survey_Data` · `Market_Research` · `TAM_SAM_SOM` · `Competitor_Analysis` · `Feature_Prioritization` · `Pricing` · `Unit_Economics` · `Financial_Projection` · `Risk_Register` · `Validation_Score` · `Dashboard`

## What is real vs assumed
- **Sourced:** market and competitor facts in `Market_Research` and `Competitor_Analysis`, each with a link. Several sources are secondary, undated, or conflict (for example Vyapar pricing); each is marked *Verify*.
- **Assumed:** TAM/SAM/SOM percentages, ARPU, CAC, churn, margin, costs, growth and all scores.
- **Demo:** every row tagged `DEMO` in `Customer_Interviews` and `Survey_Data`.

## Limitations
- No real customer interviews, survey, landing-page or payment data yet.
- Some market statistics are dated, and a few lack a publication year in the retrieved excerpts.
- Competitor review mining is not done (that column is intentionally empty).

## Next steps (30 days)
1. Run 10–15 real interviews with behavioural questions and log them as `REAL`.
2. Verify every *Verify* item and mine 50+ real app-store reviews.
3. Run a WhatsApp concierge demo and a ₹99 pre-register landing test.
4. Offer a paid pilot, update the scores and recalculate the decision.

## Tools
Excel, Google Forms (planned), web research, and AI assistance for drafting (all outputs to be verified).

*Interviewee names and personal data must never be committed to this repository.*
