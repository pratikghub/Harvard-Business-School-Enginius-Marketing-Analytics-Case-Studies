# Case Study Title: Zach’s Garage Pricing Strategy

## Case Study Overview
This case study explores **pricing optimization for Zach’s Garage**, a premium car detailing service. The business faces the challenge of setting an **optimal price point** that maximizes profitability while maintaining customer retention and competitiveness.  

Using a structured **marketing analytics approach**, the study evaluates **demand, willingness-to-pay, and revenue implications** of different pricing strategies. The goal is to identify a **data-driven optimal price range** that balances **customer satisfaction, revenue growth, and long-term positioning**.  

---

**Author:** Pratik Ganguli  
**Date:** August 7, 2025  
**University:** University of Auckland  

---

## Table of Contents

1. [Problem Statement](#problem-statement)  
2. [Purpose of the Report](#purpose-of-the-report)  
3. [Methodology](#methodology)  
   - [Gabor-Granger Pricing Method](#gabor-granger-pricing-method)  
   - [Data Collection](#data-collection)  
   - [Model Setup](#model-setup)  
4. [Analysis and Results](#analysis-and-results)  
   - [Revenue Maximization](#revenue-maximization)  
   - [Attendance Drop-off Analysis](#attendance-drop-off-analysis)  
   - [Break-even Pricing Analysis](#break-even-pricing-analysis)  
   - [Segmented Pricing Analysis: Free Youth Entry](#segmented-pricing-analysis-free-youth-entry)  
   - [Segmented Pricing Analysis: Discounted Youth Entry](#segmented-pricing-analysis-discounted-youth-entry)  
5. [Recommendations](#recommendations)  
6. [Conclusion](#conclusion)  
7. [Exhibits](#exhibits)
8. [Repository Contents](#repository-contents)
9. [Acknowledgement](#acknowledgement)
10. [Citation](#citation)

---

## Problem Statement

Zach’s Garage is a grassroots music venue in Chicago, founded by Zachary Lewis, a dark metal fan and accountant. The venue was created to:

- Showcase aspiring musicians without financial barriers  
- Offer free or low-cost access to audiences, particularly students  

Rapid growth has led to financial strain:

- $3,000 monthly deficit  
- Upcoming capital expenses for safety, sound, lighting, and compliance  

Zach must consider **ticket pricing strategies** that maintain inclusivity while ensuring **financial sustainability**.

---

## Purpose of the Report

The report uses **Gabor-Granger analysis** to evaluate ticket pricing for Zach’s Garage. Key business questions:

1. **Revenue Maximization:** What ticket price maximizes expected revenues (250 attendees per event, 12 events per month)? Can it cover the $3,000 monthly cost?  
2. **Demand Sensitivity:** At which price does attendance drop by 50% (from 250 to 125)?  
3. **Break-even Pricing:** Minimum price to cover $3,000 monthly operating costs?  
4. **Segmented Pricing – Free Youth:** Optimal pricing if attendees aged ≤21 enter free?  
5. **Segmented Pricing – Discounted Youth:** Profit-maximizing price for youth if offered a discount instead of free entry?  

---

## Methodology

### Gabor-Granger Pricing Method

- Estimates consumer sensitivity to different ticket prices  
- Survey asks attendees likelihood to attend at 6 price points: **$1, $3, $5, $8, $12, $20**  
- 5-point scale mapped to probabilities:  
  - 1–2 → 0% likelihood  
  - 3 → 10% likelihood  
  - 4 → 40% likelihood  
  - 5 → 100% likelihood  

### Data Collection

- 3,000 potential attendees (12 events × 250 attendees)  
- Demographics collected: age and gender  
- Subsets used for segmented pricing analysis: youth (≤21) vs. adults (22+)  

### Model Setup

- Tool: **Enginius Pricing Optimization**  
- Model: Logit model with ceiling, intercept, linear & logarithmic price terms  
- Parameters:  
  - Market size: 3,000  
  - Fixed costs: $3,000/month  
- Simulation outputs: attendance likelihood, units sold, revenue, gross profit  

---

## Analysis and Results

### Revenue Maximization

| Price | Attendance | Revenue | Gross Profit |
|-------|------------|---------|--------------|
| $1    | 2,591      | $2,591  | -$409        |
| $3    | 1,580      | $4,741  | $1,741       |
| $5    | 856        | $4,280  | $1,278       |
| **$3.31** | 1,439  | $4,768  | $1,768       |

- Optimal single-price ticket: **$3.31**  
- Monthly revenue: $4,768, covering $3,000 costs  
- Attendance: 1,439 per event  
- Balances profit and attendance  

### Attendance Drop-off Analysis

- Attendance drops to 125 (~50%) just below **$3**  
- Demonstrates high **price sensitivity** near the $3 threshold  
- Implication: prices above $3 risk significant attendance loss  

### Break-even Pricing Analysis

- Minimum ticket price to cover $3,000 costs: **$1.45–$1.49**  
- $1 results in loss, $1.50 yields $523 profit  
- Critical **pricing floor** for operational viability  

### Segmented Pricing Analysis – Free Youth Entry

- Youth (≤21) enter free; paying segment = adults (22+)  
- Adult market: 2,000; youth market: 1,000  
- Optimal adult ticket price: **$3.57**  
- Adult gross profit: $659.21; revenue: $3,659  
- Total attendance: 2,024 including free youth  
- Ensures revenue while maintaining youth inclusivity  

### Segmented Pricing Analysis – Discounted Youth Entry

- Youth (≤21) offered **$2.60 ticket**  
- Predicted attendance: 450/1,000 (45%)  
- Youth revenue: $1,167 → treated as gross profit  
- Adult gross profit (from $3.57 adult price): $659  
- **Total gross profit: $1,826.39** → 3.3% higher than single-price model  
- Total attendance: 1,474 (slightly higher than flat pricing)  
- Segmenting enhances both **profit and audience reach**  

---

## Recommendations

1. **Single-Price Model**
   - $1.50 per ticket: covers costs, retains 78.3% attendance  
   - Prioritizes accessibility over maximum profit  

2. **Segmented Pricing (Adults & Youth)**
   - $2.00 adults, $1.00 youth  
   - Covers fixed costs and expands reach  
   - Revenue: $3,806.83 (slightly below profit-maximizing, higher engagement)  

3. **Adults-Only Pricing (Free Youth Entry)**
   - $2.00 for adults aged 22+  
   - Covers costs, increases adult attendance (77.2%)  
   - Maximizes youth inclusivity  

**Key Principle:** Prioritize **financial sustainability, community engagement, and inclusivity** over pure profit maximization.

---

## Conclusion

- Zach should **avoid profit-maximization-only strategies** unless expansion becomes a goal.  
- Recommended pricing models:  
  1. Flat **$1.50** ticket  
  2. Segmented **$2.00/$1.00** adults/youth  
  3. Adults-only **$2.00**, free youth entry  

- Each model ensures:  
  - Operational viability  
  - High audience engagement  
  - Support for local artists  
  - Long-term community trust  

---

## Exhibits

- **Exhibit A1:** Enginius Price Optimization Setup  
- **Exhibit A2:** Revenue & Profit Outcomes Across Prices  
- **Exhibit A3:** Revenue, Cost, Gross Profit Curves  
- **Exhibit A4:** Incremental Price Point Analysis (Break-even & Optimal Prices)  
- **Exhibit B1–B4:** Adult Segment Pricing & Youth Segment Modeling  
- **Exhibit C1–C3:** Youth Segment Pricing and Revenue Curves  
- **Exhibit D1:** Predicted Purchase Likelihood Curve  
## Tools & Techniques
- **Enginius** – Pricing & Conjoint Analysis  
- **Analytics Methods:** Conjoint Analysis, Price Elasticity Modeling, Revenue Simulation, Scenario Analysis  

---

## Repository Contents
- `README.md` – Repository documentation and case study details  
- `ZachsGarageCaseAnalysis_.pdf` – Initial uploaded case study file  
- `ZachsGarage_Case_Study_.pdf` – Final full case study report  

---

## Acknowledgement
- This case study was completed as part of a **Master’s program project** at the **[University of Auckland](https://www.auckland.ac.nz/en.html)**.  
- Special thanks to **Enginius Marketing Analytics** for providing the tools to conduct conjoint and pricing analysis.  
- Data sourced from **customer survey responses and modeled preference data**.  

---

## Citation
Ganguli, P. (2025). *Zach’s Garage Pricing Strategy: A Marketing Analytics Case Study.* University of Auckland.  

---


